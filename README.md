<h1 align="center">
  MCTools
</h1>
<p align="center">
        <img src="https://github.com/mullak99/MCTools/actions/workflows/master_deploy.yml/badge.svg" />
        <img src="https://github.com/mullak99/MCTools/actions/workflows/beta_deploy.yml/badge.svg" />
        <img src="https://github.com/mullak99/MCTools/actions/workflows/api_master_deploy.yml/badge.svg" /><br>
        <img src="https://github.com/mullak99/MCTools/actions/workflows/api_beta_deploy.yml/badge.svg" />
        <img src="https://img.shields.io/github/issues/DJStompZone/MCTools" />
        <img src="https://img.shields.io/github/issues-pr/DJStompZone/MCTools" /><br>
        <img src="https://img.shields.io/github/stars/DJStompZone/MCTools" />
	<a href="https://discord.stomp.zone" alt="StompZone Discord">
        <img src="https://img.shields.io/discord/599808270655291403?logo=discord&label=StompZone%20Discord" />
    </a>
</p>

 
A web app for a few Minecraft-related tools, specifically for resource packs.

### Links (Web App)
- [MCTools (Stable)](https://mctools.mullak99.co.uk)
- [MCTools (Beta)](https://mctools-beta.mullak99.co.uk)

### Links (API)
- [MCTools API (Stable)](https://mctools-api.mullak99.co.uk/swagger)
- [MCTools API (Beta)](https://mctools-api-beta.mullak99.co.uk/swagger)

## Features

### Textures Tool

Tool for comparing textures within resource pack against vanilla. Tool will output a list of matching, missing, and unused textures.

Allows for customising what textures are excluded.

### Potion Converter

Tool for converting potions between Java and Bedrock formats (currently limited to converting from Java only).

### Vanilla Assets

Tool for downloading vanilla assets for specific versions.

### Version Difference

Tool for comparing two versions of Vanilla (Java) Minecraft's assets. Lists showing added, removed, changed, and unchanged textures will be generated. These can be exported, or paths copied.

Changed textures additionally can be compared pixel-by-pixel and exported, resulting in Blue and Magenta pixels showing what has or hasn't changed. A README is provided in the exported zip explaining this.

## API

The Stable and Beta API's can be found linked above. API-related code can be found in the MCTools.API directory.

## SDK

The SDK can be manually downloaded from the GitHub Actions:
- [Stable SDK](https://github.com/mullak99/MCTools/actions/workflows/sdk_master_package.yml)
- [Beta SDK](https://github.com/mullak99/MCTools/actions/workflows/sdk_beta_package.yml)

Or via the [NuGet](https://nuget.mullak99.co.uk/packages/mctools.sdk).
This can also be used within Visual Studio by adding `https://nuget.mullak99.co.uk/v3/index.json` as a package source.
