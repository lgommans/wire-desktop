# Wire™

![Wire logo](https://github.com/wireapp/wire/blob/master/assets/logo.png?raw=true)

This repository is part of the source code of Wire. You can find more information at [wire.com](https://wire.com) or by contacting opensource@wire.com.

You can find the published source code at [github.com/wireapp/wire](https://github.com/wireapp/wire).

For licensing information, see the attached LICENSE file and the list of third-party licenses at [wire.com/legal/licenses/](https://wire.com/legal/licenses/).

If you compile the open source software that we make available from time to time to develop your own mobile, desktop or web application, and cause that application to connect to our servers for any purposes, we refer to that resulting application as an “Open Source App”.  All Open Source Apps are subject to, and may only be used and/or commercialized in accordance with, the Terms of Use applicable to the Wire Application, which can be found at https://wire.com/legal/#terms.  Additionally, if you choose to build an Open Source App, certain restrictions apply, as follows:

a. You agree not to change the way the Open Source App connects and interacts with our servers; b. You agree not to weaken any of the security features of the Open Source App; c. You agree not to use our servers to store data for purposes other than the intended and original functionality of the Open Source App; d. You acknowledge that you are solely responsible for any and all updates to your Open Source App.

For clarity, if you compile the open source software that we make available from time to time to develop your own mobile, desktop or web application, and do not cause that application to connect to our servers for any purposes, then that application will not be deemed an Open Source App and the foregoing will not apply to that application.

No license is granted to the Wire trademark and its associated logos, all of which will continue to be owned exclusively by Wire Swiss GmbH. Any use of the Wire trademark and/or its associated logos is expressly prohibited without the express prior written consent of Wire Swiss GmbH.

## Wire Desktop

Cross platform desktop app, wrapping the [wire-webapp](https://github.com/wireapp/wire-webapp).
Based on [Electron](http://electron.atom.io).

### Install

Install [Node.js](https://nodejs.org/).

### Clone

```shell
git clone https://github.com/wireapp/wire-desktop.git
cd wire-desktop
npm install
```

### Start

```shell
npm start
```

### Test

```shell
npm test
```
### Enable Support for Google Contacts (optional)

If you wish to import Google Contacts to Wire, you will need to [generate Google OAuth 2.0 credentials](https://console.developers.google.com/apis/credentials/oauthclient) for an "other" type app ([See here](https://developers.google.com/identity/protocols/OAuth2) for more details). Once you have generated your credentials, store the "Client ID" and "Client secret" in the environment as `GOOGLE_CLIENT_ID` and `GOOGLE_CLIENT_SECRET`, respectively.

### Tasks

```shell
# Build for macOS
npm run build:macos

# Build for Windows
npm run build:win

# Build for Linux
npm run build:linux
```

### Troubleshooting

If you are having troubles building Wire for Desktop, then [our troubleshooting page](https://github.com/wireapp/wire-desktop/wiki/Troubleshooting) might be of help.

### Translations

All Wire translations are crowdsourced via [Crowdin](https://crowdin.com/projects/wire).
