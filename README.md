# Project Legacy Discord RPC API Simplified

This is a simplified version of Discord API Made by Project Legacy.org

![picture alt](https://raw.githubusercontent.com/KaramBotStudios-DEV1/Discord-RPC-API/main/Preview.jpg "Title is optional")

## Dependencies

 * DIscord RPC
 * Project Legacy Simplified Discord RPC API

## Initialization

```C#
using SimpleDiscordRPC;

RPCCient ClientName = new RPCCient();
```

## Functions

Set Discord RichPresense [1]

```C#
SetFullRPC(Client ID, State, Details, LargeImageKey, LargeImageText, SmallImageKey, SmallImageText);
```
Set Discord RichPresence [2]

```C#
SetDiscordRPC(Client ID);
```

Add State Manually

```C#
AddState(State);
```

Add Details Manually

```C#
AddDetails(Details);
```

Add Small Image Manually

```C#
AddSmallImageKeyAndText(SmallImageKey, SmallImageText);
```

Add Large Image Manually

```C#
AddLargeImageKeyAndText(LargeImageKey, LargeImageText);
```

## Examples

Set Discord Rich Presence [1]

```C#
using SimpleDiscordRPC;

RPCCient DiscordClient = new RPCCient();

DiscordClient.SetFullRPC(912832157235431, "Playing CS:GO", null, "csgoimagekey", "CS:GO", null, null);
```

Set Discord Rich Presence [2]

```C#
using SimpleDiscordRPC;

RPCCient DiscordClient = new RPCCient();

DiscordClient.SetDiscordRPC(912832157235431);
```

Add State Manually

```C#
using SimpleDiscordRPC;

RPCCient DiscordClient = new RPCCient();
DiscordClient.SetDiscordRPC(912832157235431);
DiscordClient.AddState("Hello World!");
```

Add Details Manually

```C#
using SimpleDiscordRPC;

RPCCient DiscordClient = new RPCCient();
DiscordClient.SetDiscordRPC(912832157235431);
DiscordClient.AddDetails("Playing Game");
```

Add Large Image Manually

```C#
using SimpleDiscordRPC;

RPCCient DiscordClient = new RPCCient();
DiscordClient.SetDiscordRPC(912832157235431);
DiscordClient.AddLargeImageKeyAndText("csgoimagekey", "CSGO");
```

Add Small Image Manually

```C#
using SimpleDiscordRPC;

RPCCient DiscordClient = new RPCCient();
DiscordClient.SetDiscordRPC(912832157235431);
DiscordClient.AddSmallImageKeyAndText("Nice Logo", "Playing Logo");
```
