# This is a Text/File Editor Desktop Application built with ElectronJS

## Application Overview

### There is a two step process for getting things running.
- You first have to start the basic React Application via Yarn.
- Second, you have to open a new Terminal window in the same project folder (preferably in the root of the app) and start ElectronJS via Yarn.
- You'll notice the the React Application's web page that's displayed in the browser window, will show an error. That's OK and intended for the time being. This is a Desktop application and the window you'll work from will be one generated through starting the Electron app itself.
- Upon starting the Electron application, a window will populate on your Desktop. Electron uses Chromium as for its UI (which means Google DevTools is built in!).
- Below are the commands for starting up the application.

## Application Startup

Clone the app locally:

```bash
git clone https://github.com/harlemtraveler/Logger-Journaling-Application.git
```

cd into the application

```bash
cd Logger-Journaling-application
```

Install yarn dependencies

```bash
yarn Install
```

Install ElectronJS

```bash
yarn add --dev electron
```

Start the React Web Application

```bash
yarn start
```

In Terminal, open a new window.

```bash
CmdOrCtrl+T
```

Within the same app directory (root of Logger-Journaling-application), start the Electron application

```bash
yarn electron
```

You should automatically be navigated to your Desktop, where a new window displaying the app UI will populate!
