# Secret Hitler Red Dawn Edition
Step into an era of heightened political tension and espionage with the Red Dawn Edition for the acclaimed social deduction game, Secret Hitler.  

This is a standalone game that tightens up elements of the expansions and adds a few new twists.  The goal is to make SHRDE more accessible to veterans and new players alike. This version has not been released yet, but you can see work in progress rules here: [SHRDE Rules](https://github.com/iFreeon/secret-hitler-red-dawn-edition/blob/main/Secret_Hitler_Red_Dawn_Rules.md)

## Design Principals
1. Game setting is 1933 where liberal parties are trying to hold together a fragile republic. Historically this is one year before the establishment of the Third Reich. 
2. Love the 3rd faction idea. This version will use Communists. 
3. Make the docs easy to update and deploy.
4. 12 to 14 players seems like the sweet spot for max players.
5. Pull inspiration from original, socialist and XL expansions but treat this as a stand alone game. Explain the player motivation, win conditions, setup (board, player, policy), flow, and optional items.  
6. Game balancing should focus on: game boards, party loyalty, policy cards, etc.
7. Win conditions must be unique and distinct to each faction.  No shared win conditions.   
8. Secret roles should advance or hinder a faction. Avoid roles with personal win conditions as this takes away from group dynamic. 
9. As player counts increase, presidential should increase. lots of goodness to go around.  


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
