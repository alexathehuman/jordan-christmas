# Free Box
A phone-friendly Christmas treasure hunt for Jordan. First playable prototype.

## Play
Open index.html in a browser. No installation or build step is needed.

## GitHub Pages
Upload index.html, style.css, game.js, music.js, winter-background.png, gondola-jordan.png and .nojekyll to the root of a GitHub repository. In the repository's Settings → Pages, choose Deploy from a branch, then main and / (root). GitHub will provide the published URL. Generate the Christmas QR code from that stable URL after testing the game on a phone.

## Challenge rules
90 seconds. Twelve shuffled face-down cards form six pairs: New Skis, Bicycle, A good book, Coffee mug, Socks, Gift for mom. Flip two cards to find a matching pair. Mismatches flip back after 400ms, or immediately when another card is selected; no extra time penalty. Matched pairs stay visible. The timer and one-use powerups sit above the card grid; the collection list, pair counter, and redundant directions are removed. Pause and info controls have additional spacing. Finding all six pairs stops the clock and opens the ending automatically. Coffee adds 15 seconds once per run; unplugging the laptop pauses the clock for 10 seconds once per run. Running out of time shows “You dropped the boxes!” with a retry or a 60-second extension. Gravity-driven boxes and item contents tumble, bounce and fall off the screen. Jordan appears as part of one cohesive gondola illustration with natural proportions, hair pulled back and a raised hand. The cabin follows the cable painted in the background on the opening and ending only; gameplay has no gondola or reserved spacer. The final cabin departs off screen unless reduced motion is enabled.

## Reward status
The ending is a clearly labeled preview. It sends no email and contains no real gift card or recipient details. A separate server endpoint is required for automatic email delivery. Never put claim codes, email API credentials, or private recipient information in the public repository. The future server must verify a one-time claim token, use durable claim/send records and support safe retries.

## Included
Original code-drawn item illustrations and a provisional Jordan character, plus generated snowy Telluride-inspired artwork and a generated unified Jordan-and-gondola illustration. The gold gift card sits inside an open Free Box with a moving sheen and no crossing lid; animations respect reduced-motion preferences. Jordan's original photography is not embedded. This version is a matching game; the photo gallery remains a future addition.

## Pause and instructions
Pause and info buttons sit beside the timer. Either pauses play; info opens instructions. The card grid is hidden and inert while paused, and Escape or the resume button returns to play. Matches advance directly to the ending. No footer credit is shown. The opening button says Start; instructions read “Match all the pairs before the last gondola leaves.”

## Audio and readability
Original upbeat, mellow instrumental music is synthesized locally with Web Audio, begins muted and is enabled using the header sound button. It pauses in hidden tabs and can be muted at any time. No recordings or external audio requests are used. Intro instructions have a dark contrast panel, the location has a pin icon, and feedback uses a compact bottom strip. The purse uses warm tan leather colors and rounded corners with curved handles.

## Validation
Automated game-logic checks cover deck contents, matches, mismatches, input locking, powerups, timer expiry, replay, extension and boarding. Music scheduling and mute controls also pass mocked logic checks. Browser appearance, actual audio playback and phone playtesting are still pending.

## Next
Playtest difficulty and phone layout; refine item illustrations; connect the real reward endpoint; publish to GitHub Pages; generate and test the QR code. Progress lasts for the current play session only. Optional Google Fonts have system fallbacks.
