# REGEX

* [IranPostalCode](#iranpostalcode)
* [FirstnameAndLastname](#firstnameandlastname)


## IranPostalCode

#### Structure regex
```js
^\d{0,5}[ -]?\d{0,5}$
```
[Checkout and Example](https://regex101.com/r/CoGm0i/1)

#### Structure & Content regex
```js
^(?!(\d)\1{3})[13-9]{4}[1346-9][ -]?[013-9]{5}$|^$
```
[Checkout and Example](https://regex101.com/r/gAiZ7F/1)


## FirstnameAndLastname
#### Witout Persian Word
```js
^[A-z]{2,}( [A-z]{2,})+([A-z]|[ ]?)$
```
[Checkout and Example](https://regex101.com/r/wIkoxd/1)

#### With Persian Word
```js
^[آ-یA-z]{2,}( [آ-یA-z]{2,})+([آ-یA-z]|[ ]?)$
```
[Checkout and Example](https://regex101.com/r/gg77DK/1)

