# Server Installation

For easy reliable server setup and hosting, we recommend using [BisectHosting](https://www.bisecthosting.com/enigmatica) to run Enigmatica servers. Use the code "**enigmatica**" to get **25%** off your first month as a new client for any of their gaming servers. We recommend that you use **at least 4GB** to run our modpacks with 5-7 players.

The guide below is for self-hosting a server. You will need to be familiar with how to setup a vanilla Minecraft server before following this guide. If you are using another hosting provider, please see their documentation too, and contact their support first if you have any issues.

## Before Beginning

You should ensure that you are familiar with how to setup a regular (vanilla) Minecraft server. [This article](https://minecraft.gamepedia.com/Tutorials/Setting\_up\_a\_server) on the Minecraft Wiki is a good way to learn the basics of setting up a Minecraft server. There are also many guides available on YouTube.

A key difference between vanilla Minecraft and modded Minecraft is that you will need far more memory to host a server with Enigmatica than you normally do with a vanilla server. Please make sure your server has ample specs before continuing (usually 4-8GB), and please do not try to host a Enigmatica server on the same system that you intend to play the pack on.

## Installing a Server

1.  Make sure you have the correct version of Java for the modpack you wish to install.&#x20;

    See [#installing-java](java.md#installing-java "mention")
2. Go to the [CurseForge](https://www.curseforge.com/members/nillermeddild/projects) page of the modpack you want to install, and download the server files.
3.  Unzip the downloaded server files into an empty folder_._&#x20;

    _<mark style="color:yellow;">Make sure you do not have this in OneDrive or another synced folder, as those can lock up the installer.</mark>_
4. Run the `start-server` script and wait for the installation to complete.
5. You should now see a prompt to accept the EULA. Accept by typing `TRUE` and pressing `Enter`
6.  When the server has started fully, close the window and run the `start-server` script again.

    _<mark style="color:yellow;">This works around a known issue where you cannot type in the console the first time you start the server.</mark>_

{% hint style="info" %}
Use `start-server.bat` on Windows

Use `start-server.sh` on Mac & Linux
{% endhint %}

## Updating

{% tabs %}
{% tab title="Selfhosted" %}
### If you are hosting the pack yourself

Follow the steps in [#installing-a-server](server-installation.md#installing-a-server "mention")

1. Stop the server.
2. Delete the `world` folder.
3. Copy the `world` folder from your old installation to the new.
4. Start the server.
{% endtab %}

{% tab title="Server Host" %}
### If you're using a server host

1. Follow the steps in [#installing-a-server](server-installation.md#installing-a-server "mention")
2. Stop the server.
3. Delete the Forge jar and the following folders from the server:
   * configs
   * defaultconfigs
   * kubejs
   * libraries
   * mods
   * patchouli\_books
4. Upload the Forge jar and the list of folders from the new server folder to your server.
5. Start the server.

{% hint style="warning" %}
If your old server contains the file `server-setup-config.yaml`, you should also delete the following files from the server:

* server-setup-config.yaml
* serverstarter.lock
* startserver.bat
* startserver.sh

And upload those same files from the new server folder.



<mark style="color:blue;">These steps are only needed for server hosts that use the serverstarter script.</mark>
{% endhint %}
{% endtab %}
{% endtabs %}

{% hint style="success" %}
Remember to re-apply any changes you have made.
{% endhint %}

## Server Properties

Default `server.properties` files for our modpacks.

<table><thead><tr><th>Modpack</th><th data-type="files">server.properties</th></tr></thead><tbody><tr><td>Enigmatica 2</td><td></td></tr><tr><td>Enigmatica 2: Light</td><td></td></tr><tr><td>Enigmatica 2: Expert</td><td></td></tr><tr><td>Enigmatica 2: Expert Skyblock</td><td></td></tr><tr><td>Enigmatica 4</td><td></td></tr><tr><td>Enigmatica 5</td><td></td></tr><tr><td>Enigmatica 6</td><td></td></tr><tr><td>Enigmatica 8</td><td></td></tr><tr><td>Create Together</td><td></td></tr></tbody></table>
