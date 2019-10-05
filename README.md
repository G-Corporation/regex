# REGEX

* [Iran Postal Code](#iranpostalcode)


## IranPostalCode

#### Structure regex
```js
^\d{0,5}[ -]?\d{0,5}$
```
[Checkout and Example](https://regex101.com/r/qnJ1Ka/1)

#### Structure & Content regex
```js
^(?!(\d)\1{3})[13-9]{4}[1346-9][ -]?[013-9]{5}$|^$
```
[Checkout and Example](https://regex101.com/r/munDmh/1)
