# Atom Cheatsheet (Linux version).
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Atom Cheatsheet</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Paul Dunne</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

I created this as a printable version of **Jesse Kasky's** excellent **atom-keybinding-cheatsheet** [Github KeyBinding Cheatsheet Package](https://github.com/jkasky/atom-keybinding-cheatsheet)

CheatSheet Source Code: https://github.com/pd-gmit/atom-cheatsheet.git

<!---
My first iteration I was using keyboard images .. but then switched to
to the keyboard tag <kbd> </kbd>
Here is some of the original source for this cheat sheet for reference:
Open the command palette (ctrl-shift-p)   ![CTRL](./keys/ctrl.png)  ![SHIFT](./keys/shift.png)
<img src="./keys/ctrl.png" alt="Drawing" style="width: 70px;"/>
<img src="./keys/shift.png" alt="Drawing" style="width: 70px;"/>
<img src="./keys/P.png" alt="Drawing" style="width: 70px;"/>
-->

## window
| Keys | Action        |
|:-----|---------------:
| <kbd>F11</kbd> | Toggle full screen
| <kbd>Ctrl</kbd> <kbd>+</kbd> |Increase font size
| <kbd>Ctrl</kbd> <kbd>=</kbd> |Increase font size
| <kbd>Ctrl</kbd> <kbd>-</kbd> |Decrease font size
| <kbd>Ctrl</kbd> <kbd>_</kbd> |Decrease font size
| <kbd>Ctrl</kbd> <kbd>0</kbd> |Reset font size
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>p</kbd> | Run package specs
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>f</kbd> | reload
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>Ctrl</kbd> <kbd>&#8595; </kbd> |focus on pane below
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>Ctrl</kbd> <kbd>&#8592; </kbd> |focus pane on left
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>Ctrl</kbd> <kbd>n</kbd> |focus on next pane
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>Ctrl</kbd> <kbd>p</kbd> |focus on previous pane
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>Ctrl</kbd> <kbd>&#8594;</kbd> |focus on pane on right
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>Ctrl</kbd> <kbd>&#8593;</kbd>  |focus on pane above
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>l</kbd> |toggle dev tools
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>W</kbd>| close

## tree-view
| Keys | Action        |
|:-----|---------------:
| <kbd>a</kbd>  | add file|
| <kbd>Alt</kbd> <kbd>&#8592; </kbd> | recursive collapse directory
| <kbd>Alt</kbd> <kbd>&#8594; </kbd>| recursive expand directory
| <kbd>backspace</kbd> | remove
| <kbd>Ctrl</kbd> <kbd>0</kbd>| toggle focus
| <kbd>Ctrl</kbd> <kbd>1</kbd>| open selected entry in pane 1
| <kbd>Ctrl</kbd> <kbd>2</kbd>| open selected entry in pane 2
| <kbd>Ctrl</kbd> <kbd>3</kbd>| open selected entry in pane 3
| <kbd>Ctrl</kbd> <kbd>4</kbd>| open selected entry in pane 4
| <kbd>Ctrl</kbd> <kbd>5</kbd>| open selected entry in pane 5
| <kbd>Ctrl</kbd> <kbd>6</kbd>| open selected entry in pane 6
| <kbd>Ctrl</kbd> <kbd>7</kbd>| open selected entry in pane 7
| <kbd>Ctrl</kbd> <kbd>8</kbd>| open selected entry in pane 8
| <kbd>Ctrl</kbd> <kbd>9</kbd>| open selected entry in pane 9
| <kbd>Ctrl</kbd> <kbd>&#91;</kbd>| collapse directory
| <kbd>Ctrl</kbd> <kbd>&#92;</kbd>| toggle
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>&#91;</kbd>| recursive collapse directory
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>&#93;</kbd>| recursive expand directory
| <kbd>Ctrl</kbd> <kbd>c</kbd>| Copy
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>Ctrl</kbd> <kbd>b</kbd>| toggle
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>&#8595;</kbd>| open selected entry down
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>h</kbd>| open selected entry left
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>k</kbd>| open selected entry up
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>l</kbd>| open selected entry right
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>h</kbd>| open selected entry left
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>j</kbd>| open selected entry down
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd></kbd>| open selected entry left
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>&#8592;</kbd>| open selected entry left
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>&#8594;</kbd>| open selected entry right
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>&#8593;</kbd>| open selected entry up
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>C</kbd>| copy full path
| <kbd>Ctrl</kbd> <kbd>v</kbd> | paste
| <kbd>Ctrl</kbd> <kbd>x</kbd> | cut
| <kbd>Ctrl</kbd> <kbd>&#124;</kbd> | reveal active file
| <kbd>d</kbd>| duplicate
| <kbd> &#9249;</kbd>| remove
| <kbd>Enter</kbd>| open selected entry
| <kbd>F2</kbd> | move
| <kbd>h</kbd> | collapse directory
| <kbd>I</kbd> | toggle vcs ignored files
| <kbd>l</kbd> | expand directory
| <kbd>&#8592;</kbd> | collapse directory
| <kbd>m</kbd> | move
| <kbd>&#8594;</kbd> | expand directory
| <kbd>Shift</kbd> <kbd>A</kbd> | add folder


