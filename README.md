# BombDefusal

Created when I watched RTGames struggle with **Keep Talking and Nobody Explodes** *(He exploded)*.

Visit at: https://fiendchain.github.io/KeepTalkingAndNobodyExplodesSolver/

## Possible improvements
All bomb modules are functional, however the interface is considerably clunky for a few modules.

| Module | Issue | Solutions? |
| --- | --- | --- |
| Knobs | Looks | Use bootstrap buttons to make a good looking grid |
| Simon Says | Instructions are not aligned properly | Fix the html and css |
| Who's first | Module selector button is blocked by the row element, and the buttons change size depending on text | Fix html |
| Buttons | For the strip LED instructions, you cannot use it while holding the button in game | Show a list of the colours and instructions, instead of making it selectable |
| Maze | Maze is just loaded as an image. Maze indicator changing is unintuitive and confusing | Make map render as an overlay. Use left and right click to change position of maze indicators. |
| Password | Interface is clunky and much large than other card | Work on html to improve looks. Use an input field like the github tags input field to add letters more easily |

## Disclaimer
This project was started as a introductory project into Angular 6, and as result the code is probably horrible. Also I haven't implemented any end to end or unit tests. 
