# Brief: Backgammon Mentor (backgammon training app, French and English)

Read AGENT_BRIEF.md first: its tools, rules and final report all apply, with the changes below.

## About the app
- The app follows the phone's language: **French** on a French phone, **English** on every other
  language. Never report a missing translation into another language, or right-to-left not applied.
  Do report: text left in the wrong language (French on an English phone or the reverse), text that
  is cut, overlaps, or does not fit the screen at this device's text size.
- Two pillars on the home screen: **Jouer** / Play (a game against the computer opponent "Mentor") and
  **Entraînement** / Training (series of positions: you play your move, you get a verdict with an explanation).
  Games are analysed move by move afterwards (**Revue**). There is also **En ligne** (online play).
- Words: *dame* = checker, *videau* = doubling cube, *Doubler* / *Prendre* / *Passer* = double / take /
  pass, *partie* = game, *coup* = move.
- You play a checker by tapping it, then tapping the point where it goes (dragging may also work).
- Decided on purpose, not bugs (never report them): no arrows or lines drawn on the board; no numbers
  or percentages in the cube explanations; Mentor's move plays in full and a tap during Mentor's turn
  does nothing; the app is always light (it ignores the system dark theme) and has no theme or text-size
  setting of its own (it follows the phone's text size); one tap on a checker plays the die at once;
  Mentor's card sits on the middle of the board and stays there; positions 2 and 3 of the first series
  have no back arrow; the streak flame stays at 0 until a finished game or a series of 5; no summary
  screen after the first series of 3; the board points are narrower than 44 pt / 48 dp on purpose;
  the sheet grabber is the system one; text lines are balanced (a paragraph may wrap before the right
  edge, and its last two words stay together); the English is American (US flag, US spelling) whatever
  the phone's English region.
- On an iPad, if a tap seems to do nothing, check your coordinates against the screenshot scale before
  reporting it: a tool mismatch is not an app bug.
- Never buy anything, never start a real payment or subscription. Look at a Premium screen if you
  meet one, then close it. Never create an online account with a real-looking e-mail: if En ligne
  asks for an account, use `<persona>@example.com` once; if it still needs more, report it and move on.

## Your goal (replaces the persona's goal)
Budget: about **60 actions**. As your persona, a backgammon player who wants to improve:
1. First launch: go through the welcome and onboarding until the home screen.
2. Pick the part of the app given by your persona id below, and use it for real:
   - anna, kenji, ravi, felipe, clara, yuki, giulia: **Jouer**. Start a game against Mentor, play at
     least 6 of your own moves (roll, move checkers, try the cube if offered), then leave the game
     and come back to it from the home screen. Check that it resumes where you left it.
   - malik, layla, olga, mehmet, noah, amira, wei: **Entraînement**. Do a full series of positions,
     read each verdict and explanation, try one wrong move on purpose, then open the progress or
     statistics screen.
   - grace, lucia, jonas, mateo, sven, minjun: **everything once**, quickly: home, a few moves in
     Jouer, two positions in Entraînement, the Revue of a game if one exists, settings, En ligne,
     then relaunch the app and check what was kept.
3. Then open the settings, change one thing that matters to you (text size, sound, theme...), leave
   and come back to check it applied.

## Look closely at
- The board: are all checkers, the dice and the cube visible and not cut, on THIS device (small
  phone, tablet, very large text)? Does a tap on a checker do what you expect?
- Anything that blocks a game or a series, a crash, a frozen screen, a button that does nothing.
- Buttons hidden behind the home bar, notch, or cut at large text sizes.
- Rotate to landscape once (if your tool can) on a tablet, and say how the board looks.
