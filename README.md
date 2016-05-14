`<firebase-list>` wraps the content into a flexwrap container and provides a Firebase collection

    <firebase-list firebase-root="https://YOUR-FIREBASE.firebaseio.com/YOUR-COLLECTION" collected="{{collected}}" route="[[route]]" path="ROUTING-PATH">
      <template is="dom-repeat" items="[[collected]]" as="item">
        <firebase-card
          firebase-root="https://YOUR-FIREBASE.firebaseio.com/YOUR-COLLECTION/"
          document-key="{{item.__firebaseKey__}}"
          fire-document="{{fireDocument}}">
          <paper-input label="SOME-PROPERTY" value="{{fireDocument.SOME-PROPERTY}}"></paper-input>
          <paper-input label="SOME-OTHER-PROPERTY" value="{{fireDocument.SOME-OTHER-PROPERTY}}"></paper-input>
        </firebase-card>
      </template>
    </firebase-list>

In the above examplle replace YOUR-FIREBASE, YOUR-COLLECTION, SOME-PROPERTY, SOME-OTHER-PROPERTY with appropriate values from your Firebase.

ROUTING-PATH should match the URL path used to access this element which triggers the Firebase collection to initialize.
