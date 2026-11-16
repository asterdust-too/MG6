# MG6
## Devlog
### Prompt Answers

1. I think that when you write that Update method, the game will lag because it is taking time away from game resources to generate that for loop. This could be used to create a whole bunch of assets, and would make the game slow down, since Update runs every frame. Constantly making new objects until the loop finishes, say 300, would run down performance but let you play even through it.
2. When playing, I noticed that I got stuck in the roof of the level. This is because I stopped jumping while I was passing through the tilemap, and since the player character doesn't have collision while they are jumping, they phase through the roof. As a result, the cat gets stuck in the roof and has no choice to jump outside the bounds of the level to free themselves.
