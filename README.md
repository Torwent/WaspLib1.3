# WaspLib
 
## What is WaspLib?
WaspLib is a include for Simba I made for myself to quickly write scripts with functions and procedures I use often throughout my scripts.

## What can WaspLib do?
It can do a lot of things ranging from simple very basic things that I think that should be included on SRL and are not like:
- Bank tabs support.
- Scroll bars (Bank, chat, etc) support,
- etc.

To very custom things like:
- Attempt to walk/ towards an object (bank, anvil, npc, whatever) and try to click it while it's walking towards it.
- Cast high alchemy while walking.

It also contains a couple of custom maps and updated existing maps for RSWalker.



Not everything in the include is mine, though 90% is. Some things are based on other people's work and I think I left everything properly credited. If you find anything that is your work and is not credited let me know so I can fix it! Also if you are not happy I include your code let me know and I'll remove it.

## What do you need to use WaspLib?
First of all you need to be using [Simba 1.3 RC2](https://github.com/MerlijnWajer/Simba/releases/tag/simba-1.3-rc2).

Then, you need to include in your script the latest [SRL](https://github.com/SRL/SRL/releases) and the latest [RSWalker](https://github.com/ollydev/RSWalker/releases).

The start of your script should look something like this:

```
programScript;
{$i SRL/OSR.simba}
{$i SRL/utils/rsclient.simba} //Optional... only if you not using SMART.
{$i RSWalker/Walker.simba}
{$i WaspLib/WaspLib.simba}
```

## More info
I plan to support future Simba versions but right now Simba 1400 gives my coordinates problems so it's untested. It should work fine though if you don't have DPI Scaling enabled.

Simba 1.3 RC1 and older probably doesn't work.
I remember the RC1 was giving me some error I couldn't fix until I decided to use 1.3 RC2.
So I'm guessing even older versions might not work but you can try it if you want.

### Need help?
If you need help setting up feel free to add me on discord.

Aqua Shy Wasp#1415