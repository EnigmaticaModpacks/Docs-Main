---
description: >-
  An easier way to keep your server running on the latest modpack version.
  Follow the below steps to be able to update modpack version with only a few
  clicks.
---

# Automatic Server Updates

{% hint style="success" %}
Currently available for

* Enigmatica 6
* Enigmatica 8
* Enigmatica 9
* Create Together
{% endhint %}

1. Download [Git](https://git-scm.com/downloads) if you don't have it already.
2. Download Powershell if you don't have it already.
   * Windows comes with Powershell pre-installed.
   * [Linux Download Instructions](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-linux)
   * [Mac Download Instructions](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-macos)
3. Clone the modpack of your choice into an empty folder.

```
# Enigmatica 6
git clone https://github.com/EnigmaticaModpacks/Enigmatica6

# Enigmatica 8
git clone https://github.com/EnigmaticaModpacks/Enigmatica8

# Enigmatica 9
git clone https://github.com/EnigmaticaModpacks/Enigmatica9

# Create Together
git clone https://github.com/EnigmaticaModpacks/CreateTogether
```

1. Open the `automation` folder.
2. Run the script `InstanceSyncSetup`
3. Run the script `update-server`
4. Start the server using the script `start-automated-server` found in the instance root.

Re-run the script `update-server` whenever you want to update to a new modpack version.

**Notes**

* Using the `update-server` script will reset changes you've made to tracked files.
* The world and mods folders are backed up by the update-server script.
* Anything put in the `overrides` folder will be copied into the root folder when the `update-server` script is finished. We recommend you put any changed configs and added mods there.
* Whenever you run `update-server`, the `settings.cfg` is reset to the latest default to get the latest Forge version.&#x20;
