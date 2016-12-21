# \<firedb\>

Sample using firebase DB

## Setup Firebase
Configure the firebase app in [firebase-config.html](https://github.com/craigivy/polymer-edu/blob/master/firedb/src/firedb-app/firebase-config.html)

Setup the database roles to read and write without authorization.  This can be done in the firebase console
````
// These rules give anyone, even people who are not users of your app,
// read and write access to your database
{
  "rules": {
    ".read": true,
    ".write": true
  }
}
````

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```