
## create-uevr-plugin-func

This repo contains a MaslowGPT command that allows you create C++ Template functions for your UEVR Plugins.

How to use:

- Install the `MaslowGPT` npm package. More info here:

https://github.com/MaslowCorporation/MaslowGPT

You don't need to subscribe to the MaslowGPT API to use this tool. You can if you want ;-)

- Set your custom commands folder in MaslowGPT, with the 

```
npx maslow set-commands-folder
```

command.

- Install the create-uevr-plugin-func command to your MaslowGPT commands folder, with this command

```
npx maslow add-command-from-github
```

when asked what repo you want to install from, use this URL:

```
https://github.com/MaslowCorporation/create-uevr-plugin-func
```

- Use the `create-uevr-plugin-func` command in MaslowGPT, by using the

```
npx maslow run-command
```

command, and select `create-uevr-plugin-func` from the list of choices.

It will generate a folder containing your UEVR C++ function code. A simple arithmetic function that you can turn into anything ;-).
