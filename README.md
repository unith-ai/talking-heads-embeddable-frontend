# Talking Heads Embeddable UI

## What it does

With this bundled files you can easily embed the talking heads ui in any website of your choice.

## Necessary files

In order for the UI to work on your server, three files need to be downloaded and added yo the HTML code.

#### javascript bundle

This contains the functional part of the application. You can choose to always use the latest version or keep using a version that you like.

The possible bundle names are:

- latest.js
- `version`.js (you can check the available versions in the changelog)

#### css bundle

This contains the styling of the aplication. As in the javascript bundle, you can choose to always use the latest version or keep using a version that you like. **Make sure to use the same version in both bundles.**

The possible bundle names are:

- latest.css
- `version`.css (you can check the available versions in the changelog)

#### microsoft sdk

This contains the speech recognition functionality. The name is:

- microsoft-speech-sdk.js

## Integration

To fully integrate the component on your webpage, you will need to download all these three files from our server.

Then, you will need an html element that will have the id set to `talking-head`.

**Note**: you can replace `latest` with the version of your choice.

```html
<!-- JavasScript bundle -->
<script defer src="https://talk.crowdmedia.com/bundle/latest.js"></script>

<!-- CSS bundle -->
<link rel="stylesheet" href="https://talk.crowdmedia.com/bundle/latest.css" />

<!-- Microsoft speech recognition bundle -->
<script src="https://talk.crowdmedia.com/bundle/microsoft-speech-recognition.js"></script>

<!-- Body containing element with id="talking-head" -->
<body>
  <div
    id="talking-head"
    data-org_id="your org id"
    data-head_id="your head id"
    data-theme="light"
    data-language="en-US"
    data-font="Nunito"
    data-time_pressure="true"
  ></div>
</body>
```

# Configure your head

We provide some configuration options, that you can add inside the element containing the id="talking-head".

- `data-org_id`: Your org id (required)
- `data-head_id`: Your head id (required)
- `data-theme`: light or dark (default is light)
- `data-language`: used for speech recognition and UI elements (default is en-US). If you need a language we do not support, contact us.
- `data-font`: A font of your choice. Note: you will need to have this font available in your current frontend. (default is Nunito)
- `data-time_pressure`: choose if you wish to show the counter timer to the user.
