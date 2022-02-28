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
* Create Together
{% endhint %}

1. Download [Git](https://git-scm.com/downloads) if you don't have it already.
2. Clone the modpack of your choice into an empty folder

```
git clone https://github.com/NillerMedDild/Enigmatica6
```

1. Open the `automation` folder.
2. Run the script `InstanceSyncSetup`
3. Run the script `update-server`

Re-run the script `update-server` whenever you want to update to a new modpack version.

**Notes**

* Using the `update-server` script will reset changes you've made to tracked files.
* The world and mods folders are backed up by the update-server script.
* Anything put in the `overrides` folder will be copied into the root folder when the `update-server` script is finished. We recommend you put any changed configs and added mods there.
* You start the server using the script `start-automated-server` found in the instance root.
* You will have to update forge version yourself whenever the modpack updates Forge - You can find the version used for every modpack version in the changelog. You update the Forge version in the `settings.cfg` file found in the instance root.
