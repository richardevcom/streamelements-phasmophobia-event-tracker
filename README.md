**Phasmophobia Event Tracker** (remastered)

Phasmophobia Event Tracker for your Twitch stream.
_(original author ![@GlichedMythos](https://github.com/GlitchedMythos/se-widgets))_

[![Video tutorial](https://i.ibb.co/N1SFgWj/Screenshot-1.png)](https://youtu.be/OIZgBi3ZI9s)

![Watch Tutorial](https://youtu.be/OIZgBi3ZI9s)

# Example Commands
| Name | Command | Action |
|--|--|--|
| Name Reset | !ghostreset | Reset the ghost |
| Name Input | !ghostname "name" | Change name to "name" |
| Toggle EMF | !ge | Change EMF to opposite of current state |
| Toggle Spirit Box | !gs | Change Spirit Box to opposite of current state |
| Toggle Fingerprints | !gf | Change Fingerprints to opposite of current state |
| Toggle Orbs | !go | Change Ghost Orbs to opposite of current state |
| Toggle Ghost Writing | !gw | Change Ghost Writing to opposite of current state |
| Toggle Freezing Temps | !gt | Change Freezing Temps to opposite of current state |
| Optional Objectives | !oo "a" "b" "c"<br />!oo "a" | Set the optional objectives. Replace a, b or c with the objective you'd like below |
| Toggle Optional Objective 1 | !o1 | Toggles Optional Objective 1 from being marked or not |
| Toggle Optional Objective 2 | !o2 | Toggles Optional Objective 2 from being marked or not |
| Toggle Optional Objective 3 | !o3 | Toggles Optional Objective 3 from being marked or not |
| Set Counter Name | !setcounter "phrase" | Set's the phrase before the number in the counter |
| Set Counter Number | !setcounternumber "num" | Set's the number in the counter to the number input |
| Increment the counter by 1 | !counterup | Adds one to the counter number |
| Decrement the counter by 1 | !counterdown | Subtracts one from the counter number |

# Optional Objectives
| Objective | Possible Phrases |
|--|--|
| Motion Sensor | "mo" "motion" |
| Salt | "sa" "salt" |
| Photo | "ph" "photo" |
| Event | "ev" "event" |
| EMF | "em" "emf" |
| Crucifix | "cr" "crucifix" |
| Smudge Ghost (NON-Hunt) | "sm" "smudge" |
| Parabolic Microphone | "pa" "parabolic" "mic" |
| Escape | "es" "escape" |
| Smudge Ghost (During Hunt) | "hu" "hunt" |
| <25% Sanity | "san "sanity" |
| Candle | "ca" "candle" |

## Example Usage:
To get `Salt Photo Event`

    !oo sa ph ev

To get `Crucifix Motion Salt`

    !oo cr motion sa

Individual Objectives can be used and can be toggled on and off

To get `Smudge`

    !oo sm

# How to Add to StreamElements?!?
1. Create a Brand New Overlay
2. Add a new Widget and select "Static/Custom" followed by Custom Widget
3. Select the Widget under Layers on the left. Select Open Editor. This will give you a code screen with several tabs. DON'T BE SCARED. For each tab, delete everything that exists and paste the related content from the files listed in this folder into the editor and save.

## Which files represent which?!? 
* widget.html -> html
* widget.css -> css
* widget.js -> js
* fields.json -> fields
* data.json -> data

