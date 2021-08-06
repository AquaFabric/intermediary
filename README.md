# Intermediary mappings

This repository contains the match information between different versions of Minecraft, created by wafflecoffee, as well as the "intermediary" mappings, which is an intermediary naming form which tries to keep names the same across versions and mapping changes.

This is structured the same as [FabricMC/intermediary](https://github.com/FabricMC/intermediary), but with some other versions not supported by the Fabric project.

## Files included in this repo

* __mappings/\<mcversion\>.tiny__: Intermediary mappings in the Tiny mapping format.
* __matches/\<mcversion1\>-\<mcversion2\>.matches__: Matches between Minecraft versions, created by wafflecoffee with the aid of Matcher.

## Generating / updating mappings

In general, you're going to want to use the following tools:

* [Matcher](https://github.com/FabricMC/Matcher) can be used to create a match file between two JARs. In addition, it can load Enigma-format mappings, which can be used as an aid in figuring out changes.
* [Stitch](https://github.com/FabricMC/stitch) is a toolset for generating mappings based on match files. "updateIntermediary" is used to add a new entry to the chain based on the previous entry and a match file.

## License

I provide these intermediary mappings under the Creative Commons Zero license, so all can benefit.
