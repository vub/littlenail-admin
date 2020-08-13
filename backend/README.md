# Start backend
npm install -g firebase-tools
firebase login
firebase projects:list
firebase open

### Install app
firebase init

### Development
firebase serve
firebase serve --host 0.0.0.0

### Deploy
firebase deploy
firebase deploy --only functions

### Ref
firebase deploy --only hosting (Firebase Hosting content)
firebase deploy --only database (Firebase Realtime Database rules)
firebase deploy --only storage (Cloud Storage for Firebase rules)
firebase deploy --only firestore (Cloud Firestore rules and indexes)
firebase deploy --only firestore:rules (Cloud Firestore rules)
firebase deploy --only firestore:indexes (Cloud Firestore indexes)
firebase deploy --only functions (Cloud Functions for Firebase (more specific versions of this flag are possible))
