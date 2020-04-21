# All Credits to [jtpio](https://github.com/jtpio/)

# Just a copy of [jupyterlab-logout](https://github.com/jtpio/jupyterlab-logout) with another URL

# jupyterlab-control

Control Panel Button for JupyterLab

![screenshot](./doc/screenshot.png)

## Additional configuration

Button leads to /user/<user_name>/<lab_name>/home. Additional redirect rule in proxy is required, to actually send the user to the ControlPanel.

## Prerequisites

* JupyterLab

## Installation

```bash
jupyter labextension install jupyterlab-control
```

## Development

For a development install (requires npm version 4 or later), do the following in the repository directory:

```bash
npm install
npm run build
jupyter labextension link .
```

To rebuild the package and the JupyterLab app:

```bash
npm run build
jupyter lab build
```

