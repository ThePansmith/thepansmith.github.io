---
title: "Neoforge Stable Modding Version Proposal"
date: 2025-07-06T20:04:20-05:00
draft: false
categories:
- News
author: pansmith
summary: "A simple proposal on how to end modded Minecraft version chasing with a single step."
description: "A simple proposal on how to end modded Minecraft version chasing with a single step."
---

According to an ongoing form I've been running, most mod developers would greatly prefer having a stable version to develop their mods over version chasing. The community currently suffers from a general lack of communication on the matter, and while a community effort could happen, involving Neoforge itself in the process would greatly simplify it. 

The proposal is simple: Neoforge announces a specific Minecraft version to be a **Stable Modding Version** (SMV), with the exact minecraft version being determined by reoccuring community vote.

## How?
<!-- 1. Host a community vote every 2-3 years on if the SMV should be changed. 
2. Done  -->

| ![Stable Modding Version chart](smv-chart.png) |
|:--:|
| *It's really as simple as that.* |

Neoforge hosts a community vote every 2-3 years to see if the Stable Modding Version should be updated, and if so, to what version.  This also has the benefit of getting modders more involved with Neoforge's community and votes as whole.

With Neoforge allowing users to submit PRs and backports, *the community can handle the Stable Modding Version*, while the neoforged team can continue to implement new features and port to the latest versions as ususal.

## Benefits 
- Large Mod developers will be able to develop their mods further instead of constantly porting
- Neoforge can continue to develop new features and port to newer versions, as SMV support would largely be community managed.
    - Some modders will still follow to individual patches (optimization, clientside mods, and other mods targeted towards vanilla players), so neoforge will still have testers for newer patches.
    - Mod developers would be more involved with Neoforge, in order to cast their vote more accuratly.
- More modders will be willing to port to neoforge (and modern Minecraft in general), knowing that the porting cycle is not an issue.
- Modders are able to further develop their mods instead of having to constantly port them, leading to higher quality mods.
- Allowing a version to mature allows for things like modpacks, etc to happen; which in turn helps create more mods (and more modders) to fulfill those modpacks needs.
    - High quality modpacks in general can reemerge, with the lack of them being a symptom of version chasing.
- Community controlled, while still having an authoritative voice to lead the community.
- Easy to implement on Neoforge's end, simply being a recurring vote, a blogpost and a installer tweak. 

---

## Question and Answer

**Q**: What about players wanting the content not available in the current SMV? \
**A**: Players can be directed to install the [Vanilla Backports](https://www.curseforge.com/minecraft/mc-mods/vanillabackport) mod, which backports said content to 1.21.1 (and will likely do the same for future versions).

**Q**: What about neoforge just suggesting a version when asked about stability? \
**A**: Keeping things clearly communicated would both keep it clear for mod developers, and cause people to not ask neoforge developers that question repeatedly, a win:win.

**Q**: What if mod developers simply just repeatably elect to stay on 1.21.1 forever? \
**A**: Likely will not happen, as mod developers do appreciate the technical improvements that are implemented, it's just that there isn't enough present in any individual patch to justify the time required to port. If this wasn't the case, 1.7.10 would still be as popular as it was a over decade ago.

**Q**: Why can't mod developers just figure it out themselves? Neoforge shouldn't mettle in such fares.\
**A**: Mod developers will determine what version they prefer to be on via vote, this simply helps solve the communication issue. The last time the community was able to settle on a stable modded version without communication was nearly [eight years ago](https://howoldisminecraft1122.today/).

**Q**: I'm a mod developer who prefers to keep my mods on the latest patch of Minecraft, how will this affect me? \
**A**: Not in the slightest. It is fully expected that some mods will do just that, such as optimization mods, clientside and serverside only mods, etc. This is just to give content modders a unified direction on where to port and maintain their mods.

**Q**: How would voting work? \
**A**: Simplest answer would just be a [runoff vote](https://en.wikipedia.org/wiki/Runoff_voting) hosted on neoforge's discord or otherwise.

**Q**: Why isn't this just a text document? \
**A**: ¯\\_(ツ)\_/¯


