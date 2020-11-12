---
description: >-
  For DBTGen to work, we need to make a base configuration. This section covers
  it in a lot of detail, but first we need to set up the basics.
---

# Making a base config setup

## Creating a DBTGen Config directory

DBTGen generators look at `./DBTGen.config/` \(case **insensitive**\) for configuration files.

{% tabs %}
{% tab title="Windows" %}
Open the Windows **Explorer** \(hint: it's where you usually make folders and such\) and open your bot's folder.

Create a new folder called `DBTGen.config` \(make sure this is a FOLDER, not a file!\) and then you are all set to continue!
{% endtab %}

{% tab title="macOS" %}
## From the Finder

Open Finder, \(hint: it's where you usually make folders and such\) and open your bot's folder.

`Ctrl`+Click in the space, and choose "New Folder" from the options that pop up. Name this folder `DBTGen.config` \(make sure this is a FOLDER, not a file!\) and then you are all set to continue!

## From Terminal

Open Terminal, \(press `Command`+`Space` and type "Terminal"\) and then run `cd my/bot/folder`. If your folder contains a space, drag it from the Finder into the terminal after typing `cd` \(note the extra space\). Then press enter and type

```bash
mkdir DBTGen.config
```

Then you are all set to continue!
{% endtab %}

{% tab title="Linux" %}
## Come on, you know how to do this!
{% endtab %}
{% endtabs %}



