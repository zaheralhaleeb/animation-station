# Animation Station

Bring these graphics to life with CSS!

## Installation

Run `npm install`

## Usage

- To run the live server, run `npm run serve`
- To run the SASS file watcher run `npm run scss-watch`
- For a one-time SASS/SCSS build, run `npm run scss-compile`
- For a one-time SASS linter check, run `npm run sass-lint`

## Preparing for your assignments

**Important!** Before working on these assignments, please make sure to create
a new branch with the name "solution" in the terminal;

`git checkout -b solution`

When you have finished making your changes, use the following command to mark all changed files
to be added to the next commit;

`git add .`

And then commit as follows;

`git commit -m "Your message"`

Replace the text _Your message_ with something a short summary of the changes you've made

It's good practise to separate your code changes into multiple commits,
for example - if you're building a website, you might want to have 1 commit for your header code,
one for your navigation code, etc.

## Submitting your assignments

Once you've finished your changes and you are ready to submit your work, you can push the changes
to the remote server via the following commands;

If you've already pushed before, you can simply use:

`git push`

If however you get an error, telling you the remote branch for "solution" does not exist, use the
following command:

`git push --set-upstream origin solution`

Once this is done, create a **Pull Request** from the `solution` branch to the `master` branch
via the GitHub interface.

## Research

[CSS Transform](https://developer.mozilla.org/en-US/docs/Web/CSS/transform)

[Using CSS animations](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations)

## Assignments

### Rainy days

1. Using the 'raindrops' background image, set a repeating background for the `<section>` 'rainy-days'.

2. Animate the background to move from top to bottom using CSS3 features `@keyframes` and `animation`.

3. Create a new HTML element inside the `<section>` tag, then using CSS3 set the 'totoro' image to move
from right to left.

### Retro platformer

1. Set the background colour for the `<section>` tag 'retro-platformer' to something blue.

2. Create an HTML element inside the `<section>` tag, then using CSS3 set the 'bullet-bill' image to move
from right to left.

3. Create a new HTML element inside the `<section>` tag, then set the 'mario' image as background.

4. Animate the mario character to run, jump, land and continue running

### Digital Traffic

1. Using the 'isometric' background image, set a repeating background for the `<section>` 'digital-traffic'.

2. Create a new HTML elements inside the `<section>` tag, for each of the following graphics:
    - `ambulance.png`
    - `bus.png`
    - `lorry.png`
    - `tractor.png`
    - `truck.png`
    
3. Using `position: absolute`, place the elements next to each other, to imitate a road of 2 lanes

4. Animate each vehicle to all move alongside each other at the same speed (so they don't crash!)
and that they follow the isometric lines accurately.

Hint: You will need to move them horizontally and vertically, but you may have to use some trial and error
to determine the correct values.

### Space Journey

1. Using the 'space' background image, set a static background for the `<section>` 'space-journey'.

2. Create a new HTML element inside the `<section>` tag using position absolute, set the 'spaceship' image as
the background.

3. Animate the spaceship position:
    - from the top left of the screen to the top right of the screen
    - from the top right of the screen to the bottom right of the screen
    - from the bottom right of the screen to the bottom left of the screen
    - from the bottom left of the screen to the top left of the screen
    - ensure the animation performs in one continuous loop

4. Research the CSS3 property `transform`

5. Using the property `transform: rotate()`, animate the spaceship rotation to coincide
with it's position on the screen
