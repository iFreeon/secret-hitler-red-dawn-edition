# Secret Hitler Red Dawn Edition
Step into an era of heightened political tension and espionage with the Red Dawn Edition for the acclaimed social deduction game, Secret Hitler.  

This is a standalone game that tightens up elements of the expansions and adds a few new twists.  The goal is to make SHRDE more accessible to veterans and new players alike. This version has not been released yet, but you can see work in progress rules here: [SHRDE Rules](https://github.com/iFreeon/secret-hitler-red-dawn-edition/blob/main/Secret_Hitler_Red_Dawn_Rules.md)

## Design Principals
1. Game setting is 1933 where liberal parties are trying to hold together a fragile republic. Historically this is one year before the establishment of the Third Reich. 
2. Re-work rules, to make the 3rd party (Communists) feel like a more natural addition to the game.
3. Win conditions must be unique and distinct to each party.  No shared win conditions.   
4. 12 to 14 players seems like the sweet spot for max players.
5. Make the docs easy to update and deploy.
6. Pull inspiration from original, socialist and XL expansions but treat this as a stand alone game. Explain the player motivation, win conditions, setup (board, player, policy), flow, and optional items.  
7. Secret roles should advance or hinder a faction. Avoid roles with personal win conditions as this takes away from group dynamic. 
8. As player counts increase, presidential should increase. lots of goodness to go around.  
9. Game balancing should focus on good gameplay and less on mechanics that extend the game.


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

## Other Tools
- Investigate this for card layout: https://www.dextrous.com.au/