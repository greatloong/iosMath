## Changelog

### v0.8.4 (2016-08-10)
* Fix crash for \\epsilon and \\varrho
* Add commands: \\mho, \\angstrom and \\AA

### v0.8.3 (2016-07-31)
* Add `textColor` field to `MTMathUILabel` to set the color of the
  rendered equation.
* Fixed issue with height of tall radicals set incorrectly.

### v0.8.2 (2016-07-23)
* Support for \\overline and \\underline
* Includes math spacing: \\, \\; \\> \\! \\quad \\qquad \\' '

### v0.8.1 (2016-07-17)
* Added support for binomials
* New commands supported: \\over, \\atop, \\choose, \\brack, \\brace,
  \\binom.

### v0.8.0 (2016-07-09)
* Added support for \\left and \\right
* New API for constructing `MTMathList`
* Improved LaTeX error reporting
* Made internal rendering functions and APIs private
* Nullability annotations for using with Swift
* Improved documentation
* Tests for rendering

### v0.7.3 (2016-05-28)
* Moved all font-related files into their own bundle.

### v0.7.2 (2016-05-27)
* Added `MTMathListIndex`

### v0.7.1 (2016-05-25)
* Improved documentation.
* Added `latex` property to set the latex directly on MTMathUILabel.
* Improved error handling.

### v0.7.0 (2016-05-24)

* Support for multiple fonts.
* Includes large operators (\\sum, \\prod)
* Includes arrow symbols
* Includes showing limits (\\lim etc.)
* Includes integrals
* Added italic correction

#### API Changes:
The `MTFontManager` API has been rewritten.
Introduce `MTFont` class to represent a font for the label.

This release contains backwards incompatible API changes.

### v0.6.3 (2016-05-15)
* Include `MTFontManager` in public API.

### v0.6.2 (2016-05-13)
* Fix issues with Greek letters being incorrect.
* Many common math symbols added.
* Improved example program.
* Minor rendering fixes.

### v0.6.1 (2016-05-12)
* Fix the bundle to work correctly with Cocoapods.

### v0.6.0 (2016-05-12)
* Inital public release.

