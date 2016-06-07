# firebase-list

`<firebase-list>` wraps the content of a firebase-collection into an iron-list

[API Docs and Demo](https://heka-house-polymer-demos.firebaseapp.com/firebase-list)

[Source](http://github.com/hekahouse/firebase-list/)

## Install

    bower install --save HekaHouse/firebase-list

## Example

    <firebase-list
      app-name="heka-house"
      app="{{app}}"
      user="{{user}}"
      firebase-branch="/sample"
      route="default"
      path="default">
    </firebase-list>

The Firebase document is initiaized once the user and app properties are provided.

These come from associated firebase-app and firebase-auth elements

## Notes

`route` must match `path` to trigger the Firebase collection to initialize.

These should correspond with the url used to access to ensure lazy loading.

This element uses the `firebase-query` to access data.

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

and uses the pre-release [polymerfire](https://github.com/firebase/polymerfire)