## pane
| Keys | Action        |
|:-----|---------------:
| <kbd>Alt</kbd> <kbd>1</kbd> | show item 1|
| <kbd>Alt</kbd> <kbd>2</kbd> | show item 2|
| <kbd>Alt</kbd> <kbd>3</kbd> | show item 3|
| <kbd>Alt</kbd> <kbd>4</kbd> | show item 4|
| <kbd>Alt</kbd> <kbd>5</kbd> | show item 5|
| <kbd>Alt</kbd> <kbd>6</kbd> | show item 6|
| <kbd>Alt</kbd> <kbd>7</kbd> | show item 7|
| <kbd>Alt</kbd> <kbd>8</kbd> | show item 8|
| <kbd>Alt</kbd> <kbd>9</kbd> | show item 9|
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>W</kbd>| close other items
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>Ctrl</kbd> <kbd>w</kbd> | close other items
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>&#8595;</kbd>|split-down |
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>&#8592; </kbd> | split-left|
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>&#8594; </kbd>| split-right|
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>&#8593; </kbd>| split-up|
| <kbd>Ctrl</kbd> <kbd>PgDn</kbd> | show next item|
| <kbd>Ctrl</kbd> <kbd>PgUp</kbd> | show previous item|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>T</kbd>| reopen closed item|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>PgDn</kbd>| move item right|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>PgUp</kbd>| move item left|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>&#8633;</kbd>|show previous item|
| <kbd>Ctrl</kbd> <kbd>&#8633;</kbd>| show next item|

