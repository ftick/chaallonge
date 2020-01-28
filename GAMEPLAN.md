## Motivation
I organize free weekly tournaments for UW Smash Club and kept running to seeding issues due to sudden influxes of new players and too many players overall to consistently seed well without 10 minutes of deliberation. The ultimate goal is to create something that helps avoid repeated matchups early in bracket, early "teamkills", and is minimal enough to use in presentation that TOs just getting into the swing of things can easily pick up and use.

## Base app
- Informative seeding page (hover to check recent history)
- Highlight players in both pages
    - Green if Braacket match found
    - Grey if Braacket match not found

## TODO
- Start finding appropriate API calls that need to be made to Braacket
- Pick colours for highlights (look nice on browser)
- Research how to make Chrome extension / Firefox add-on

## Features
- New optional field per entry that forms a manual link to Braacket
    - Change behaviour of clicking edit icon to editing advanced options
    - Clicking text will take over rename functionality
    - If above not possible, make text clickable to activate Braacket match finder dialog
- Avoid recent WR1/WR2 matchups (highlight, don't fix)
- "Sand-bagging" checkbox
    - changes colour, maybe include closest emoji approximation to character selection
- 