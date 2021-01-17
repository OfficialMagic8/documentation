---
description: A variety of tools and settings for Magic8 - Requires Manage Server
---

# 👮 Administrator Commands

## General Information

These commands can be accessed by all users with `Manage Server` permission. If you were to kick Magic8 then reinvite, your settings will still be saved.

## Anti-Ping

The Anti-Ping system is a method of preventing users from @mentioning a specified user. There are also bypass roles that can be set. For example, you'd set the staff roles of your server to be a bypass role.

{% hint style="warning" %}
It is actually impossible to prevent a user from pinging another. This system simply deletes the message and warns the user with a message you can customize.
{% endhint %}

**Base Command:** `antiping` or `ap` Anti-Ping Settings Menu

| Sub-Command | Usage | Information |
| :--- | :--- | :--- |
| adduser | &lt;user&gt; | Disable Pings For A User By ID Or @mention |
| removeuser | &lt;user&gt; | Re-enable Pings For A User By ID Or @mention |
| message | &lt;message&gt; | Ping Warning Message. Placeholder: {USER} |
| addrole | &lt;role&gt; | Add A Bypass Role By ID Or @mention |
| removerole | &lt;roles&gt; | Remove A Bypass Role By ID Or @mention |
| roles |  | View Current Bypass Roles |
| users |  | View Current Anti-Ping Users |

## Auto Voice Channels

Auto Voice Channels created limited user voice channels for gamers looking for groups. Duos Trios and Squads are the three current options available.

![Auto Voice Channels \(10 second cooldown\)](https://media1.giphy.com/media/mKD1b9By8Q1n3s4z0g/giphy.gif)

**Base Command:** `autovoice` or `av`

| Sub-Command | Usage | Information |
| :--- | :--- | :--- |
| create | &lt;duo\|trio\|squad&gt; | Create An Auto Voice Channel |
| delete | &lt;channel ID&gt; | Delete An Auto Voice Channel |
| reset |  | Delete generated channels and number IDs |
| name | &lt;duo\|trio\|squad&gt; | Set the name of a channel type |
| category | &lt;category ID&gt; | Set Category For Auto Voice Channels |
| cooldown | &lt;5-300 seconds&gt; | Joining/Leaving Auto Voice Channels Delay |
| info |  | Auto Voice Channel Settings Information |

## Fake Ping

Magic8 can edit your server's icon and put a notification badge where a normal ping would be. Your old server icon will be saved and sent to you. There is a 5 minute cooldown between using this command.

**Base Command:** `fakeping` or `fp`

## Language

Magic8 pulls almost every message sent from a GitHub repository. Most languages are incomplete, but English is 100% done. If a language does not have the translations, it will appear in English. Languages are set or viewed by their abbreviation. Example: `en` \(English\)

**Base Command:** `language` or `lang`

| Sub-Command | Usage | Information |
| :--- | :--- | :--- |
| set | &lt;language abbreviation&gt; | Sets the language of Magic8 for your server |
| help |  | Information about how Magic8 languages work |
| info | &lt;language abbreviation&gt; | View specific information of a language |
| list | \[page number\] | View all languages |

## Prefix Settings

The prefix can be set to anything desired, there is no limit on the length of it, just make sure that users are able to easily use it. @Magic8 will always be a working prefix. Simply run the command below and write a prefix afterwards. Anything after a space will not be saved!

**Base Command:** `prefix` or `pf`

## Toggle Command Settings

Commands that are not in [Information](../information.md) or [Administrator](./) can be toggled for all users within your server.

**Base Command:** `toggle` or `tog`

<table>
  <thead>
    <tr>
      <th style="text-align:left">Sub-Command</th>
      <th style="text-align:left">Usage</th>
      <th style="text-align:left">Information</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">toggle</td>
      <td style="text-align:left">[command]</td>
      <td style="text-align:left">
        <p>If no command is provided, toggled</p>
        <p>commands are shown, otherwise the</p>
        <p>provided command is toggled</p>
      </td>
    </tr>
  </tbody>
</table>

## Advanced Settings

Click the commands below to be taken to further detail if the menu in Discord did not help you enough!

**Base Command:** `settings` or `s`

| Sub-Command | Information |
| :--- | :--- |
| 8ball | [Magic 8 Ball Settings](settings.md#magic-8-ball-settings) |
| media | [Server Media Settings](settings.md#server-media-settings) |
| lfg | [Looking For Group Settings](settings.md#looking-for-group-settings) |
| funchannel | [Restrict Fun Commands to Channels](settings.md#fun-commands-channel-settings) |
| minigamechannel | [Restrict Minigames to Channels](settings.md#minigame-channel-settings) |
| miscellaneouschannel | [Restrict Miscellaneous Commands to Channels](settings.md#miscellaneous-channel-settings) |
| reactionchannel | [Restrict Reaction Commands to Channels](settings.md#reaction-commands-channel-settings) |