## editor
| Keys | Action        |
|:-----|---------------:
| <kbd>Alt</kbd> <kbd>b</kbd>| move to beginning of word|
| <kbd>Alt</kbd> <kbd>d</kbd>| delete to end of word|
| <kbd>Alt</kbd> <kbd>f</kbd>| move to end of word|
| <kbd>Alt</kbd> <kbd>h</kbd>| delete to beginning of word|
| <kbd>Alt</kbd> <kbd>Shift</kbd> <kbd>B</kbd>| move to end of word|
| <kbd>Alt</kbd> <kbd>Shift</kbd> <kbd>F</kbd>| slect to end of word|
| <kbd>Alt</kbd> <kbd>Shift</kbd> <kbd>&#8595;</kbd>| add selection below
| <kbd>Alt</kbd> <kbd>Shift</kbd> <kbd>&#8593;</kbd>| add selection above
| <kbd>Ctrl</kbd> <kbd>/</kbd> | toggle line comments|
| <kbd>Ctrl</kbd> <kbd> < </kbd> | scroll to cursor|
| <kbd>Ctrl</kbd> <kbd>&#91;</kbd> | outdent selected rows|
| <kbd>Ctrl</kbd> <kbd>&#93;</kbd> | indent selected rows|
| <kbd>Ctrl</kbd> <kbd>&#91;</kbd> | outdent selected rows|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>&#91;</kbd> | fold current row|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>&#93;</kbd> | unfold current row|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>f</kbd> | fold selection|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>Shift</kbd> <kbd>P</kbd>| log cursor scope|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>z</kbd> | checkout head revision|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>{</kbd> | fold all|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>}</kbd> | unfold all|
| <kbd>Ctrl</kbd> <kbd>&#9003;</kbd> | delete to beginning of word|
| <kbd>Ctrl</kbd> <kbd> &#9249;</kbd> | delete to end of word|
| <kbd>Ctrl</kbd> <kbd> &#8595;</kbd> | move line down|
| <kbd>Ctrl</kbd> <kbd> Enter</kbd> | newline below|
| <kbd>Ctrl</kbd> <kbd> j </kbd> | join lines|
| <kbd>Ctrl</kbd> <kbd> K</kbd> <kbd>Ctrl</kbd> <kbd>0</kbd>  | unfold all|
| <kbd>Ctrl</kbd> <kbd> K</kbd> <kbd>Ctrl</kbd> <kbd>1</kbd>  | fold at indent level 1|
| <kbd>Ctrl</kbd> <kbd> K</kbd> <kbd>Ctrl</kbd> <kbd>2</kbd>  | fold at indent level 2|
| <kbd>Ctrl</kbd> <kbd> K</kbd> <kbd>Ctrl</kbd> <kbd>3</kbd>  | fold at indent level 3|
| <kbd>Ctrl</kbd> <kbd> K</kbd> <kbd>Ctrl</kbd> <kbd>4</kbd>  | fold at indent level 4|
| <kbd>Ctrl</kbd> <kbd> K</kbd> <kbd>Ctrl</kbd> <kbd>5</kbd>  | fold at indent level 5|
| <kbd>Ctrl</kbd> <kbd> K</kbd> <kbd>Ctrl</kbd> <kbd>6</kbd>  | fold at indent level 6|
| <kbd>Ctrl</kbd> <kbd> K</kbd> <kbd>Ctrl</kbd> <kbd>7</kbd>  | fold at indent level 7|
| <kbd>Ctrl</kbd> <kbd> K</kbd> <kbd>Ctrl</kbd> <kbd>8</kbd>  | fold at indent level 8|
| <kbd>Ctrl</kbd> <kbd> K</kbd> <kbd>Ctrl</kbd> <kbd>9</kbd>  | fold at indent level 9|
| <kbd>Ctrl</kbd> <kbd> K</kbd> <kbd>Ctrl</kbd> <kbd>l</kbd>  |lower case|
| <kbd>Ctrl</kbd> <kbd> K</kbd> <kbd>Ctrl</kbd> <kbd>u</kbd>  | upper case|
| <kbd>Ctrl</kbd> <kbd>l</kbd>  |select line|
| <kbd>Ctrl</kbd> <kbd>&#8592;</kbd>  |move to beginning of word|
| <kbd>Ctrl</kbd> <kbd>&#8594;</kbd>  |move to end of word|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd> C</kbd>  |copy path|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd> D</kbd>  |duplicate lines|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd> K</kbd>  |delete line|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd> Enter</kbd>  |newline above|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd> &#8592; </kbd>  |select to beginning of word|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd> &#8594; </kbd>  |select to end of word|
| <kbd>Ctrl</kbd> <kbd> &#8593; </kbd>  |move line up|
| <kbd>End</kbd> |move to end of sceeen line|
| <kbd>Enter</kbd> |newline|
| <kbd>Esc</kbd> |consolodate selection|
| <kbd>Home</kbd> |move to first character of line|
| <kbd>Shift</kbd> <kbd>End</kbd> |select to end of line|
| <kbd>Shift</kbd> <kbd>Home</kbd> |select to first character of line|
| <kbd>Shift</kbd> <kbd>Tab</kbd> |outdent selected rows|
| <kbd>Tab</kbd> |indent|

