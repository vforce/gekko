# Setting up configuration

If you haven't done so already, first thing you will need to do is to copy `sample-config.js` to `config.js` in the same folder where you cloned gekko out.

# Enable debug log in command line

Set `config.debub = true;` (should already be the default setting) to see debug logs when using the command line

Set `config.silent = false;` and `config.debug = true;` in `gekko/web/routes/baseConfig.js` to see debug logs when using ui mode

With those settings enabled, you can log anything anywhere using `console.log('some message');`
