# Setting up configuration

If you haven't done so already, first thing you will need to do is to copy `sample-config.js` to `config.js` in the same folder where you cloned gekko out.

# Enable debug log in command line

To see debug logs when using the command line, set below setting in `config.js`

    config.debub = true;


To see debug logs when using ui mode, set below settings in `gekko/web/routes/baseConfig.js` 

    config.silent = false;
    config.debug = true; 


With those settings enabled, you can log anything anywhere using 

    console.log('some message');
