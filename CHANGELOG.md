# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [0.4.2] - 2018-01-31
### Added
* Adds persistant Cookie Storage when accepting Cookie Consent Message. Added by [Kobes](https://github.com/Kobes).


## [0.4.1] - 2018-01-30
### Added
* Fixes dependency issue so site bundles all required dependencies. Adds default portfolio_type to avoid error regaridng missing file. [issue #15](https://github.com/jameshamann/jekyll-material-theme/issues/15).
* Adds RSpec/Capybara for Testing
* Adds CircleCI for build pipeline




## [0.4.0] - 2018-01-29
### Added
* Adds dynamic portfolio_heading and fixes project_button [issue #14](https://github.com/jameshamann/jekyll-material-theme/issues/14). Added by [Kobes](https://github.com/Kobes).


## [0.3.0] - 2018-01-19
### Added
* Adds Tools and Experience Section [issue #11](https://github.com/jameshamann/jekyll-material-theme/issues/11)


## [0.2.0] - 2018-01-16
### Added
* Fixes [issue #9](https://github.com/jameshamann/jekyll-material-theme/issues/9)
* Adds Portfolio Cards [issue #8](https://github.com/jameshamann/jekyll-material-theme/issues/8)



## [0.1.2] - 2018-01-09
### Added
* Fixes [issue #5](https://github.com/jameshamann/jekyll-material-theme/issues/5) regarding baseurl, where assets weren't being loaded correctly. Ensure the <b>url</b>: field within the ```_config.yml``` does not have a trailing "/". Fixed by [jameshamann](https://github.com/jameshamann) and [jamrizzi](https://github.com/jamrizzi). For example:

  * ```url: http://example.com``` :white_check_mark:

  * ```url: http://example.com/``` :x:


* Updates year on Copyright Footer to 2018.


## [0.1.1] - 2018-01-08
### Added
* Added Changelog
* Fixes [issue #3](https://github.com/jameshamann/jekyll-material-theme/issues/3) where assets were not being correctly loaded on Github Pages. Fixed by [jamrizzi](https://github.com/jamrizzi).
* Fixes contact form issue where the message body wasn't being sent as part of the submission.


## 0.0.1 - 2017-12-07
### First Release
