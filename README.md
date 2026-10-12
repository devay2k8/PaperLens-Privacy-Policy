# PaperLens Privacy Policy

Last updated: 12 October 2026

This policy covers the PaperLens PDF reader and editor on Android and Windows. For privacy questions, contact [pdnexus.apps@gmail.com](mailto:pdnexus.apps@gmail.com).

## Documents and processing

PaperLens reads, edits, searches, converts, scans, and exports files on your device. PaperLens does not operate an account or document-upload server. You choose the files to open and where to save or share outputs. If you choose a file from a cloud-storage provider, that provider may download it under its own terms. If you explicitly share an output with another app, that app handles its copy under its own policy.

On Android, PaperLens requests camera access when you choose to scan. Recognition of document text uses bundled on-device English and Devanagari models. On Windows, OCR uses the bundled local Tesseract runtime. The optional Windows Assistant can send selected document evidence to a separately installed Ollama service on your own computer when you enable that local provider. PaperLens does not send document content to an online AI service in the current build.

## Information stored on your device

On Android, PaperLens stores recent-document references and preferences on the device. You can clear recent entries in the app and remove app data in Android settings. Android backup is disabled for PaperLens.

On Windows, PaperLens stores settings, recent file paths, reader state, notes, and bookmarks in the app's local `data` folder. If local recovery is enabled, temporary work files may also be stored there. Uninstalling the Windows app may leave this user-data folder in place so your data is not removed unexpectedly; you can delete it yourself when you no longer need it.

## Android ML Kit diagnostics

The bundled Google ML Kit text-recognition SDK may collect technical information such as device and app details, installation identifiers, performance metrics, feature events, and error codes for diagnostics and usage analytics. Google states that this data is encrypted in transit. See [Google's ML Kit data disclosure](https://developers.google.com/ml-kit/android-data-disclosure). PaperLens does not run its own advertising or analytics service.

## Feedback and support

When you choose Send feedback on Android, PaperLens opens your email app with its support address, app version, device model, and Android version in a draft. On Windows, the feedback dialog opens a draft containing the message you wrote and the app version. You review and choose whether to send it. PaperLens does not send feedback automatically or attach a PDF. Your email provider processes a message only if you choose to send it.

## Accounts, advertising, and policy website

PaperLens does not require an account and does not include an advertising SDK or ad banner. This policy is published in a public GitHub repository. Visiting the policy link sends a website request to GitHub, which handles website access information under [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

## Changes

This page will be updated when PaperLens's data handling changes. The date above identifies the latest policy revision.

