Hello, its youngstar!

well I got bored and I need to make a loader for BlueX so I decided to make it just like a library as well 

Code:
local CustomLoader = loadstring(game:HttpGet("https://raw.githubusercontent.com/Snakeboy99/BLUEX/main/Loader_BlueX.lua"))()
local SET_UP = CustomLoader("BlueX Library", "json",{
   URL = "https://raw.githubusercontent.com/Snakeboy99/BLUEX/main/Games/GamesFile.json";
})


I don't want to explain how it works cause its pretty simple
if you can't figure it out feel free to ask for help 

JSON TABLE FORMAT: 

Code:
{
   "4483381587":{"name":"baseplate","Script":"pathtoscript","Working":true}
}

LUA TABLE FORMAT: 

Code:
local GAMES = {
  [id] = {name="baseplate", script="scriptpath", working=true}
}
return GAMES

You can test on Empty Baseplate
