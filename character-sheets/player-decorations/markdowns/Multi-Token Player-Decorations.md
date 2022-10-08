<!-- Multi-Token: Player Decorations -->

<!-- Reference URLS -->
[Homebrewery]: https://homebrewery.naturalcrit.com/ "Naturalcrit's Homebrewery V3.0.0"
[Repo Files]: https://github.com/Tougher-Together-DnD/common-game-assets/tree/main/character-sheets/player-decorations "Tougher Together Files"
[Repo Raw Path]: https://raw.githubusercontent.com/Tougher-Together-DnD/common-game-assets/main/character-sheets/player-decorations/images/ "Incomplete path; add image filename"

<!-- Images -->
[Main Banner]: https://raw.githubusercontent.com/Tougher-Together-DnD/common-game-assets/main/character-sheets/containers/images/none.png#banner ""
[Screenshot]: https://raw.githubusercontent.com/Tougher-Together-DnD/common-game-assets/main/character-sheets/player-decorations/images/decoration-screengrab.gif#screenshot

<!-- API URLs -->
[TokenMod-URL]: https://github.com/Roll20/roll20-api-scripts/tree/master/TokenMod

<style>
/* CSS style for NaturalCrit's Homebrewery V3.0.0 */
.page { background-color: transparent; }
.page#p1{ text-align:left; }
.page#p1:after{ display:none; }
.page p+p { margin-top:.2em; }
.page blockquote { margin-top:1em; margin-bottom:2em; }
.page h1, .page h2, .page h3, .page h4, sup, span { color:#006699; }
span { font-weight:bold; }
ul li { line-height:2; }
.page table tbody tr td { border:1px solid #1C6EA4; text-align:left; }
th:empty { display:none; }

/* css for markdown */
img[src*="#banner"] { display:block; margin-left:auto; margin-right:auto; width:750px; }
img[src*="#screenshot"] { display:block; margin-left:auto; margin-right:auto; width:500px; }
</style>

{{wide
## Player Decorations
*Note: Macros to be shared between Players and Dungeon Masters, or are intended as universal token actions, should be loaded into game under "Collections" tab.*
:
#### Macros*
* Commit-to-Map-Layer: *Move the token to the Map Layer. It will be un-selectable.*
* Resize-Double: *Will scale the token up twice in size.*
* Resize-Half: *Will scale the token down to half its size.*
* Resize-Pixels: *Will set the width and height of the token to the inquired pixels.*
* Resize-Units: *Will set the width and height of the token in map units (usually 5ft = 1 grid square = 70 pixels).*

***Required API Scripts:***  
<span>* All</span> [TokenMod][TokenMod-URL]  

<br>

#### Usage
1. Drag this Character Sheet to the tabletop.
1. Right Click and select "Multi-Sided".
1. Scroll through the available images and select the decoration you want.
1. Using the above macros resize the decoration to the desired dimensions.
1. Rotate and Move the decoration into place for your playing enjoyment.
1. When you have the decoration where you want, use the Commit macro to move it to the Map Layer. Be careful, only the GM can select the token after doing this.
:
![][Screenshot]

<br>

#### Using the Macro bar
If the macros are not available as a token action, a player can use the macros from this character sheet.

1. Go under the *Collections* tab and turn on macro bar.
2. This will display a space under the player names.
3. Open this character sheet, go to *Attributes and Abilities*, and select *Show in Macro Bar*.
4. You can right click on the bar to get options for renaming and changing its color.
:
## Footnotes
1. [Source Files][Repo Files]
}}