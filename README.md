# Nuxt.js v3 Pterodactyl egg
[![Discord](https://img.shields.io/discord/818135932103557162.svg?label=&logo=discord&logoColor=fff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/tVYhJfyDWG)

A [Pterodactyl](https://pterodactyl.io/) egg for deploying [Nuxt.js v3](https://nuxt.com) applications.

This will clone a git repository, build the nuxt application to `.output/` and run the server from the generated `output/server/index.mjs` file on `localhost` (the port will be pulled from your server's primary allocation).

To use the egg, go to the [raw egg .json file](https://github.com/WiIIiam278/nuxtjs-pterodactyl-egg/raw/master/egg-nuxt-js-v3.json) and hit CTRL+S (Windows) / CMD+S (Mac) to save it as a file. Then use Pterodactyl's egg import feature to save it to a nest. Configure the various parameters, including specifying a repository containing your code to pull from (and required authentication if needed). 

Check [the Nuxt deployment documentation](https://nuxt.com/docs/getting-started/installation) for more information. Based on [the node.js egg by pasrkervcp](https://github.com/parkervcp/eggs). Licensed under MIT.