json2html
=========

project to convert JSON object into nice html

Use JSOUP 1.7.2 http://jsoup.org
Google Gson 2.2.4https://code.google.com/p/google-gson

The goal is to parse a defined known Jsonified Object and
generate an HTML partial.

The user can choose which HTML element to render.
The Js Object can be mapped with mustache notation {{object.attribute}}

or for more specific frameworks ex AngularJS ng-model="object.attribute"

