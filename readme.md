selenium-launcher [![Build Status](https://secure.travis-ci.org/daaku/nodejs-selenium-launcher.png)](http://travis-ci.org/daaku/nodejs-selenium-launcher)
=================

A library to download and launch the Selenium Server.

```javascript
require('selenium-launcher').launch(function(er, selenium) {
  // selenium is running
  // selenium.host / selenium.port are available
  // selenium is a child process, so you can do selenium.kill()
})
```

Testing
---

```sh
npm test
```
