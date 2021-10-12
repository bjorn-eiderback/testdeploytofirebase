# testdeploytofirebase

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Deploy to Firebase
https://learning.oreilly.com/library/view/flutter-cookbook/9781838823382/a7aa89fb-2f1c-4f05-8f02-d1dd49bb167d.xhtml#uuid-ded46ee1-824e-4832-95bb-24b8542e3a45

### Deployed
* Project Console: https://console.firebase.google.com/project/flutterhellotest/overview
* Hosting URL: https://flutterhellotest.web.app

### Process and commands
Open your browser and go to the Firebase console at the address https://console.firebase.google.com.
<br />Create a new Firebase project (you can also use an existing one).


<pre>
~/tests/flutter/testdeploytofirebase>firebase login
...
~/tests/flutter/testdeploytofirebase>firebase init

     ######## #### ########  ######## ########     ###     ######  ########
     ##        ##  ##     ## ##       ##     ##  ##   ##  ##       ##
     ######    ##  ########  ######   ########  #########  ######  ######
     ##        ##  ##    ##  ##       ##     ## ##     ##       ## ##
     ##       #### ##     ## ######## ########  ##     ##  ######  ########

You're about to initialize a Firebase project in this directory:

/Users/bjorne/tests/flutter/testdeploytofirebase

? Which Firebase features do you want to set up for this directory? Press Space to select features, then Enter to confirm your choices. Hosting: Configure files for Firebase Hos
ting and (optionally) set up GitHub Action deploys

=== Project Setup

First, let's associate this project directory with a Firebase project.
You can create multiple project aliases by running firebase use --add,
but for now we'll just set up a default project.

? Please select an option: Use an existing project
? Select a default Firebase project for this directory: flutterhellotest (FlutterHelloTest)
i  Using project flutterhellotest (FlutterHelloTest)

=== Hosting Setup

Your public directory is the folder (relative to your project directory) that
will contain Hosting assets to be uploaded with firebase deploy. If you
have a build process for your assets, use your build's output directory.

? What do you want to use as your public directory? build/web
? Configure as a single-page app (rewrite all urls to /index.html)? No
? Set up automatic builds and deploys with GitHub? No
✔  Wrote build/web/404.html
? File build/web/index.html already exists. Overwrite? No
i  Skipping write of build/web/index.html

i  Writing configuration info to firebase.json...
i  Writing project information to .firebaserc...

✔  Firebase initialization complete!
~/tests/flutter/testdeploytofirebase>firebase deploy

=== Deploying to 'flutterhellotest'...

i  deploying hosting
i  hosting[flutterhellotest]: beginning deploy...
i  hosting[flutterhellotest]: found 16 files in build/web
✔  hosting[flutterhellotest]: file upload complete
i  hosting[flutterhellotest]: finalizing version...
✔  hosting[flutterhellotest]: version finalized
i  hosting[flutterhellotest]: releasing new version...
✔  hosting[flutterhellotest]: release complete

✔  Deploy complete!

Project Console: https://console.firebase.google.com/project/flutterhellotest/overview
Hosting URL: https://flutterhellotest.web.app
~/tests/flutter/testdeploytofirebase>
</pre>