# Notifications
| Keys | Action        |
|:-----|---------------:
| <kbd>Alt</kbd> <kbd>Ctrl</kbd> <kbd>Tab</kbd> |select to first character of line|


#Find and Replace
| Keys | Action          |
|:-----|---------------:|
| <kbd>Alt</kbd> <kbd>Enter</kbd> | find all |
| <kbd>Alt</kbd> <kbd>F3</kbd>     |  select all  |
| <kbd>Ctrl</kbd> <kbd>Alt</kbd>  <kbd> / </kbd> | toggle regex option  |
| <kbd>Ctrl</kbd> <kbd>Alt</kbd>  <kbd>c</kbd> |  toggle case option |
| <kbd>Ctrl</kbd> <kbd>Alt</kbd>  <kbd>f</kbd> |  show replace |
| <kbd>Ctrl</kbd> <kbd>Alt</kbd>  <kbd>s</kbd> |  toggle selection option |
| <kbd>Ctrl</kbd> <kbd>Alt</kbd>  <kbd>w</kbd> |  toggle whole word option |
| <kbd>Ctrl</kbd> <kbd>d</kbd> |  select next |
| <kbd>Ctrl</kbd> <kbd>e</kbd>  |  use selction as find pattern |
| <kbd>Ctrl</kbd> <kbd>Enter</kbd>  |  confirm |
| <kbd>Ctrl</kbd> <kbd>Enter</kbd>  | replace all| ??|
| <kbd>Ctrl</kbd> <kbd>f</kbd>  | show|
| <kbd>Ctrl</kbd> <kbd>k</kbd> <kbd>Ctrl</kbd> <kbd>d</kbd>  | select skip|
| <kbd>Ctrl</kbd> <kbd>u</kbd>  | select undo|
| <kbd>F3</kbd>  | find next|
| <kbd>Shift</kbd> <kbd>Enter</kbd>  | previous show|
| <kbd>Shift</kbd> <kbd>F3</kbd>  | find previous|
| <kbd>Shift</kbd> <kbd>Tab</kbd>  | focus-previous|
| <kbd>Tab</kbd>  | focus next|

#Open on GitHub
| Keys | Action          |
|:-----|---------------:|
| <kbd>Alt</kbd> <kbd>g</kbd> <kbd>n</kbd> | blame |
| <kbd>Alt</kbd> <kbd>g</kbd> <kbd>c</kbd> | copy URL |
| <kbd>Alt</kbd> <kbd>g</kbd> <kbd>h</kbd> | history |
| <kbd>Alt</kbd> <kbd>g</kbd> <kbd>o</kbd> | file |
| <kbd>Alt</kbd> <kbd>g</kbd> <kbd>r</kbd> | branch compare |

#Git Diff
| Keys | Action          |
|:-----|---------------:|
| <kbd>Alt</kbd> <kbd>g</kbd> <kbd>d</kbd> | toggle diff list |
| <kbd>Alt</kbd> <kbd>g</kbd> <kbd>&#8595;</kbd> | move to next diff |
| <kbd>Alt</kbd> <kbd>g</kbd> <kbd>&#8593;</kbd> | move to previous diff |


#Snippets
| Keys | Action          |
|:-----|---------------:|
| <kbd>Alt</kbd> <kbd>Shift</kbd> <kbd>S</kbd> | "available" |
| <kbd>Shift</kbd> <kbd>Tab</kbd> | previous tab stop |
| <kbd>Tab</kbd> | expand|
| <kbd>Tab</kbd> | next tab stop|


#Bookmarks
| Keys | Action          |
|:-----|---------------:|
| <kbd>Alt</kbd> <kbd>Shift</kbd> <kbd>F2</kbd> | clear bookmarks |
| <kbd>Ctrl</kbd> <kbd>F2</kbd> | view all|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>F2</kbd> | toggle bookmarks |
| <kbd>F2</kbd> | jump to next bookmark |
| <kbd>Shift</kbd> <kbd>F2</kbd> | jump to previous bookmark |


