# aspectj.gradle
Fork of official the aspectj plugin for gradle


Usage
-----

Something like this:

```groovy
buildscript {
    repositories {
        maven {
            url "https://s3-eu-west-1.amazonaws.com/gskillz-maven-repo"
        }
    }

    dependencies {
        classpath "aspectjfork:gradle:1.1-SNAPSHOT"
    }
}

project.ext {
    aspectjVersion = '1.9.3'
}

apply plugin: 'gradle.aspectjfork'
```
