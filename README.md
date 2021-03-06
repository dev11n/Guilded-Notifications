# Guilded-Notifications
## What does it do?
Whenever you get a message (`MessageCreated` -> Guilded.NET), it flashes the Guilded icon in your taskbar.

## Why?
Because Guilded's notifications are broken, and you may want to get that orange flash as a bullet-proof way of never missing a message.

Or as me, use Do not Disturb and still get notifications. *because the red color looks better than the other ones*

## Assembly
Created with: `Jetbrains Rider`

C# Version: `9.0`

SDK: `.NET Core 3.1 LTS`

## Warning
This is really not a reliable solution for Guilded's notifications, as it will break after a short time due to the `MessageCreated` event not firing after a while.

## Libraries
- [Guilded.NET](https://github.com/Guilded-NET/Guilded.NET/) - Unofficial way of creating self-bots.
   - Please be aware that this is in the gray zone of Guilded's ToS, and may or may not get your account terminated. You'll also not get any support for using the API as it's currently undocumented.
- [Newtonsoft.Json](nuget.org/packages/Newtonsoft.Json/) - Parsing the `config.json` file
