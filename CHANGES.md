# Flask-Moment change log

**Release 1.0.4** - 2022-07-17

- Add packaging as a dependency [#86](https://github.com/miguelgrinberg/flask-moment/issues/86) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/e7bc9332eff0e78c9312100ad8540e2cdda600a9)) (thanks **Chuxiao Feng**!)

**Release 1.0.3** - 2022-07-16

- Return the raw JavaScript code to enable unsupported use cases [#84](https://github.com/miguelgrinberg/flask-moment/issues/84) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/c79961d46f3b69c7ffc217c2bb35f8289e54b8c4))
- Remove deprecated `StrictVersion` usage [#85](https://github.com/miguelgrinberg/flask-moment/issues/85) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/02a8392876f84c439f548fe639a8890aef0ede97))

**Release 1.0.2** - 2021-07-16

- High CPU usage when refresh is disabled [#81](https://github.com/miguelgrinberg/flask-moment/issues/81) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/7ffce2fea01c25d72b4417b408b6cca5119b8a3e))

**Release 1.0.1** - 2021-06-11

- Fix package metadata for release [#80](https://github.com/miguelgrinberg/flask-moment/issues/80) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/19d601e87eae4c0bd7d34f4734de46b931e8b1b2))

**Release 1.0.0** - 2021-06-11

- Remove dependency on jQuery ([commit](https://github.com/miguelgrinberg/flask-moment/commit/3ab78505303ca5ecf1de1324893918f3b541f2d6)) (thanks **yuxiaoy**!)
- Add `diff()` function [#78](https://github.com/miguelgrinberg/flask-moment/issues/78) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/79d8f43a6f0d31ce9a81d39954bb3f2f08923028)) (thanks **valerii**!)
- Import Markup from markupsafe [#71](https://github.com/miguelgrinberg/flask-moment/issues/71) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/b1c48c41d6783585096003dd22bfd0d121ea306e)) (thanks **jn**!)
- Fix Markup in unit tests [#72](https://github.com/miguelgrinberg/flask-moment/issues/72) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/7566c6b6c2d09ca3b06e3116dd7b5f35ce37b83e)) (thanks **Valerii Tryhubov**!)
- Sphinx documentation ([commit](https://github.com/miguelgrinberg/flask-moment/commit/e9afd81a602cbf1962af307a6d5b5556ee827381))
- Update requirements for example application ([commit](https://github.com/miguelgrinberg/flask-moment/commit/1cdc1f16eed3ad945d2774b925a4f9e2f2a54644))
- Improved project structure ([commit](https://github.com/miguelgrinberg/flask-moment/commit/f79481c84eae62d7d0c8606bfa235f5b223111cf))
- Update links in documentation [#79](https://github.com/miguelgrinberg/flask-moment/issues/79) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/335d3b3cea648f0eb90137b1cdd3840b7cb737ee)) (thanks **Frank Yu**!)
- Unit test reorganization ([commit](https://github.com/miguelgrinberg/flask-moment/commit/e29403f78b326b70445ef4659b42aea29de67604))
- GitHub Actions builds ([commit](https://github.com/miguelgrinberg/flask-moment/commit/1886b76330fd9d1f07985f588ecc5ceaeec5c9fc))
- Fix documentation typos [#74](https://github.com/miguelgrinberg/flask-moment/issues/74) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/13a35e259292666210445018ea72e6d1b0579486)) (thanks **yuxiaoy**!)

**Release 0.11.0** - 2020-12-17

- Update default moment version and hash [#67](https://github.com/miguelgrinberg/flask-moment/issues/67) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/f4ceefbdab6c9dcf1449127e7cdf7a3aa0049da3)) (thanks **Irakliy Krasnov**!)
- Always use `https://` to request the JavaScript files from the CDN [#65](https://github.com/miguelgrinberg/flask-moment/issues/65) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/a8f42fce6b1f50b73694830975a29bb30d95efdd)) (thanks **Vicki Jackson**!)
- Update moment.js and add option to use Moment.js without locales [#63](https://github.com/miguelgrinberg/flask-moment/issues/63) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/5472239042d674809fc62dd3112d52f8154d3ec9)) (thanks **Steven van de Graaf**!)

**Release 0.10.0** - 2020-06-10

- Various code and test improvements, also add python 3.7 and 3.8 to build ([commit](https://github.com/miguelgrinberg/flask-moment/commit/842185179d2b89f895281b0b4077a8eabeba6f83))
- Remove use of JavaScript eval[#60](https://github.com/miguelgrinberg/flask-moment/issues/60) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/5e453fc0e9a0947662ceaa0fca50cab090ca3811)) (thanks **Emilien Klein**!)
- Docs: Fix simple typo, acepted -> accepted [#58](https://github.com/miguelgrinberg/flask-moment/issues/58) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/e506753ffe9d0b5200173f714c0294754b685699)) (thanks **Tim Gates**!)
- Add `toTime` and `toNow` to display functions [#57](https://github.com/miguelgrinberg/flask-moment/issues/57) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/13ba7ee3b0ab8d0e7aa774781ef3b3ec33cad9ce)) (thanks **Mohamed Feddad**!)

**Release 0.9.0** - 2019-08-04

- Updated requirements in example application ([commit](https://github.com/miguelgrinberg/flask-moment/commit/28a5fdbcffcd8b6ed03d9e67bdbf31328b57e2d6))
- Add support of customization object for the method moment.locale [#50](https://github.com/miguelgrinberg/flask-moment/issues/50) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/5b274132604f6e2d8dd5b4c7adb221b17c42c817)) (thanks **Aleksandr**!)

**Release 0.8.0** - 2019-06-16

- Default format [#48](https://github.com/miguelgrinberg/flask-moment/issues/48) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/8786663286806668eab3683458aa3390d505484b)) (thanks **jacobthetechy**!)
- Simplify tests and handling of js versions ([commit](https://github.com/miguelgrinberg/flask-moment/commit/1b273c445957ea507ee23926dfa17be111b74fd7))
- Add SRI v2.0 [#42](https://github.com/miguelgrinberg/flask-moment/issues/42) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/d87eaf8e485757a871928e5248d07a586abfd5fc)) (thanks **M0r13n**!)

**Release 0.7.0** - 2019-02-16

- Added `no_js` argument to `include_moment` ([commit](https://github.com/miguelgrinberg/flask-moment/commit/d99f9ba7c393fa120afff10a9bded11d09a303d5))
- Fix license declaration in setup.py ([commit](https://github.com/miguelgrinberg/flask-moment/commit/243d8e0d523e4f060a7c2cf1ce7b8135bdcefaf1))

**Release 0.6.0** - 2017-12-28

- Fix travis build ([commit](https://github.com/miguelgrinberg/flask-moment/commit/d0468b770d2cbdedf92e051053793c186eb9f6ba))
- Add auto-detect locale support [#33](https://github.com/miguelgrinberg/flask-moment/issues/33) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/32e18b6fc6594ba34281cef04356a5d24bfdf5a2)) (thanks **Grey Li**!)
- Fixed unit tests ([commit](https://github.com/miguelgrinberg/flask-moment/commit/6503a2f53cccba498df9675f3ebceaae01dc5c1c))

**Release 0.5.2** - 2017-09-29

- Bump moment.js version to 2.18.1 ([commit](https://github.com/miguelgrinberg/flask-moment/commit/c412f13e1235ab4ec5f07fd01a8dcf56b9a7ad51))
- Travis build badge ([commit](https://github.com/miguelgrinberg/flask-moment/commit/bbd622383b63892702f337772e45f1443bf610c7))
- A few unit test fixes, plus tox/travis builds ([commit](https://github.com/miguelgrinberg/flask-moment/commit/71f46e56ff60d2ae66f189909de3544d7aca35ec))
- Add tests for the basic features [#28](https://github.com/miguelgrinberg/flask-moment/issues/28) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/e908e2befa456f4fd886845e52060b643b3ecf04)) (thanks **Kyle Lawlor**!)
- Added example of how to setup Flask-Moment using a Flask app factory ([commit](https://github.com/miguelgrinberg/flask-moment/commit/5a27fff48864d7233b05936b54edbc3212f0938d)) (thanks **Jeff Widman**!)
- Switched imports from deprecated `flask.ext.extensionname` format to `flask_extensionname` ([commit](https://github.com/miguelgrinberg/flask-moment/commit/32f8efc9079a5e7eedf05abba72d42ffc806d4c3)) (thanks **Jeff Widman**!)

**Release 0.5.1** - 2015-08-06

- Hide timestamps until rendering is complete [#16](https://github.com/miguelgrinberg/flask-moment/issues/16) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/a5d312f789949e352845dd1f767e98a8e428b3eb)) (thanks **Cole Kettler**!)
- Upgrading the default version to the latest moment.js release(2.10.3) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/56102d5b53c8d2b95b3684661517cc0cb2a6c713)) (thanks **small-yellow-rice**!)

**Release 0.4.0**

- Added `local_js` option to `include_moment()` and `include_jquery()` ([commit](https://github.com/miguelgrinberg/flask-moment/commit/8bd3035ec4d234ac7617e22e46efc06936cd0db2))
- pep8 fixes ([commit](https://github.com/miguelgrinberg/flask-moment/commit/ff63a40e97c91a1432101125c6b26cc40f2b62d2))

**Release 0.3.3**

- Correct fix for [#8](https://github.com/miguelgrinberg/flask-moment/issues/8) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/0d3dcd8a550bb7961d3a1469ed80b24bcf277466))

**Release 0.3.2**

- Correct `include_moment(version=None)` handling [#8](https://github.com/miguelgrinberg/flask-moment/issues/8) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/e59dae390e4fccb30ef761ff18e29803fe3d9e57))

**Release 0.3.1**

- Fixed https support ([commit](https://github.com/miguelgrinberg/flask-moment/commit/1ccf8aec18f3325eb9d74468f904cd10b9c31f27)) (thanks **Tal Shiri**!)

**Release 0.3**

- Added "local" argument to `moment()` constructor to disable conversion from UTC to local time ([commit](https://github.com/miguelgrinberg/flask-moment/commit/3afcbc6290494402b420a0a98bae2be94a7565f1))
- Use secure URLs when request is secure [#2](https://github.com/miguelgrinberg/flask-moment/issues/2) ([commit](https://github.com/miguelgrinberg/flask-moment/commit/0ee69da4408171168c6c0fe84d6f437ab4e8031f))

**Release 0.2**

- First public version 
