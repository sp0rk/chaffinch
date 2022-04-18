# Secrets

| Name            | Description                            | Definitions                                         | Uses                                   | 
|-----------------|----------------------------------------|-----------------------------------------------------|----------------------------------------|
| PORT            | HTTP port for heroku api deployment    | Heroku dashboard                                    | api: embeddedServer                    |
| jitpackToken    | Token for private Jitpack dependencies | $HOME:.gradle/gradle.properties<br>Heroku dashboard | api: build.gradle<br>and: build.gradle |
| FIREBASE_APP_ID | Firebase app id from Firebase Console  | and: Github actions secret                          | and: qaDeploy action                   |
| FIREBASE_TOKEN  | Firebase token from firebase cli       | and: Github actions secret                          | and: qaDeploy action                   |
