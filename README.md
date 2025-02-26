local HttpService = game:GetService("HttpService")

if game.PlaceId == 74594314478567 then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/alicee-idk/animesagaX/refs/heads/main/README.md"))() 
elseif game.PlaceId == 135534863791172 then
   loadstring(game:HttpGet("https://raw.githubusercontent.com/alicee-idk/animeimmortals/refs/heads/main/README.md"))()
elseif game.PlaceId == 77752950694673 then
  loadstring(game:HttpGet("https://raw.githubusercontent.com/alicee-idk/animebotao/refs/heads/main/README.md"))()
elseif game.PlaceId == 17236692255 then
  loadstring(game:HttpGet("https://raw.githubusercontent.com/alicee-idk/ascentelemental/refs/heads/main/README.md"))()
else
    warn("This game don't support my script")
end
