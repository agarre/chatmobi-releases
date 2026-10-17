# ChatMobi desktop — releases

Installers of the ChatMobi desktop app. Nothing is built here: each release is published by
the release workflow of the app's repository when a `v<version>` tag is pushed there.

Installed apps check `https://agarre.com.br/chatmobi/navegador/`, which redirects to the
latest release of this repository, and install an update only when its `.sig` (Ed25519, over
the version and the setup's SHA-512) matches a key built into the app.

Download the current installer:
https://agarre.com.br/chatmobi/navegador/latest.yml lists it; the setup is
`ChatMobi-Setup-<version>.exe` in the latest release.
