# Linus_Torvlads_AI-clone
This model tries to mimic Linus Torvalds, the inventor of Linux and Git regarding his inventions and general overview of computers. It gives insightful answers to your questions.

To prevent any errors, Instead of cloning this repository I suggest you download the gaianet node using the following curl command on your linux machine. 
```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

After successful installation of the node, 
Run the command printed on the terminal to set up the environment path, it is something like `source /<directory>/.zshrc`

After that set the configuration file using the following command. This is the config command used to initialize the node in my repository. My repository has a gigabyte sized file missing since I wanted to upload my project on github. 

This is the configure command which fetches the data from my configuration file. 
```
gaianet init --config https://raw.githubusercontent.com/just-karrot/Linus_Torvalds-AI-clone/main/config.json
```
# After the init command
The init command may take sometime to configure the node based on your machine, after successful completion, run the following to start the node. 
```
gaianet start
```
This will start the node on your system and you should see a link to interact with the Linus Torvalds chat bot.
