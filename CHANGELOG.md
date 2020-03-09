# Release Notes for CKEditor for Craft CMS

## 1.1.0 - 2020-03-09

### Changed
- Added the @ckeditor/ckeditor5-table plugin
- Added changes from https://github.com/sokolovstas/ckeditor/commit/ad1f1445080e8148ee6e3981e9a972be98952c74
- CKEditor fields’ default HTML Purifier config now allows `id` attributes. ([craftcms/redactor#82](https://github.com/craftcms/redactor/issues/82))

### Fixed
- Fixed a deprecation error when running CKEditor on Craft 3.0.0-RC15 or later.
- Fixed a bug where an empty CKEditor field would return some HTML content.

## 1.0.0-beta.2 - 2018-01-15

### Changed
- Improved the field content legibility.

### Fixed
- Fixed a bug where lists were’t getting indented, and were missing their bullets/numerals. ([#1](https://github.com/craftcms/ckeditor/issues/1))

## 1.0.0-beta.1 - 2017-12-04

Initial release.
