aviary4gradle
=================

This project allows you to build an AAR for importing to Gradle/Android Studio projects.

Build by: ./gradlew assemble

aviary.aar found in build/libs, move to your libs folder

Include in your gradle build with:
dependencies {
    compile files('libs/aviary.aar')
}
