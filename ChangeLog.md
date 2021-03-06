## 0.6.0

* Export `show` from `Show` typeclass, and rename current `show` to `tshow` [#67](https://github.com/snoyberg/basic-prelude/issues/67)

## 0.5.2

* Expose `bool`

## 0.5.1

* Expose `asum`
* Deprecate `empty` (so it can be replaced with `Alternative`'s `empty`)

## 0.5.0

* Expose more Foldable/Traversable stuff

## 0.4.1

* terror

## 0.4.0

* Drop system-filepath

## 0.3.13

* Export converters between FilePath <-> Text, String. [#56](https://github.com/snoyberg/basic-prelude/pull/56)

## 0.3.12

* Add `fromShow` [#55](https://github.com/snoyberg/basic-prelude/pull/55)

## 0.3.11

* [Generalize `print`](https://github.com/snoyberg/basic-prelude/pull/51)

## 0.3

* Moved a number of exports from @BasicPrelude@ to @CorePrelude@ and vice-versa.

## 0.2

* Renamed `BasicPrelude` to `CorePrelude` and added a new @BasicPrelude@ module
provided a full-featured `Prelude` alternative. Also added a number of new
exports.

## 0.1

* Initial version, code taken from @classy-prelude@ with a few minor tweaks.
