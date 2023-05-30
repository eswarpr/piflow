# Pi Flows

This is the repository for all the release for the "Pi Flows" app. The app was demoed in the "Power Platform Community Call" and a recording of the call can be found in [their](https://youtu.be/__gcts_NKrk) channel.

Please refer to the [license](./LICENSE) file and ensure you are aware of your rights, and risks when using the releases available here.

To use this app you will need:

- One or more Raspberry Pi 2+ or Pi Zero
- Remote GPIO must be enabled in the Pi
- The Pi will need to be connected to the local network
- The IP address of the Pi

An introduction to enabling remote GPIO can be found at [this](https://gpiozero.readthedocs.io/en/stable/remote_gpio.html) link.

The release features builds for both Linux (x64) and Windows (x64). Please ensure you use the appropriate build for your system. You will need to install [.NET 7.0](https://dotnet.microsoft.com/en-us/download/dotnet/7.0) in your system. You will also need to install the ASP.NET Core runtime from the download link.

Once you have downloaded the appropriate release, extract the app to a folder in your system and run the ``Berry.PiFlows.Server`` executable. The app will be available from http://localhost:8890.

Enjoy hacking!
