This plugin allows people with the permission send messages to offline players. On the players next connection, these messages will be printed to them via chat

## Permissions
- `offlinemail.use` -- players with this permission can send messages
- `offlinemail.admin` -- players with this permission can wipe players inboxes

## Usage
The plugin comes with commands usable both via ingame chat command, and RCON console. These commands are used to manipulate players inboxes.

## Chat Commands
- **/mail \<playername\> <"message">**
- **/clearmail <playername>**

## Console commands
- **mail \<playername\> <"message">**
- **clearmail \<playername\>**

## Configuration File
```json
{
  "Settings": {
    "Console Name": "Admin",
    "Message Delay Time": 3.0
  }
}
```
