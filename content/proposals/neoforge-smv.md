---
title: "Neoforge Stable Modding Version Proposal"
date: 2025-07-06T20:04:20-05:00
draft: false
categories:
- news
author: pansmith
summary: "A simple proposal on how to end modded Minecraft version chasing with a single step."
description: "A simple proposal on how to end modded Minecraft version chasing with a single step."
---

{{< notice note >}}
There is a [followup survey](https://forms.gle/ec68AdSHvQxVYjcY9) related to the idea of a Stable Modding Version, for both giving feedback and showing support if you wish. With Neoforge's annual question and answer session coming up, this could be a talking point with enough support.
{{< /notice >}}


> "Notably, to avoid version fragmentation, we recommend that modders continue to actively maintain the 1.21.1 version of their mods until the release of Minecraft 1.22!"

According to an ongoing survey I've been conducting, most mod developers would strongly prefer having a stable version to develop their mods over constantly porting their mods to the latest version. The community currently suffers from a lack of clear communication on where modders are gathered, fragmenting the modded community. While a community-driven effort could address this, involving Neoforge directly in the process would make it significantly more streamlined.

The proposal is simple: The Neoforged team designates a specific Minecraft version as the **Stable Modding Version** (SMV); The exact version would be determined through recurring community votes.

## How?
<!-- 1. Host a community vote every 2-3 years on if the SMV should be changed. 
2. Done  -->

| ![Stable Modding Version chart](smv-chart.png) |
|:--:|
| *It's as simple as that.* |

Neoforge hosts a community vote every 2-3 years to determine if the Stable Modding Version (starting with 1.21.1) should be updated and, if so, to which version. This also encourages modders to become more involved with Neoforge's community and voting processes as a whole.

With Neoforge allowing users to submit PRs and backports, *the community can manage the Stable Modding Version*, while the Neoforge team can continue implementing new features and porting to the latest versions as usual.

## Benefits 
- Large mod developers will be able to focus on further developing their mods instead of constantly porting them to new versions.
- Neoforge can continue to develop new features and port to newer versions, as SMV support would largely be community-managed.
    - Some modders will still follow individual patches (e.g., optimization mods, client-side mods, and other mods targeted toward vanilla players), ensuring Neoforge will still have testers for newer patches.
    - Mod developers would be more involved with Neoforge in order to cast their votes more accurately.
- More modders will be willing to port to Neoforge (and modern Minecraft in general), knowing that the porting cycle is no longer an issue.
- Modders can focus on improving the quality of their mods instead of constantly porting them, leading to higher-quality mods overall.
- Allowing a version to mature enables the creation of modpacks, which in turn fosters the development of more mods (and more modders) to meet the needs of those modpacks.
    - High-quality modpacks can reemerge, addressing the lack of them caused by version chasing.
- The process is community-controlled while still having an authoritative voice to guide the community.
- Easy to implement on Neoforge's end, requiring only a recurring vote and a blog post.

---

## Questions and Answers

**Q**: What about players wanting content not available in the current SMV? \
**A**: Players can be directed to install the [Vanilla Backports](https://www.curseforge.com/minecraft/mc-mods/vanillabackport) mod, which backports said content to 1.21.1 (and will likely do the same for future versions).

**Q**: What about Neoforge just suggesting a version when asked about stability? \
**A**: Keeping things clearly communicated would both make it clear for mod developers and reduce the frequency of Neoforge developers being asked that question repeatedly, a win-win for everyone.

**Q**: What if mod developers repeatedly elect to stay on a single version forever? \
**A**: This is unlikely, as mod developers do appreciate the technical improvements implemented into the game over time. The issue is that no single patch (or even update in some cases) typically justifies the time and effort required to port.

**Q**: Why can't mod developers just figure it out themselves? Neoforge shouldn't meddle in such affairs. \
**A**: The Mod developer community will determine the stable modding version via vote. This proposal simply addresses the communication issue, allowing the community to easily vote and communicate with each other, as well as having a resource to point others to. 
<!-- The last time the community managed to settle on a stable modding version without structured communication was nearly [eight years ago](https://howoldisminecraft1122.today/). -->

**Q**: I'm a mod developer who prefers to keep my mods on the latest patch of Minecraft. How will this affect me? \
**A**: It won't affect you at all. It is fully expected that some mods, such as optimization mods, client-side mods, and server-side mods, will continue to target the latest patches. This proposal is aimed at giving content modders a unified direction for porting and maintaining their mods.

**Q**: How would voting work? \
**A**: The simplest approach would be a [runoff vote](https://en.wikipedia.org/wiki/Runoff_voting) hosted on Neoforge's Discord or another platform.

---
## Supporters:
Like mentioned in the info banner, there is a [form](https://forms.gle/ec68AdSHvQxVYjcY9) for this proposal. Demonstrating to the Neoforge team that the community would support this would greatly improve it's odds of passing.


<!-- | Users              |  Mods | Downloads |
| :---------------- | :------: | :----: |
| Pansmith       |   Deep Mob Evolution, Steam Additions,   | 1.9M |
| idk          |   lol   | 3 | -->
