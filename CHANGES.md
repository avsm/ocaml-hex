* Add AFL fuzz testing.

v1.1.0 2017-05-23
-----------------

* Port build to [Jbuilder](https://github.com/janestreet/jbuilder) (#19 @avsm).
* Modernise Travis CI test matrix (#19 @avsm).
* Add `LICENSE` file (#18 @djs55).

v1.0.0 2015-10-13
-----------------

* Fix performance issues: make `of_string` less consy when `ignore` is empty
  (#13, fix by @yallop)
* Add missing `Bytes` dependency (#16)

v0.2.0 2015-05-04
------------------

* Add an `opam` file
* Add Travis CI files
* Add `Hex.of_cstruct` and `Hex.to_cstruct` to converters from and to cstructs
  (#5 by @trevorsummerssmith)
* Add `Hex.hexdump` to pretty-print an hex value (#6 by @trevorsummerssmith)
* Change the optional argument of `Hex.of_string` to take a list of characters
  to ignore (#6 by @trevorsummerssmith)

v0.1.0 2014-09-24
-----------------

* Initial release
