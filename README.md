# KotlinMPErroSample
A kotlin MP sample to reproduce some problems.

## IDE
IntelliJ IDEA 2019.2.4 (Community Edition)

## About This Project
This project is created from IDEA template: __Kotlin Mobile Android/iOS | Gradle__

## Problem
I added the dependency `com.squareup.okio:okio-multiplatform:2.4.0` in app/build.gradle. This time the gradle sync successful, but the dependency isn't resolved really. If you download and sync this project, you will find that there is no Okio library under __External Libraries__ . And you also cannot use Okio in __app/src/commonMain__ .
