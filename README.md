# WebToApk Egaa — Android build pipeline

This repository holds the Android WebView template and the GitHub Actions
workflow used by the **WebToApk Egaa** web app to build real APK files.

Builds are triggered with `workflow_dispatch` and published as GitHub Releases
tagged `build-<build_id>`.
