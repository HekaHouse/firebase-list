`<firebase-list>` wraps the content of a firebase-collection into an iron-list

    <firebase-list firebase-root="https://YOUR-FIREBASE.firebaseio.com/YOUR-COLLECTION" collected="{{collected}}" route="[[route]]" path="ROUTING-PATH">
    </firebase-list>

In the above examplle replace YOUR-FIREBASE, YOUR-COLLECTION with appropriate values from your Firebase.

ROUTING-PATH should match the URL path used to access this element which triggers the Firebase collection to initialize.
