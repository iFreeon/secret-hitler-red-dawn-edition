# Secret Hitler Red Dawn Edition
Step into an era of heightened political tension and espionage with the Red Dawn Edition for the acclaimed social deduction game, Secret Hitler.  

This is a standalone game that tightens up some of the expansion game-play and puts it together in a package that is easier consumer for new players to consume.  

## Design Principals
1. Make the docs easy to update and deploy.
1. Game setting is 1933 where liberal parties are trying to hold together a fragile republic. Historically this is one year before the establishment of the Third Reich. 
2. Love the 3rd faction idea. This version will use Communists. 
3. 14 players seems like the sweet spot for max players.
4. Pull inspiration from original, socialist and XL expansions but treat this as a stand alone game. Explain the player motivation, win conditions, setup (board, player, policy), flow, and optional items.  
5. Game mechanics and balancing focus game boards, player faction mix, policy card mix, and extras. 
6. Win conditions must be unique and distinct to each faction.  No shared win conditions.   
7. Secret roles should advance or hinder a faction. Avoid roles with personal win conditions as this takes away from group dynamic. 


## Convert Docs to PDF
Docs are in markdown and converted to PDF, not the prettiest but much easier to collaborate on, update, and see change in git.

### Install Converter
On Windows
```
choco install pandoc
choco install rsvg-convert python miktex
```

### Run Convert MD to PDF
```
pandoc Secret_Hitler_Red_Dawn_Rules.md -o Secret_Hitler_Red_Dawn_Rules.pdf --variable geometry:margin=0.5in
```