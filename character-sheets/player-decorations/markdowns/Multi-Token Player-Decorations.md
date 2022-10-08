<!-- Multi-Token: Player Decorations -->
<!-- common-game-assets -->
<!-- character-sheets -->
<!-- player-decorations -->

<!-- Reference URLS -->
[Tougher Together Repo]: https://github.com/Tougher-Together-DnD "Tougher Together DnD"
[Repo Files]: https://github.com/Tougher-Together-DnD/common-game-assets/tree/main/character-sheets/player-decorations "Tougher Together Files"

[Collection Icon]: https://raw.githubusercontent.com/Tougher-Together-DnD/common-game-assets/main/character-sheets/macro-bars/images/menu-icon.png#icon
[Avatar]: https://raw.githubusercontent.com/Tougher-Together-DnD/common-game-assets/main/character-sheets/macro-bars/images/art-avatar.webp
[Screenshot]: https://raw.githubusercontent.com/Tougher-Together-DnD/common-game-assets/main/character-sheets/player-decorations/images/decoration-screengrab.gif#screenshot

<!-- API URLs -->
[TokenMod-URL]: https://github.com/Roll20/roll20-api-scripts/tree/master/TokenMod

<!-- External Tools -->
[Github-URL]: https://github.com/Tougher-Together-DnD
[Firefox-URL]: https://www.mozilla.org
[VTTES Enhancement Suite-URL]: https://addons.mozilla.org/en-US/firefox/addon/roll20-enhancement-suite/

<style>
/* CSS style for NaturalCrit Homebrew render. */
.phb#p1{ text-align:left; }
.phb#p1:after{ display:none; }
.phb p+p { margin-top:.2em; }
.phb blockquote { margin-top:1em; margin-bottom:2em; }
.phb h1, .phb h2, .phb h3, .phb h4, sup, span { color:#006699; }
span { font-weight:bold; }
ul li { line-height:2; }
.phb table tbody tr td { border:1px solid #1C6EA4; }
th:empty { display:none; }
</style>

# Player Decorations

## Macros*
*Note: Macros to be shared between Players and Dungeon Masters, or are intended as universal token actions, should be loaded into game under "Collections" tab.*

* Commit-to-Map-Layer
* Resize-Double
* Resize-Half
* Resize-Pixels
* Resize-Units

***Required API Scripts:***  
<span>* All</span> [TokenMod][TokenMod-URL]  

<br>

## Usage
1. Drag this Character Sheet to the tabletop.
1. Right Click and select "Multi-Sided".
1. Scroll through the available images and select the decoration you want.
1. Using the above macros resize the decoration to the desired dimensions.
1. Rotate and Move the decoration into place for your playing enjoyment.
1. When you have the decoration where you want, use the Commit macro to move it to the Map Layer. Be careful, only the GM can select the token after doing this.

***Commit-to-Map-Layer.*** Move the token to the Map Layer. It will be un-selectable.

***Resize-Double.*** Will scale the token up twice in size.

***Resize-Half.*** Will scale the token down to half its size.

***Resize-Pixels.*** Will set the width and height of the token to the inquired pixels.

***Resize-Units.*** Will set the width and height of the token in map units (usually 5ft = 1 grid square = 70 pixels).

### Using Macro bar
If the macros are not available as a token action, a player can use the macros from this character sheet.

1. Go under the *Collections* (![][Collection Icon]) tab and turn on macro bar.
2. This will display a space at the bottom of the window under player names.
3. Open this character sheet, go to *Attributes and Abilities*, and select *Show in Macro Bar*.
4. You can right click on the bar to get options for renaming and changing its color.

![][Screenshot]

<br>

## Footnotes
1. [Source Files][Repo Files]