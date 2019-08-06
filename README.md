# jitci

Welcome to JitCI - JitPack's CI https://jitci.com

JitCI is an all-in-one solution to publish high quality libraries with ease. It provides the following features:

- Running tests
- Code Coverage
- Dependency Audit
- License Checks
- Vulnerability Reports
- Publishing to a package repository

You can enable the CI from project settings on JitPack or simply sign-in on jitci.com and add your repository.

## Building on push

JitCI works with GitHub webhooks to start builds automatically. To add a webhook manually open:
`https://github.com/USER/REPO/settings/hooks`

And add a new webhook with:
 - Payload Url: https://jitci.com/api/webhooks 
 - Content Type: application/json

## Feedback

Feel free to open an issue with feature requests or bug reports. All feedback is appreciated!

