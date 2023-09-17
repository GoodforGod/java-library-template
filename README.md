# java-library-template

[![Minimum required Java version](https://img.shields.io/badge/Java-11%2B-blue?logo=openjdk)](https://openjdk.org/projects/jdk/11/)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.goodforgod/java-library-template/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.goodforgod/java-library-template)
[![GitHub Action](https://github.com/goodforgod/java-library-template/workflows/CI%20Master/badge.svg)](https://github.com/GoodforGod/java-library-template/actions?query=workflow%3A"CI+Master"++)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=GoodforGod_java-library-template&metric=coverage)](https://sonarcloud.io/dashboard?id=GoodforGod_java-library-template)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=GoodforGod_java-library-template&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=GoodforGod_java-library-template)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=GoodforGod_java-library-template&metric=ncloc)](https://sonarcloud.io/dashboard?id=GoodforGod_java-library-template)

Template for Java library.

## Features
- Spotless for Code Style and Formatting.
- .gitignore and .gitattributes for proper ignore and symbols check.
- .editorconfig for simple configs code style and encoding UTF-8.
- Proper Gradle and Gradle Wrapper configuration.

## GitHub Actions

Required Environment variables:
- OSS_GITHUB_TOKEN - GitHub package release token with `package write & read permissions`.
- OSS_USERNAME - OSS username.
- OSS_PASSWORD - OSS password.
- OSS_SIGNING_KEY - OSS signing key in ASCII armor.
- OSS_SIGNING_PASSWORD - OSS key decrypt password.
- SONAR_TOKEN - sonar token.