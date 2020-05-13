# jitci

Welcome to JitCI - JitPack's CI https://jitci.com

JitCI is an all-in-one solution to publish high quality libraries with ease. It provides the following features:

- Running tests
- Code Coverage
- Dependency Audit
- License Checks
- Vulnerability Reports
- Publishing to a package repository

The idea behind JitCI is simple - make testing and publishing code as easy as possible. At the same time it provides you with insights to help improve your project. All this without extensive setup on your part so you can focus on what matters - providing value to your users

## Test Reports

On JitCI you can see your tests run in real-time and get notified immediately. JitCI tracks tests over time and reports which fail most frequently and which are the slowest.

To achieve this JitCI is tightly integrated with build tools and testing frameworks. Specifically, we understand your build files and use byte code instrumentation in order to track tests in real-time.

Currently supported:
- Build tools: Gradle, Maven
- Test frameworks: Junit 5, Junit 4, KotlinTest, (any test framework based on Junit5).

## Building on push

JitCI works with GitHub webhooks to start builds automatically. To add a webhook manually open:
`https://github.com/USER/REPO/settings/hooks`

And add a new webhook with:
 - Payload Url: https://jitci.com/api/webhooks 
 - Content Type: application/json

## Build Plugins

To publish Android applications we recommend https://github.com/Triple-T/gradle-play-publisher

You can also build docker containers using https://github.com/GoogleContainerTools/jib

## Feedback

Feel free to open an issue with feature requests or bug reports. All feedback is appreciated!

