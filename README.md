# Office Clicker v0.9.8 - The Offline Overtime Update

Welcome back to the inbox mines.

This release gives **Office Clicker** a tidy performance pass, a few quality-of-life upgrades, and one very important new feature: your corporate empire now keeps grinding while you are away. Because apparently even closing the tab is not enough to escape Outlook.

## New Feature: Offline Earnings

Your workforce now continues generating emails while you are away from the game.

When you return, Office Clicker checks how long it has been since your last save, calculates your current passive email generation rate, and awards the emails your corporate machine produced during that time.

To keep things balanced and prevent the universe from collapsing under unread notifications, offline earnings are capped at **8 hours**.

In practical terms:

- Close the game or step away.
- Your progress is saved with a timestamp.
- When you come back, the game calculates your offline time.
- You receive passive earnings based on your current emails-per-second rate.
- The earnings are added to both your current email total and lifetime output.
- A cheerful little report tells you how much damage your department caused while unsupervised.

Example:

> While you were away, your department sent 42.7 Million emails. Nobody read them.

Beautiful. Terrible. Efficient.

## Improvements

### Smoother Game Loop

The passive income system has been rebuilt to use a cleaner animation-based loop instead of relying on a fixed 100ms interval.

This should make the game feel smoother, behave better after tab throttling, and generally reduce the amount of tiny spreadsheet gremlins running around in the background.

### Cleaner UI Updates

The game no longer checks achievements constantly during passive income ticks. Achievement checks now happen when they actually matter, such as after buying upgrades or automation.

Less unnecessary work. More pretending to be productive.

### Better Save Data

Saves now store the important moving parts of your progress rather than dragging along all the static game configuration.

This makes saves leaner, easier to maintain, and better prepared for future balancing changes.

Old saves should still load correctly, because we respect legacy systems even when they contain cursed procurement logic.

## Fixes

### Fixed Number Formatting

Large numbers now display correctly.

Previously, some values were getting promoted through the corporate hierarchy far too quickly. Millions were becoming Billions, Billions were becoming Trillions, and Finance was starting to ask questions.

The formatter now scales properly through:

- Million
- Billion
- Trillion
- Quadrillion
- And many increasingly suspicious suffixes beyond that

### Corporate Takeover Matrix Now Does Something

The Executive Store item **Corporate Takeover Matrix** now actually contributes to gameplay instead of sitting around looking important in meetings.

Very realistic, but not ideal for balance.

### General Cleanup

- Removed duplicate CSS.
- Removed an extra closing HTML tag.
- Tidied some internal save/load handling.
- Reduced unnecessary processing in the main loop.

## Not Included

Department Synergies have **not** been added in this release.

They are still sitting in a meeting room somewhere, aligning stakeholders, waiting for a future roadmap discussion.

## Final Note

This update is all about making Office Clicker smoother, cleaner, and better at rewarding players who step away from the chaos.

Which is ironic, because the game now encourages your office to keep sending emails while you are gone.

Truly, innovation.
