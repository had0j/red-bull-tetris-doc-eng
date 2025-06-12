# Red Bull Tetris unofficial rules document
((TN = translation note))

Game link: https://www.redbull.com/us-en/events/red-bull-tetris-united-states

Note: Only has touch controls. To play on computer press F12 to open DevTools on browser, toggle device toolbar ((TN: or press Ctrl+Shift+M)), then play by dragging the cursor.

## Controls

Swipe to move, tap to rotate, swipe down to soft drop (two cells distance). When releasing, if there was a noticeable up-swipe/down-swipe movement a moment before the release then hold/hard drop.

Gravity is one cell per second. Any input can reset lock delay, and there is an infinite up-kick bug.

## Scoring

+1 per cell for soft drop, +2 per cell for hard drop.

Clearing 1/2/3/4+ lines give 100/300/500/800 points respectively.

T0/1/2/3 give 200/800/1200/1600 points respectively. ((TN: "T" short for T-Spin))

Clearing a power-up gives an additional +1000 points.

Note that the only criterion for a T piece to be considered a T-Spin is that the piece's last movement was a rotation using the fifth-kick.

Another note: non-clear T0's are also part of "any clear action" in the multiplier energy and power-up energy sections below.

Scoring aside from soft drop and hard drop points are increased by multiplier, starting with x1, being able to increase after receiving multiplier energy.

There is no combo system, B2B, or Perfect Clears.

## Multiplier energy

Any clear action gives +4. After reaching 20, the multiplier is increased by +1 and multiplier energy is cleared.

Energy will gradually deplete over time. x1 to x6 has slower depletion, whereas starting from x7 the energy bar becomes red and depletion noticeably speeds up, causing it to be harder to increase.

## Power-up energy

Placing a piece adds +1, and any clear action adds +5.

After two seconds have passed since the last placement, power-up energy automatically increases over time (around 0.27 per second, or for accuracy 74 seconds to 20).

After reaching 20 the next piece becomes a power-up piece (which has one power-up block) and power-up energy is cleared.

## Power-up effects

When power-up blocks are cleared the following three effects are triggered (following the fixed order below) ((TN: clearing power-ups out of order causes the effects to be out of order too)):

1. Shifter: All blocks are shifted either left, down, left; right, down, right; or both sides, down, both sides, then filled rows are automatically cleared.
2. Pusher: Four rows of ((TN: clean)) garbage rise, then the six highest rows of the stack are cleared.
3. Filler: Directly fill nearly every hole in the stack.
