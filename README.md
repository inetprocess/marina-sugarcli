# Sugarcli Plugin for inetprocess/marina
Plugin made by Inet Process to run [sugarcli](https://github.com/inetprocess/sugarcli) commands

__WARNING: The plugin directory must be named `sugarcli`__ (complete path: plugins/sugarcli)

# Installation
Clone the repository in the plugins/ directory of your docker-lamp

# sugarcli commands
Use `lamp sugarcli` to use sugarcli. On the first run, sugarcli is downloaded.

Example to get a list of users:
```bash
cd www/sugarproject
marina sugarcli user:list --path .
```
