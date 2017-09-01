# VIPSystem

## [KEEPOMOD](http://keepomod.com)

VIPSystem is an automated donations store system that works with CS: GO.
Payments are handled securely through PayPal and actions are automatically applied on the server when payment is received.

#### This system is not integrate with SourceBans/SourceBans++ 

### Contact me on steam to purchase : http://steamcommunity.com/profiles/76561198192893746
### DEMO : http://keepomod.com/projects/VIPSystem/

## VIPSystem Features!

  - Easy to install and use for players and system owners.
  - Secure (Using PDO), automatic payment handling through PayPal IPN.
  - Ability to add servers and custom plans for 1 server or all servers.
  - Easy view/edit/remove information from the admin panel.
  - Ability to login with steam.
  - View latest 10 payments made, how much payments made this month and on 24 hours.

## Supported Games
- Currently only CS: GO.

## Requirements

- PHP >= 5.5
- MySQL Database
- curl enabled
- PDO enabled
- Hosting that accepting remote database for the server plugin.


## Installation
- Drag and drop the web files to your hosting and set your database info at `core/db/db-config.php `.
- Set your URL and steam apikey for login with steam at `core/steamauth/SteamConfig.php `.
- Import the SQL file from `SQL/vipsystem.sql` to your phpmyadmin.
- Login with steam at your site, go to `users` table and set `admin` column to `1`.
- Refresh the page and click Admin Panel, go to settings and set the settings of your site.
- Create new server at `Package Manager` and install the plugin on your server.
- Set the flag you want at `admin_groups.cfg`.
- Get the server id from the panel and set the cvar at `csgo/cfg/sm_vipsystem.cfg` to the server id from the panel.
- Congratulations you are done installing `VIPSystem' !

# Rules

- When buying the system you are accepting the rules.
- You are not allowed to publish or share any code of the system.
- You are not allowed to change the credits at the bottom of the site.
- I'm not responsible if your system got hacked by making any changes to the system.
