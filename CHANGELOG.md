Changelog
=========

All notable changes to this project will be documented in this file.

<!---
### Added
### Changed
### Deprecated
### Removed
### Fixed
### Security
-->

Unreleased
----------

### Changes

- Updated readme's images with new color scheme
- [#42] xslt file has been splited in three files
- Diagram's targets are surrounded by a rectangle

v1.7.2 - (2018-10-23)
---------------------

### Added 

- Change target background color [#37](https://github.com/jawira/phing-visualizer/issues/37)

### Fixed

- Updated PHPUnit test with `eps` format [#34](https://github.com/jawira/phing-visualizer/issues/34)
- Updated Behat tests with `dummy.xml` 

v1.7.1 - (2018-10-13)
---------------------

### Fixed

- PHPUnit tests fixed

### Updated

- Images in README.md have new color scheme

v1.7.0 - (2018-10-13)
---------------------

### Added

- `phing-visualizer` now supports `eps` format.
- New color scheme for visualization

v1.6.0 - (2018-07-23)
---------------------

### Changed

- Executable can be executed directly without options. Default _format_ and 
default _buildfile name_ has been added.
- Improving ./CONTRIBUTING.md

v1.5.1 - (2018-07-11)
---------------------

### Added

- Adding more examples in readme file, all buildfiles are freely available in 
Gist and Github

v1.5.0 - (2018-07-05) 
---------------------

### Added

- Supporting visualization of RunTargetTask

v1.4.5 - (2018-07-03)
---------------------

### Added

- An help option (-h, --help) was added to executable #12
- Code Climate badges in README.md
- Travis-ci badges in README.md

### Fixed

- Updating Makefile to download latest Phing's version, older version was not 
compatible with current buildfile

v1.4.4 (2018-06-08)
-------------------

### Fixed

* Error loading autoload file was fixed. Executable will work when executing 
from `vendor/bin/phing-visualizer`. #28

### Changed

* Improved README.md

v1.4.0 (2018-03-05)
-------------------

### Added

* Phing visualiser now supports ForeachTask
* Created CONTRIBUTING.md 

### Fixed

* Updating files for test \Jawira\PhingVisualizer\DiagramTest::testGenerateImage

### Changed

* Readme file was updated: badges, installing instructions, example and 
executable usage

v1.3.1 (2017-01-23)
-------------------

### Fixed

* Valid license in `composer.json`  

v1.3.0 (2017-01-13)
-------------------

### Added

* Tests with travis-ci.org & code climate


v1.2.0 (2017-01-11)
-------------------

### Changed

* Improved Unit tests for Diagram class


v1.1.0 (2017-01-08)
-------------------

### Added

* Unit tests for Diagram class
* Phing support

### Changed

* Refactored Diagram class


v1.0.0 (2017-01-02)
-------------------

### Changed

* Renaming project name from `PhingDiagram` to `PhingVisualiser`.
* Updated library usage in Readme file
* Changed signature \Jawira\PhingVisualiser\Diagram::save


v0.0.0 (2017-11-17)
-------------------

### Added

* First functional version
* Executable in `bin` dir
* XSLT file
