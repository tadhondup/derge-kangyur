# Digital Derge Kangyur (eKangyur)

Digital Derge Kangyur prepared by Esukhia in 2013 for [84000](http://84000.co/) and [SOAS](https://www.soas.ac.uk/) under the supervision of [TBRC](https://www.tbrc.org/) and [UVA](http://www.virginia.edu/).

## Background
...

## Methodology
This digital version of the Derge Kangyur, or eKangyur as it is called on tbrc.org, is intended as an exact representation of the Derge Kangyur edition help by the Library of Congress ([available on BDRC](https://www.tbrc.org/#!rid=W4CZ5369)). As an exact representation it preserved the likes of spelling mistakes, carving mistakes, archaic spellings and mistakes caused by wood-block damage.

This digital version isn't a new manual input but rather the result of comparing 4 different previous digital version. This process was chosen in order to minimize the creation of new errors, but of course you might still find some.

For more information on the workflow please refer to:
* [Project Descrition](https://docs.google.com/document/d/17RGGczT9bZl5Hoy7Z6Avo-xympw6eFDeHlecrdVadkM/edit?usp=sharing)
* [Compared-Proofreading Workflow](https://docs.google.com/document/d/1BobLBqSRvyOCissiYx9kCprbJsU5YDFpKf0NzPkX_Aw/edit?usp=sharing)

## Format

The texts contain the following structural markup:

* [1b] _[Page and folio markers]_
* [1b.1] _[Page and folio markers.line number]_

They also contain a few error suggestions noted as example. It is far from an exhausted list of the issues found in the original, the staff was actually discouraged to add these.

* (མི,མེ) _potential error, correction suggestion (མཁའ་ལ་(མི,མེ)་ཏོག་དམར་པོ)_

* [རྔེའུ་] _signals obvious errors (རྔེའུ་ for རྡེའུ་), highly suspicious spellings (མཎྜལ་ཐིག་[ལ]་ལྔ་པ་ལ།), un-transcribable characters (གྷ་ཀྷཱ་ཀྤ་ཀྻཱ་ཀྼ་ཀླ་[]ཀྷཾ་ཀྷཿ) _

* The ང། don't have a tsek between the ང and the །.

## Feedback

The files are on github hoping they'll improve, don't hesitate to signal errors with a pull request!

## Technical details

The files are UTF16-LE with BOM. `git` doesn't recognize them as text but you can still diff them with the trick exposed [here](https://stackoverflow.com/a/1300928/2560906).

# License

This work is a mechanical reproduction of a Public Domain work, and as such is also in the Public Domain.
