# weather-app
A weather application made with node.js and tested with WebdriverIO.

Command line instructions:

1. Start the selenium standalone server:
```
java -jar -Dwebdriver.gecko.driver=./geckodriver selenium-server-standalone-3.5.3.jar
```

2. Keep selenium server running and open a new terminal window (Command + T).

3. In the new window, execute the test runner:
```
./node_modules/.bin/wdio wdio.conf.js
```
