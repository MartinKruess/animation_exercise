# Small animation exercises

<video src="preview/Animations_are_great!.mp4" controls title="Title"></video>

## Assistance

- each animation uses only transition (property and duration)
- the main container is centered and the sections have a height of 90vh
- the inner containers have a fixed height of 14rem
- the divs have a width and height of 10rem

## Effects

- the animations start when hovering!
- rotations require an indication in deg (circle)
- section 1 animation duration of 2s
- section 2 animation duration of 4s

Tip: The distance that rolling objects cover in one revolution is the circumference ;)
This creates a realistic effect (does not roll in place)

## Toggle switch

Creating a toggle switch consists of 4 steps.

Step 1:
We need a container, a label is suitable for this, since only this can address a checkbox.

Step 2:
We need a checkbox, which we make invisible with display: none.

Step 3:
We need content that we completely style!
The content conatiner MUST be on the same level as the checkbox!

Step 4:
We say what should happen when checkbox = checked
Changes to the display properties or the width/height are popular

```
<label>
  <input type="checkbox" id="name">
  <p>Clickable element/heading/icon/:before/:after</p>
  <ul>
    <li>Content...</li>
  </ul>
</label>
```

## Difficulty

- section 1: roll animation - very easy
- section 2: Decoration - easy
- section 3: toggle-switch - a bit harder

there is a solution branch you can look at if you get absolutely stuck. Otherwise just write and ask ;)