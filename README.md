# jitci

Welcome to JitCI - JitPack's CI https://jitci.com
This repository is for documentation and issue tracking of the project. We will be updating the documentation as the project evolves.

## Building on push

JitCI works with GitHub webhooks to start builds automatically. To add a webhook manually open:
`https://github.com/USER/REPO/settings/hooks`

And add a new webhook with:
 - Payload Url: https://jitci.com/api/webhooks 
 - Content Type: application/json

