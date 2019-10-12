# REGEX

* [Iran Postal Code](#iranpostalcode)
* [First Name & Last Name](#firstnameandlastname)
* [Iran Mobile Number](#iranmobilenumber)
* [Email](#email)

## IranPostalCode

#### Structure regex
```js
^\d{0,5}[ -]?\d{0,5}$ OR ^\d{5}[ -]?\d{5}$
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

## IranMobileNumber
```js
^[0]?[9][0-9]{9}$
```
[Checkout and Example](https://regex101.com/r/gPDC8x/1)

## Email
```js
^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$
```
[Checkout and Example](https://regex101.com/r/CIKrF5/1)

