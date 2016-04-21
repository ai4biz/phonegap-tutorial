# social-crm-mobile
Social CRM Mobile

#PhoneGap
http://phonegap.com
http://docs.phonegap.com/getting-started/1-install-phonegap/desktop/

# Install
Run the command line below:

```
npm install -g bower yo gulp generator-mobileangularui
```

Then run the command to install phonegap:
```
sudo npm install -g phonegap
```

Install Gulp
```
npm install gulp
```

# Fix Error below:

```
Caios-MacBook-Pro:Geolocation_Phonegap caiomsouza$ gulp
module.js:341
    throw err;
    ^

Error: Cannot find module 'run-sequence'
    at Function.Module._resolveFilename (module.js:339:15)
    at Function.Module._load (module.js:290:25)
    at Module.require (module.js:367:17)
    at require (internal/module.js:16:19)
    at Object.<anonymous> (/Users/caiomsouza/git/github.com/Geolocation_Phonegap/gulpfile.js:66:22)
    at Module._compile (module.js:413:34)
    at Object.Module._extensions..js (module.js:422:10)
    at Module.load (module.js:357:32)
    at Function.Module._load (module.js:314:12)
    at Module.require (module.js:367:17)

```

Fixed typing:

```
npm install
```






