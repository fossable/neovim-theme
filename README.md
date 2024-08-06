# Neovim like theme 

![screenshot](./screenshot.png)

You can setup the blog name with config file in extra

```toml
[extra]
blog_name = "name"
```

And you can add some custom commands/init function with this parameter (default false)

```toml
[extra]
custom_script = true
```
then you just add a file static/js/custom_script.js and define your custom functions like this:

```javascript
// add special commands
function custom_commands(command, args){
   ...
}

// add special init routine
function custom_init(){
    ...
}
```
