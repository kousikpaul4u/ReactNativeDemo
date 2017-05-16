# ReactNativeDemo
For MAC 
Node, Watchman 
We recommend installing Node and Watchman using Homebrew. Run the following commands in a Terminal after installing Homebrew:
----------------------------------------------------------------------------------------------------------------------------
brew install node
brew install watchman
----------------------------------------------------------------------------------------------------------------------------
If you have already installed Node on your system, make sure it is version 4 or newer.

Watchman is a tool by Facebook for watching changes in the filesystem. It is highly recommended you install it for better performance.

The React Native CLI 
Node comes with npm, which lets you install the React Native command line interface.

Run the following command in a Terminal:
----------------------------------------------------------------------------------------------------------------------------
npm install -g react-native-cli
----------------------------------------------------------------------------------------------------------------------------
If you get an error like Cannot find module 'npmlog', try installing npm directly: curl -0 -L https://npmjs.org/install.sh | sudo sh.
Xcode 
The easiest way to install Xcode is via the Mac App Store. Installing Xcode will also install the iOS Simulator and all the necessary tools to build your iOS app.

If you have already installed Xcode on your system, make sure it is version 8 or higher.

You will also need to install the Xcode Command Line Tools. Open Xcode, then choose "Preferences..." from the Xcode menu. Go to the Locations panel and install the tools by selecting the most recent version in the Command Line Tools dropdown.
----------------------------------------------------------------------------------------------------------------------------
RUN:
react-native run-ios
