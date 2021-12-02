# Shortwave for Desktop (Community version)

Community version of Shortwave app for macOS

## How to Install

1. Install this specific version of nativefier
```
npm install -g nativefier@43.1.3
```
2. Run the command below in whichever directory you'd like to compile the Shortwave application
3. 
```
nativefier "https://app.shortwave.com" --user-agent "Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:70.0) Gecko/20100101 Firefox/70.0" --name "Shortwave" --internal-urls ".*" --browserwindow-options '{"webPreferences":{"nativeWindowOpen":true}}'
```
4. You may run this command with different application names, replacing "Shortwave" with "Shortwave_0" for multiple concurrent versions. 
5. Navigate to the compiled application and run!

### Download

Navigate to the releases section and download the [Shortwave community desktop compiled package](https://github.com/jakejimenez/community-shortwave-desktop/releases/download/v0.1.0-alpha/Shortwave-darwin-x64.zip)

## License
See [LICENSE](LICENSE)
