# Triggering "Infinite scroll"

## Test case 1

### Actions
1. Open [Top Channels](http://www.twitch.tv/directory/all) page.
2. Block channels until few of them left.

### Expected results
1. Infinite scroll should be triggered.

## Test case 2

### Actions
1. Open [Top Channels](http://www.twitch.tv/directory/all) page.
2. Block all visible channels.
3. Block more channels after new channels have been loaded.
4. Refresh the page.

### Expected results
1. Infinite scroll should be triggered twice.
