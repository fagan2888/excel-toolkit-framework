# Change Log

All notable changes to this project are documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

v1.3.0 (release candidate 1)
----------------------------
2016-10-31

- Fixed [issue #4][], so the toolkit's menu should work with languages other
  than English.  (Note: still needs verified with a non-English version of
  Excel.)

[issue #4]: https://github.com/mnpopcenter/vba-libs/issues/4

v1.2.0
------
2016-09-30

### Added

- The `CurrentEdition` variable to the `bootstrap.bas` module ([issue #2][]).
- The `BaseFileName` variable to the `toolkit.bas` module ([issue #3][]).

[issue #2]: https://github.com/mnpopcenter/vba-libs/issues/2
[issue #3]: https://github.com/mnpopcenter/vba-libs/issues/3

v1.1.1 
------
2016-09-27

- Added v1.1.0 (and this version) to this Change Log.

v1.1.0 
------
2016-09-26

- Fixed [issue #1][], so file properties can be changed on a toolkit's
  add-in.

[issue #1]: https://github.com/mnpopcenter/vba-libs/issues/1

v1.0.0 
------
2016-05-12

- Initial version with the Simple Toolkit add-in, which illustrates the
  dynamic bootstrapping of VBA modules.