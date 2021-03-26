# Project Legacy Discord RPC API Simplified

This is a simplified version of Discord API Made by Project Legacy.org

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