#Encoding Selector
| Keys | Action          |
|:-----|---------------:|
| <kbd>Alt</kbd> <kbd>u</kbd> | show |



#Core
| Keys | Action          |
|:-----|---------------:|
| <kbd>&#9003;</kbd>| backspace |
| <kbd>Ctrl</kbd> <kbd>:</kbd> | cancel |
| <kbd>Ctrl</kbd> <kbd>a</kbd> | select all |
| <kbd>Ctrl</kbd> <kbd>c</kbd> | copy |
| <kbd>Ctrl</kbd> <kbd>End</kbd> | move to bottom |
| <kbd>Ctrl</kbd> <kbd>Home</kbd> | move to top |
| <kbd>Ctrl</kbd> <kbd>Insert</kbd> |copy |
| <kbd>Ctrl</kbd> <kbd>s</kbd> | save |
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>S</kbd> | save as |
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>Z</kbd> | redo |
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>&#8595;</kbd> | move down |
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>End</kbd> | select to bottom |
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>Home</kbd> | select to top |
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>&#8593;</kbd> | move up |
| <kbd>Ctrl</kbd> <kbd>v</kbd>  | paste |
| <kbd>Ctrl</kbd> <kbd>w</kbd>  | close |
| <kbd>Ctrl</kbd> <kbd>w</kbd>  | cancel |
| <kbd>Ctrl</kbd> <kbd>x</kbd>  | cut |
| <kbd>Ctrl</kbd> <kbd>y</kbd>  | redo |
| <kbd>Ctrl</kbd> <kbd>z</kbd>  | undo |
| <kbd>Delete</kbd> | delete |
| <kbd>&#8595;</kbd> | move down |
| <kbd>Enter</kbd> | confirm |
| <kbd>Escape</kbd> | cancel |
| <kbd>j</kbd> | move down |
| <kbd>k</kbd> | move up |
| <kbd>left</kbd> | move left |
| <kbd>Page Down</kbd> | page down|
| <kbd>Page Up</kbd> | page up|
| <kbd>&#8594;</kbd> | right|
| <kbd>Shift</kbd> <kbd>&#9003;</kbd>  | backspace |
| <kbd>Shift</kbd> <kbd>Delete</kbd>  | cut |
| <kbd>Shift</kbd> <kbd>&#8595;</kbd>  | select down |
| <kbd>Shift</kbd> <kbd>Insert</kbd>  | paste|
| <kbd>Shift</kbd> <kbd>&#8592;</kbd>  | select left |
| <kbd>Shift</kbd> <kbd>Page Down</kbd>  | select page down |
| <kbd>Shift</kbd> <kbd>&#8594;</kbd>  | select right |
| <kbd>Shift</kbd> <kbd>Tab</kbd>  | focus previous |
| <kbd>Shift</kbd> <kbd>&#8593;</kbd>  | select up |
| <kbd>Space</kbd>   | validate |
| <kbd>Tab</kbd>  | focus next |
| <kbd>Tab</kbd>  | confirm |
| <kbd>&#8593;</kbd>  | move up |


#asciidoc preview
| Keys | Action          |
|:-----|---------------:|
| <kbd>Cmd</kbd> <kbd>+</kbd>  | zoom in |
| <kbd>Cmd</kbd> <kbd>-</kbd>  | zoom out |
| <kbd>Cmd</kbd> <kbd>0</kbd>  | reset zoom |
| <kbd>Cmd</kbd> <kbd>=</kbd>  | zoom in |
| <kbd>Cmd</kbd> <kbd>_</kbd>  | zoom out |
| <kbd>Ctrl</kbd> <kbd>Alt</kbd>  <kbd>a</kbd> | toggle render on save only |
| <kbd>Ctrl</kbd> <kbd>Shift</kbd>  <kbd>a</kbd> | toggle |


