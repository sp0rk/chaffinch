# Secrets

| Name         | Description                            | Definitions                                         | Uses                                   | 
|--------------|----------------------------------------|-----------------------------------------------------|----------------------------------------|
| PORT         | HTTP port for heroku api deployment    | Heroku dashboard                                    | api: embeddedServer                    |
| jitpackToken | Token for private Jitpack dependencies | $HOME:.gradle/gradle.properties<br>Heroku dashboard | api: build.gradle<br>and: build.gradle |
