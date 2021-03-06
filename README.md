# esx_status_hud

ESX  Status HUd  is an plugin for ESX to show status bar:

## Requirements

* Auto mode
    - [esx_status](https://github.com/esx-framework/esx_status)
    - [esx_basicneeds](https://github.com/esx-framework/esx_basicneeds)
* NodeJs
    - [node-js](https://nodejs.org/en/)
* VueCli
    - [vue-cli](https://cli.vuejs.org/) 3.x.

## Download & Installation

### Using Git
```
cd resources
git clone https://github.com/lucianfialhobp/esx_status_hud [esx]/esx_status_hud
```

### Installation
- Install interface submodule `git submodule update --init --recursive`
- Install dependecies `cd status_hud && npm install`
- Build interface `npm run build`
- Add this in your `server.cfg`:

```
ensure esx_status_hud
```

## Configuration
All settings is in `config.lua`

### Language
Set language default: en  
`Config.Locale = 'en'`  
Can you get all languages avaiable in `./locales/`

### Interval
Set hud update interval default: 5000  
`Config.UpdateHudInterval = 5000`

### Basic styles
Define hud size this can receive any unit px, vh and etc  
`Config.HudSize = '25rem'`

Define bar Weight only these three types *is-small, is-medium and is-large*  
`Config.BarWeight =  'is-small'`


# Legal
### License
esx_status_hud - ambulance script for fivem

Copyright (C) 2020 Lucian Fialho

This program Is free software: you can redistribute it And/Or modify it under the terms Of the GNU General Public License As published by the Free Software Foundation, either version 3 Of the License, Or (at your option) any later version.

This program Is distributed In the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty Of MERCHANTABILITY Or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License For more details.

You should have received a copy Of the GNU General Public License along with this program. If Not, see http://www.gnu.org/licenses/.
