# Pingpongjs

# Basic Pong HTML and JavaScript Game

This is a basic implementation of the Atari Pong game, but it's missing a few things intentionally and they're left as further exploration for the reader.

<img width="300" height="233" alt="" src="https://user-images.githubusercontent.com/2433219/94984423-03b57400-0509-11eb-91b0-974280cec0a2.png">

## Further Exploration

- Score
  - When a ball goes past a paddle, the other player should score a point. Use [context.fillText()](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/fillText) to display the score to the screen
- Mobile and touchscreen support
  - Allow the game to be scaled down to a phone size. See https://codepen.io/straker/pen/VazMaL
  - Support [touch controls](https://developer.mozilla.org/en-US/docs/Web/API/Touch_events)
- Ball trajectory
  - The ball should change trajectory based on where it hit the paddle. For example, if it hit the topmost part of the paddle it should have a sharp angle upward, whereas if it hit the direct middle of the paddle it should move completely flat towards the other payer.
  
**Important note:** I will answer questions about the code but will not add more features or answer questions about adding more features. This series is meant to give a basic outline of the game but nothing more.

## Support

Basic HTML Games are made possible by users like you. When you become a [Patron](https://www.patreon.com/straker), you get access to behind the scenes development logs, the ability to vote on which games I work on next, and early access to the next Basic HTML Game.

### Top Patrons

- Karar Al-Remahy
- UnbrandedTech
- Innkeeper Games
