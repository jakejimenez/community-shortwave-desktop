# community-shortwave-desktop
Community version of Shortwave app for macOS, Windows, and Linux

* Steps to install:
1. Install this specific version of nativefier ```npm install -g nativefier@43.1.3```
2. Run the command below in whichever directory you'd like to compile the Shortwave application


  2.1 ```nativefier "https://app.shortwave.com" --user-agent "Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:70.0) Gecko/20100101 Firefox/70.0" --name "Shortwave" --internal-urls ".*" --browserwindow-options '{"webPreferences":{"nativeWindowOpen":true}}'```


  2.2 You may run this command with different application names, replacing "Shortwave" with "Shortwave_0" for multiple concurrent versions.
  
  
3. Navigate to the compiled application and run!
