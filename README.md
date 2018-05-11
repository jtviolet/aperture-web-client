# Description
This web client for the Aperture service serves as a bare-bones example of what you can do when connecting to your aperture server. This web client implements [xterm.js](https://github.com/xtermjs/xterm.js/), so all configurations for the terminal itself can be found there.

# Authentication
Currently authentication is implemented as a bare-bones usage of [socket.io-auth](https://github.com/facundoolano/socketio-auth). Although the feature is implemented, it is up to you to personalize your authentication to your required parameters. The authentication currently allows any user or device to connect.

# Install and Run
```
git clone https://github.com/jtviolet/aperture-web-client.git
cd aperture-server
npm install
```

# Usage
You will need to have the [aperture-edge-client](https://github.com/jtviolet/aperture-edge-client) running on the devices you want to connect to. You will also need an instance of the [aperture-server](https://github.com/jtviolet/aperture-server) running.

# Contributing
If you feel you can improve this service in any way, I'm happy to accept pull requests for the good of the service. I'm pretty new to Node.js/JavaScript and there is always room for improvement; feel free to submit pull requests.
