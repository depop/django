# Change Log
All notable changes to this project will be documented in this file.

## [Unreleased]
* No Changes yet!

## [1.4.22-depop4]
### Added
* Update version tracking and add 'post' to version (1.4.22.post4)

## [1.4.22-depop3]
### Added
* Update version tracking and add 'depop' version (1.4.22d3)

## [1.4.22-depop2]
### Added
* Backported regex for locale parsing from django 1.5.12
* Implemented change in utils/translation/trans_real.py to allow parsing es-419
* Calls to parse_accept_lang_header will now return non empty for es-419

## [1.4.22-depop1]
### Security
* Implemented fix in django/utils/http.py.
* Updated function \_is\_safe\_url to patch currently vulnerable is_safe_url.
* 1.8.x fix contains updates to test cases, however those are not part of the
  1.4.22 codebase.

[Unreleased]: https://bitbucket.org/depop/django-fork/branches/compare/HEAD%0D1.4.22-depop1
[1.4.22-depop1]: https://bitbucket.org/depop/django-fork/branches/compare/1.4.22-depop1%0D1.4.22
