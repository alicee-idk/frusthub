local HttpService = game:GetService("HttpService")

if game.PlaceId == 74594314478567 then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/alicee-idk/animesagaX/refs/heads/main/README.md"))() 
elseif game.PlaceId == 135534863791172 then
   loadstring(game:HttpGet("https://raw.githubusercontent.com/alicee-idk/animeimmortals/refs/heads/main/README.md"))()
else
    warn("This game don't support my script")
end
