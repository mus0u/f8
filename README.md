# F8
a tiny self-hosted discord bot for rolling fate dice

## instructions
1. make sure ruby is installed on your local system
1. download the `f8` script file
1. navigate to https://discordapp.com/developers/applications and create a new application
1. click the `Bot` link on the sidebar
1. add a new bot user for your new application
1. click the `Copy` button to copy your new bot user's token
1. add a file named `config.yml` in the same directory as the script file, with contents `token: YOUR_BOT_TOKEN_HERE`
1. back in your browser, click the `OAuth2` link in the sidebar
1. click the `bot` checkbox in the `Scopes` section
1. a link should be generated below. click `Copy`.
1. paste the link into a new browser tab and add the bot to your server. you may have to log in again first.
1. run `./f8`

to roll the dice, type `f8 roll` or `f8 r`.
you can optionally specify a skill rating, e.g. `f8 r 5` rolls with a skill rating of +5.
the bot will listen to commands in any channel it's in.
it requires permissions to be able to send and receive messages in a channel in order to do so.

thanks to [discordrb](https://github.com/meew0/discordrb) for making this bot easy to implement.
thanks to [MusicBot](https://github.com/jagrosh/MusicBot) for inspiration and clear setup instructions.

# LICENSE
this work is distributed under the terms of the GNU general public license, version 3.
see the `LICENSE` file for details.