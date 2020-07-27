# CAD_AR_Uploader
HTML upload page to Firebase storage for CAD_AR application
Web interface for uploading GLB files too Firebase Storage

CAD_AR_Uploader

Simple HTML upload page to Firebase storage for CAD_AR application.

Uploads and clears files to personal firebase storage that is linked to the AR application.

GLB files can then be run straight from the firebase storage.

To link the uploader to your own Firebase Storage you must enter the storage details that are available from the Firebase console and replace this section with your own:

var firebaseConfig = {

apiKey: "",

authDomain: "",

databaseURL: "",

projectId: "",

storageBucket: "",

messagingSenderId: "",

appId: "",

measurementId: ""

}
