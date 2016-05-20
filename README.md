# firebase-list

`<firebase-list>` wraps the content of a firebase-collection into an iron-list

[API Docs and Demo](https://heka-house-polymer-demos.firebaseapp.com/firebase-list)

[Source](http://github.com/hekahouse/firebase-list/)

## Install

    bower install --save HekaHouse/firebase-list

## Example

    <firebase-list
      firebase-root="https://YOUR-FIREBASE.firebaseio.com/YOUR-COLLECTION"
      collected="{{collected}}"
      route="[[route]]"
      path="ROUTING-PATH">
    </firebase-list>

In the above example replace YOUR-FIREBASE, YOUR-COLLECTION with appropriate values from your Firebase.

## Note

ROUTING-PATH should match the URL path used to access this element which triggers the Firebase collection to initialize.

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

firebase-list depends on

[firebase-card](https://heka-house-polymer-demos.firebaseapp.com/firebase-card)

and

[firebase-input](https://heka-house-polymer-demos.firebaseapp.com/firebase-input)
