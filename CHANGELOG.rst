************
 Change Log
************

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

v0.3.4 - 2018-05-09
-------------------
- Fixed travis deploy collision issue

v0.3.3 - 2018-02-22
-------------------
- Updated long_description so pypi wouldn't fuck me over any more

v0.3.2 - 2018-02-22
-------------------
- Extracted reformat_exception method

v0.3.1 - 2017-12-21
-------------------
- Version bump because pypi is complaining about version conflicts

v0.3.0 - 2017-12-21
-------------------
- Added several examples to show features and complex behavior
- Added decals to README

v0.2.0 - 2017-05-18
-------------------
- Added documentation, hosted on readthedocs, and such

v0.1.12 - 2017-05-17
--------------------
- Added ability to handle only specific exceptions to handle_errors
- Improved exception reporting from within handle_errors

v0.1.11 - 2017-04-19
--------------------
- Added traceback to do_except

v0.1.11 - 2017-04-19
--------------------
- Added ability for handle_errors to absorb exception

v0.1.9 - 2017-02-01
-------------------
- Added traceback print out to handle_errors message
- Added exception class name to handle_errors output

v0.1.8 - 2016-12-30
-------------------
- Added formatted message string to on_error parameters
- Renamed project to 'py-buzz'
- Added error sanitization for messages with embedded curly braces

v0.1.7 - 2016-12-22
-------------------
- Fixed issues with packaging (took a lot of intermediary releases)
- Added accumulating context manager for checking expressions
- Added do_finally and on_error parameters to handle_errors
- Added repr function
- Added testing

v0.1.0 - 2016-12-15
-------------------

Added
.....
- First release of buzz-lightyear
- This CHANGELOG
- README providing a brief overview of the project