#image view
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>+</kbd>  | zoom in |
| <kbd>Ctrl</kbd> <kbd>-</kbd>  | zoom out |
| <kbd>Ctrl</kbd> <kbd>0</kbd>  | reset zoom |
| <kbd>Ctrl</kbd> <kbd>=</kbd>  | zoom in |
| <kbd>Ctrl</kbd> <kbd>+</kbd>  | zoom in |
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>M</kbd> | toggle |

#markdown preview
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>+</kbd>  | zoom in |
| <kbd>Ctrl</kbd> <kbd>-</kbd>  | zoom out |
| <kbd>Ctrl</kbd> <kbd>0</kbd>  | reset zoom |
| <kbd>Ctrl</kbd> <kbd>=</kbd>  | zoom in |
| <kbd>Ctrl</kbd> <kbd>_</kbd>  | zoom out |
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>M</kbd> | toggle |


#application
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>,</kbd>  | show settings|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>o</kbd> | opendev|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>s</kbd> | run all specs|
| <kbd>Ctrl</kbd> <kbd>n</kbd>  | new-file|
| <kbd>Ctrl</kbd> <kbd>o</kbd> | open file|
| <kbd>Ctrl</kbd> <kbd>q</kbd>  | qiot|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>N</kbd> | new windows|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>O</kbd> | open folder|

#settings view
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>,</kbd>  | open|

#key binding resolver
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>.</kbd>  | togggle|

#spell check
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>:</kbd>  | correct misspelling|

#bracket matcher
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>&#93;</kbd>  | remove brackets from selection|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>.</kbd> | close tag|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>&#9003;</kbd> | remove matching bracket|
| <kbd>Ctrl</kbd> <kbd>m</kbd>  | go to matching bracket|

#keybindding cheat sheet
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>/</kbd> | toggle key binding cheat sheet|

#project find
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>/</kbd> | toggle regex option|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>c</kbd> | toggle case option|
| <kbd>Ctrl</kbd> <kbd>Enter</kbd>  | confirm|
| <kbd>Ctrl</kbd> <kbd>Enter</kbd>  | replace all|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>F</kbd> | show|


#symbols view
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>&#8595;</kbd> | go to declaration|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>&#8593;</kbd> | return from declaration|
| <kbd>Ctrl</kbd> <kbd>r</kbd>  | toggle file symbols|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>&#8593;</kbd> | return from declaration|

#autoflow
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>q</kbd> | reflow selection|


#fuzzy finder
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>b</kbd> | toggle buffer finder|
| <kbd>Ctrl</kbd> <kbd>p</kbd> | toggle file finder|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd><kbd>B</kbd> | toggle git status finder|
| <kbd>Ctrl</kbd> <kbd>t</kbd>| toggle file finder|

#go to line
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>g</kbd> | toggle |


#markdown pdf
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>C</kbd>| convert|

#style guide
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>G</kbd>| show|

#grammar selector
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>L</kbd>| show|

#command palette
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>Shift</kbd> <kbd>P</kbd>| toggle|

#auto complete
| Keys | Action          |
|:-----|---------------:|
| <kbd>Ctrl</kbd> <kbd>Space</kbd> <kbd>L</kbd>| toggle|

#tool panel
| Keys | Action          |
|:-----|---------------:|
| <kbd>Esc</kbd> | unfocus|


# Terminal Commands.
$ atom --dev --foreground --help --log-file --new-window --spec-directory --test --version --wait [file ...]': open the current project or directory in atom.

$ apm install [<package_name>]': install the given Atom package.

$ apm uninstall [<package_name>]...': delete the installed package(s).

$ apm search <package_name>': search for Atom packages/themes on the atom.io registry.

$ apm view <package_name>': view information about a package/theme in the atom.io registry.


# Other Useful Things.
$ git config --global core.editor "atom --wait"': configure Atom to be your Git commit editor.
