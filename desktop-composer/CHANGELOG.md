- Review remaining compliance gaps

0.10.56

  Lock counter to white
  No red color change

0.10.55

  Use provided grok png via css mask
  Add hover support for masked icon
  Commit root landing + asset

0.10.54

  Change plus tooltip to Thread

0.10.53

  Brutalist counter: raw number
  No bg border radius or padding

0.10.52

  Smaller 10px counter
  No border, on top of divider line

0.10.51

  Shrink counter to 11px
  Show only when remaining <=10

0.10.50

  Fix Grok icon paths to match reference
  Thicker frame, bolder slash, accurate pointer

0.10.49

  Fix globe icon bright white
  Apply text-x-dim explicitly

0.10.48

  Match audience globe to other icon colors
  Replace Grok icon with provided graphic

0.10.29

  Add icon hover states
  Scale + shadow circle
  Bold on hover
  Custom pill tooltips

0.10.30

  Fix text overflow outside card
  Add min-w-0 to flex-1
  break-all + no spellcheck

0.10.31

  Remove native title tooltips
  Fix double tooltip overlap
  Keep only custom pills

0.10.32

  Remove yellow + red from counter
  Ring always purple
  Number always dim gray

0.10.33

  Remove purple from counter too
  Ring + number both dim gray
  Completely neutral

0.10.34

  Tighten spacing left of globe
  Reduce gap + remove ml-1
  Globe closer to divider

0.10.35

  Tighter globe spacing
  gap-1 + -ml-2 on wrapper
  Much closer to |

0.10.36

  Back off globe spacing
  gap-1.5 + -ml-1
  Not too tight

0.10.37

  Equal spacing around vertical line
  mx-1.5 on the | 
  Symmetric between counter and globe

0.10.38

  Pull globe closer to |
  mx-1 on line + -ml-1 on wrapper
  Globe not too far over

0.10.39

  Remove vertical line separator
  Clean gap-2 between ring and globe

0.10.40

  Remove hated ring completely
  Simple text counter, only shows when <= 40 remaining

0.10.41

  Add Free/Premium mode toggle in debug bar
  Free: counter only when <=10 remaining + hard stop
  Premium: counter completely hidden
  Replace purple with official X blue

0.10.42

  Free mode: hard 280 limit enforced in input (cannot type past)
  Cursor-adjacent counter (next to caret) only for free when <=10 remaining
  Removed old toolbar counter

0.10.43

  Cursor counter now reliably pinned bottom-right inside editor (Free only, <=10 remaining)
  Dynamic caret chasing removed (too flaky)

0.10.44

  Make editor counter much more visible for testing (bright blue + border)
  Temporarily show in Free mode whenever there's text (for visibility)
  Will tighten back to <=10 remaining after confirmation

0.10.45

  Further improved visibility of bottom-right editor counter (larger font, solid colors, border)
  Always on in Free for now so user can see it working

0.10.46

  Made counter extremely prominent (16px font, 3px white border, bright red/blue, shadow, z-9999)
  So it is impossible to miss at bottom-right inside editor in Free mode

0.10.47

  Fix Enter/Return not creating new line (highlightMentions + truncation were fighting native behavior on Enter)

0.3.0

  Hide icon row until focus in r1
  Extend reveal hide for toolbar

0.4.0

  Move audience and reply controls to header bar outside card
  Remove them from content area in r1

0.5.0

  Single icon trigger for combined audience + reply popup
  Select either in one menu

0.6.0

  Move world icon into toolbar row
  Same dim color as other icons

0.7.0

  Change reset to hammer icon
  Position in lower left corner

0.8.0

  Make reset hammer fixed to page lower left
  True debug tool positioning

0.9.0

  Replace broken hammer with "debug" text
  Cleaner debug label in corner

0.10.0

  Fix dimmed location pin icon
  Match visual style of other toolbar icons

0.10.1

  Undim location pin in baseline and r2
  Visual consistency across all three versions

0.10.2

  Add assets to composer-r2
  Complete standalone frozen reference

0.10.3

  Audience popup opens below icon like dropdown
  top-full instead of bottom-full

0.10.4

  Fix "Twitter Circle" label to "Circle"
  Current X terminology

0.10.5

  Add "Accounts you follow and who they follow" to who can reply
  Inserted above "Only accounts you mention"

0.10.6

  Make @mention purple in "Only accounts you mention" option
  Accent color for @handles

0.10.7

  Make @mention clickable with underline on hover
  cursor-pointer + hover:underline

0.10.8

  Remove Circle from audience options
  Contenteditable editor with live purple + clickable @handles on type

0.10.9

  Fix excessive line breaks when pasting multi-line text with @handles
  Better newline → <br> handling + paste re-highlight

0.10.10

  Improve character counter ring to better match real X
  Move rotation to progress circle only for accurate gap position

0.10.11

  Move audience button from left icons to right side (near + / count area)
  Swapped position with the add post button area

0.10.12

  Swap plus icon button and audience button
  Plus now before countWrap; audience inside count area

0.10.13

  Remove border circle from plus and audience icons
  Match style of other toolbar icons (no border)

0.10.14

  Move plus icon to left icon menu area
  Make plus and audience icons h-5 w-5 and match other toolbar icons

0.10.15

  Make plus icon color match other toolbar icons
  Remove explicit text-x-accent

0.10.16

  Move count number inside the ring
  Absolute centered text over the SVG counter (9px bold)

0.10.17

  Post button now enables + turns white as soon as there is any text
  Disabled only when empty or over limit

0.10.18

  Make countdown circle larger (24px)
  r=10, updated dash values and text size

0.10.19

  Make countdown circle even larger (28px)
  r=11.5, bigger text, better visual weight

0.10.20

  Fix Post button not enabling on first characters
  Call updateCount() before highlightMentions + initial sync

0.10.21

  Make Post button enabling reliable with contenteditable
  Decouple updateCount (fast path) from highlightMentions (rAF + keyup backup)

0.10.22

  Remove .overflow red dotted underline for over-limit text

0.10.23

  Fix cursor jumping to front when pressing Enter in editor
  Save/restore caret position around highlightMentions innerHTML replacement

0.10.24

  Stop fighting native Enter behavior
  Only run mention highlighting replacement when @ is present in the text

0.10.25

  Larger character counter ring (32px) with more internal padding around the number
  Reduced left margin on audience globe icon

0.10.26

  Change "@mention" to "mention" in Who can reply options
  Remove @ symbol from the audience dropdown label

0.10.27

  Force empty DOM on clear so placeholder reappears
  Fix :empty after contenteditable backspace debris

0.10.28

  Remove purple clickable styling from "mention" in Who can reply dropdown

0.1.0

  Add .gitignore
  Fix avatar cls
  Remove post console
  Update readme for standards

0.1.1

  Remove stack note
  Clean readme footer

0.2.0

  Reorganize into desktop-composer
  Create baseline folder
  Create composer-r1 folder
  Move all assets inside
