# kopy-kate v1.3.24 BETA

![alt text](https://www.kittyseedbox.tk/img/kopykate-screenshot.png)

## Change Log:

### v1.3.24
- Improved player CSS.
- Added option to either upload instant webseed or upload torrent

## Introduction:

KopyKate is a ZeroNet site; it is an alternative to YouTube, but instead of hosting videos on webservers, it uses decentralized databases in order to store magnet links for videos, and then uses WebTorrent in order to stream them. Note that WebTorrent (WebRTC) and BitTorrent use two different protocols, and the videos can only be seeded by clients made specifically for WebTorrent (e.g. WebTorrent Desktop). Even watching a video means you're simultaneously seeding, for as long as the tab open! Users also have the option to upload webseeds to a CORS-enabled webserver. This allows torrents to temporarily use a backup file from an HTTP server, until enough peers are available!

## Install instructions:

1. KopyKate is now clonable. Simply turn on ZeroNet, go to ZeroHello main page, and then select 'Clone' from the options next to the site on the list.
2. The cloned site is now 100% modifiable. Be sure to submit any pull requests to GitHub. Cheers!

## Credits to:

- Ferros Aboukhadijeh, creator of WebTorrent, Instant.io and WebTorrent.Desktop
- Creators of ZeroTalk @ ZeroNet, which the core engine and site structure was based on.
- Creators of ZeroNet for giving this project a platform to begin with.
- Creator of ZeroTube for originally coming up with the idea.

## To-Do-List:

### Major:
- Create a means to easily encode videos before they are uploaded and also checking the codec settings. Refuse to allow the user to upload videos with bad codec settings by greying out the Submit button.
- Add a channel function where you can view the uploads of a certain user. Maybe integrate ZeroMe into Kopykate?

### Minor:
- Only show a small number of videos at a time at any given moment. At the moment, it only does so when search results first come up, but does not continue to do so after 'Show More Videos' is clicked. This can overwhelm the browser with infinitesimal amounts of results!
- Featured videos will only stick if they have been very recently added or commented on. Needs to be able to stick even if they're 100 years old and haven't been commented on. 
- Clean up code and add more class names to CSS files.
- More YouTube-like menu functions and more polishing of overall site layout for both PC and mobile.
