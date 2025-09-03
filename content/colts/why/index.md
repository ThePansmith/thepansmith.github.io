---
title: "Why does mod porting take so long?"
date: 2025-08-29
draft: false
showAuthor: false
authors:
      - pansmith
summary: "A sandy explanation for a common curseforge question."
description: "A sandy explanation for a common curseforge question."
tags: ["colts"]
---
 
While discussing the COLTS proposal with some friends, the topic of mod players asking for mod ports came up. Personally, I believe it's primarily a simple issue of mod players not being aware of how Mojang versioning works, so let this be a simple explanation.

## Why?

The main reason is that Mojang likes breaking things fairly often.

Imagine a mod as a sandcastle. Normally, if you were to leave a sandcastle unattended, over time the wind or tides would wear it down until it's just a pile of sand. In a typical project, you either get the wind or the tides. Perhaps the project that you are modding updates often, but the changes are generally small and manageable, fixing your sandcastle isn't a big issue, and could even be partially automated. Constant a small but constant effect on your project if you want to keep it updated with the latest version. Other projects might be closer to the tides, where the project you're modding has massive updates with big breaking changes, but these updates are infrequent enough that keeping up isn't too bad. Sure, you have to patch a big hole in your castle all at once, but you only have to do this every couple of years, and the new material might even improve your castle.

Mojang, on the other hand, combines the two together. Rapid, breaking updates that are a massive pain to keep up with. This was already an issue, but with game drops becoming the primary way to deliver content, this has gotten even worse, opting to rewrite swaths of the codebase in a "minor" update. Now, that doesn't necessarily mean the changes Mojang makes are bad, some of them can be good for development, but it doesn't change the fact that most mod developers simply don't have the time to be constantly "repairing their sandcastles" like that. Hence, mod developers tend to update sporadically, perfering to do a larger task at once rather than try to keep up with every single patch and burn out. (Remember that this is hobby work, after all.) Even then, its not the greatest solution, and it often leads to developers burning out regardless, and a lack of coordination between mod developers tends to make the issue even worse.

If you'd like some extra reading, take a look at [this](https://notes.highlysuspect.agency/blog/the_treadmill/), and ponder at how it's somehow gotten worse since it was written.

## What to do?

In terms of the effort required for porting the mods themselves, not much can be done. Some form of wrapper to allow mods to run on multiple versions isn't a viable option.

Now, backporting future content, on the other hand, [is already a thing](https://www.curseforge.com/minecraft/mc-mods/vanillabackport).

That, combined with some kind of recurring vote for a [Community LTS](https://thepansmith.github.io/posts/colts/) version, so that mod developers can communicate with each other on what versions to settle on, would be the simplest option. It would allow you to play with both your favorite mods and the new vanilla content at the same time. So, instead of [begging mod developers to port their mods to a version the second it comes out](https://github.com/mezz/JustEnoughItems/issues/4040), consider asking them about COLTS instead.

(Thumbnail is from Tropicraft)