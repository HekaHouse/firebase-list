# firebase-login
`<firebase-login>` is a firebase login prompt presented in a paper-dialog

    <firebase-login firebase-root="https://YOUR-FIREBASE.firebaseio.com"></firebase-login>

After authentication a <a href="https://elements.polymer-project.org/elements/paper-fab">paper-fab</a> logout button is displayed in lower right corner

Authentication triggers an <a href="https://elements.polymer-project.org/elements/iron-signals">iron-signal</a> to fire named <i>logged-in</i> with the users uid as the data property

Depends on <a href="https://github.com/hejty/social-media-icons">social-media-icons</a>

Currently supports logging in with Google, Facebook, and Twitter.

To learn how to configure Firebase authentication visit <a href="https://www.firebase.com/docs/web/guide/user-auth.html">the docs</a>.
