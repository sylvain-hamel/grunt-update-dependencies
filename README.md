# grunt-update-dependencies

> Update npm dependencies.

## Getting Started

This plugin requires Grunt `~0.4.0`

Install the plugin with this command:

```shell
npm install grunt-update-dependencies --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-update-dependencies');
```

## Install Dependencies task
_Run this task with the `grunt update-dependencies` command._


### Settings

There are a number of options available.

#### options.stdout
Type: `Boolean`
Default: true

Show stdout in the terminal.

#### options.stderr
Type: `Boolean`
Default: true

Show stderr in the terminal.

#### options.failOnError
Type: `Boolean`
Default: true

Instructs the update-dependencies task to fail the grunt run if an error occurs while updating dependencies.

#### options.cwd
Type: `String`
Default: (none)  - runs in current directory

Defines the working directory to run 'npm update' (relative path)
