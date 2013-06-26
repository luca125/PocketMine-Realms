# Realms _for PocketMine-MP_

This plugins registers and sends updates about the server to the [PocketMine Realms](http://realms.pocketmine.net/) service.
If you set it properly, you can manage the soft-whitelist in-game, adding players so they can see your server in their list.
You can also open/close the server from there.


## Configuration
| Name | Type | Description |
| :---: | :---: | :--- |
| MCPEListClaimServer| string | This should be your in-game name on Realms, case-sensitive. |
| 0.0.0.0 | string | The server external IP or domain. [Get your IP](http://www.whatismyip.com/) |
| 19132 | integer | The port to access the server. __It must be forwarded, if not, players won't be able to join the server.__ [Port Forwarding](http://portforward.com/) |


## Usage

Once you've set up everything, the new server should appear at the top of your PocketMine Realms list. Then, you can add new players to it.

If your server is on your LAN, you won't be able to join it through the PocketMine Realms interface. You'll have to go to _Play_, and it'll be there.

![](http://i.imgur.com/scwvExil.png)

![](http://i.imgur.com/KPsbBXTl.png)
