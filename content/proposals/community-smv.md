---
title: "Community Stable Modding Version Proposal"
date: 2025-07-15T20:04:20-05:00
draft: false
categories:
- news
author: pansmith
summary: "A simple proposal on solving modded Minecraft version chasing with a single step."
description: "A simple proposal on solving modded Minecraft version chasing with a single step."
---

{{< notice note >}}
This proposal is a work in progress, feel free to give feedback in [the server](https://discord.gg/3gAerCZjrw).
{{< /notice >}}

{{< notice note >}}
There is [a discord](https://discord.gg/3gAerCZjrw) for further communication and voting.
{{< /notice >}}

According to an ongoing survey I've been conducting, most mod developers would strongly prefer having a stable version to develop their mods over constantly porting their mods to the latest version. The community currently suffers from a lack of clear communication on where modders are gathered, fragmenting the modded minecraft community. 

The proposal is simple: A recurring developer vote is hosted to determine a specific Minecraft version as the **Stable Modding Version** (SMV).

# Details

| ![Stable Modding Version chart](smv-chart.png) |
|:--:|
| *The process* |

A recurring developer vote is hosted to determine if the Stable Modding Version should be updated and, if so, to which version. Longterm Mod development is then focused on said version, allowing the version to mature. Users would need to be verified before being able to vote, to ensure that the Stable Modding Version vote remains developer focused.

With Neoforge allowing users to submit PRs and backports, *the community can manage the Stable Modding Version*, while the Neoforge team can continue implementing new features and porting to the latest versions as usual, while the SMV works as a community managed Long Term Support version.

# Benefits 
### For Mod Developers
- Mod developers can focus on improving their mods instead of constantly porting them to newer versions.
- Other modders may be encouraged to port, knowing that the constant porting cycle is no longer an issue.
- Allowing a version to mature fosters the creation of modpacks, which in turn drives the development of more mods and encourages new mod developers to join the community.
- Allowing a version to mature also allows for the creation of other helpful tools for modding.
- A recurring vote allows the developer community to be able to both have version longevity and be able to react to substantial technical improvements in a reasonable time.
- The process is community-driven and provides a unified direction, allowing mod developers to be able work together and communicate with one another, rather than having to guess.

### For Players and Pack Developers
- A stable modding version means more mods will be available on a single version, rather than being scattered across multiple versions.
- Mod developers being able to focus on improving their mods rather than having to constantly port them results in more feature-rich mods.
- A stable modding version allows for high-quality modpacks to develop.
- Having a stable modding verison could encourage some developers to port their older mods to that version.
- Feature backports exist, so players can still play with all of the vanilla content if they wish.
- Vanilla players are not affected by this, as optimization mods, client-side mods, server-side mods, etc would not be affected by this.

---

# Questions and Answers

**Q**: What about players wanting vanilla content that is not available in the current SMV? \
**A**: Players can be directed to install the [Vanilla Backports](https://www.curseforge.com/minecraft/mc-mods/vanillabackport) mod, or an equivalent.

**Q**: What would the first Stable Modding Version be? \
**A**: A developer vote would be held, but if you want a prediction, in the survey I conducted, a vast majority of mod developers indicated they would prefer developing on Neoforge 1.21.1 if they could choose the SMV themselves.
<!-- This can likely be attributed to several factors, such as NeoForge being by far the most popular loader on 1.21.1 and having better documentation compared to forge 1.20.1. -->

**Q**: What if mod developers repeatedly elect to stay on a single version forever? \
**A**: This is unlikely, as mod developers do appreciate the technical improvements implemented into the game over time. The issue is that no single patch (or even update in some cases) typically justifies the time and effort required to port.

**Q**: I'm a mod developer who prefers to keep my mods on the latest patch of Minecraft for vanilla players. How will this affect me? \
**A**: It won't affect you at all. It is fully expected that some mods, such as optimization mods, client-side mods, and server-side mods, will continue to target the latest patches. This proposal is aimed at giving large mod developers a unified direction for porting and maintaining their mods.

**Q**: How would voting work? \
**A**: A vote hosted on a Discord or another platform, with a verification process in place to ensure that casted SMV votes are authentic. Disussion channels would also be opened to allow developers to further discuss their thoughts.

**Q**: How often would these votes occur? \
**A**: Once every two years seems ideal. This frequency strikes a balance between providing flexibility to account for new updates bringing technical improvements and version longevity.

**Q**: How would the mod developers be made aware of this proposal? \
**A**: Initally, word of mouth will be the best option. Curseforge staff have stated that they would consider supporting and promoting the project if they think is viable.  
To quote a conversion I had with Ryan Robson, CurseForge's Creator Relations Manager:
 > I can share any potential community-led projects you are working on with our team and we can support if it's something we think is viable 🙂

So, spread the word!
<details>
  <summary>Followup Curseforge related question some might have:</summary>

**Q**: Doesn't curseforge have a monetary incentive to keep mod developers on the latest version? \
**A**: Curseforge does not have an incentive to push mod developers to the latest version on the game. To quote Ryan again:
> We have no monetary incentive to push the latest version, and a big part of our platform is continuing to support some older versions and the modpacks they support. Part of the reason we may sometimes (i.e. in contests) push for higher versions is because the modding support is improved (such as better datapack support) on these versions, but overall we have no preference on which versions users create or play content on.
</details>
