# 5CMenu
API for https://menu.jojodmo.com. To use the API, use the endpoint https://5cmenu-cache.jojodmo.com/v1/getMenu/?diningHall=<dining_hall>&startTime=<unix_timestamp>, where `<dining_hall>` is one of mcconnel, collins, malott, frank, frary, or oldenborg. For example:

https://5cmenu-cache.jojodmo.com/v1/getMenu/?diningHall=hoch&startTime=1675670400&language=en

This will respond with the JSON data for that menu

## Using this codebase

Everything here is pretty hacky and not well commented, so read at your own peril :)

The entry into this codebase is the `run` function in `menuParser.php`.
