---
description: Frequently Asked Questions. Make suggestions on Discord
---

# FAQ

### How do I install Orbis?

**Step 1** Get a 1.18.1 instance of PaperMC. Make the server run one time (to generate all the files), and delete the world folder once you stopped it.

**Step 2** Go to `bukkit.yml` and add this at the bottom:

```yaml
worlds:
  world:
    generator: Orbis:alphatest
```

**Step 3** Put [this jar](https://cdn.discordapp.com/attachments/803207168445644822/929552964299931739/Orbis-v0\_2-alpha.jar) in your `*/plugins/` folder. Then manually create the folder and `*/plugins/Orbis/packs/` . Then, put [this pack](https://cdn.discordapp.com/attachments/803207168445644822/929557399109533696/alphatest.orbis) into the packs folder (it is a zipped `.orbis` file with JSON files in it).

{% hint style="info" %}
Do not unzip the `.orbis`pack file
{% endhint %}

**Step 4** Start your server and enjoy!

**NOTE** The provided pack is a very simple and early sample Jake made to show the new backend systems in play. If you run it yourself it is purely for you to see where we are currently at. In the near future, pack creators will design packs with some more flavour, and we will provide updates to the engine to make it support all the new content!

