Hubot
=====

This GitHub's Campfire bot, hubot.  He's pretty cool.


Playing with Hubot
==================

Use [npm](http://npmjs.org) to install dependencies:

    % npm install

Now start hubot:

    % bin/hubot

You'll see some startup output about where your scripts come from.

    Loading deploy-local scripts at /Users/me/nubot/scripts
    Loading hubot core scripts for relative scripts at /Users/me/nubot/src/hubot/scripts
    Hubot: the Shell.
    { id: '1', name: 'Shell' }
    Loading hubot-scripts from /Users/me/nubot/hubot-scripts.json
    Successfully connected to Redis

Then you can interact with Hubot by typing `hubot help`.

    hubot help

    animate me <query>  - The same thing as `image me`, except adds a few
    convert me <expression> to <units> - Convert expression to given units.
    help - Displays all of the help commands that Hubot knows about.
    ...

Take a look at the scripts in the `./scripts` folder for examples.
Delete any scripts you think are silly.  Add whatever functionality you
want hubot to have.


hubot-scripts
=============

There will inevitably be functionality that everyone will want.  Instead
of adding it to hubot itself, you can submit pull requests to
[hubot-scripts](https://github.com/github/hubot-scripts).  To enable
scripts from the hubot-scripts package, add the script name to the
hubot-scripts.json file in this repo.

