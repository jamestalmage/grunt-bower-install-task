grunt-bower-install-task
========================

Download bower dependencies.

This plugin is basically the equivalent of calling `bower install` from the command line, but you can do it as a grunt task. Currently the only advantage it offers over using `grunt-shell` is that it offers a prettier log output, and is less verbose to configure.


*Install it via npm:*
```
npm install --save-dev grunt-bower-install-task;
```

*Add this to Gruntfile.js:*
```javascript

// Load The Tasks
grunt.loadNpmTasks('grunt-bower-install-task');

// Use it as part of your build.
grunt.registerTask('init','_bower_install__','some_other_task');
```

