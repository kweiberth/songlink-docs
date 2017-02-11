# Songlink
Songlink is the best way to share music. Let’s keep making it better. 🤘 This doc will (hopefully 🙏🏼) answer your questions.

* [How to use Songlink](#how-to-use-songlink)
* [Contributing](#contributing)
* [Songlink as a service](#songlink-as-a-service)
  * [Full Songlink URLs](#full-songlink-urls)
  * [ID-only Songlink URLs](#id-only-songlink-urls)
* [Contributing (Alternate Take)](#contributing-alternate-take)

## How to use Songlink
Great question. Here’s a few ways:

* facebook messenger (shown on ios)
* facebook messenger (share from spotify)
* web app, share 
* copy and paste (spotify, apple, youtube, google iOS/desktop)
* Workflow from @ndaught
* saving to home screen on safari?

## Contributing
We want to make it as easy as possible for users to create and share Songlink URLs. Thus, we need to integrate with the tools and apps they use to listen to music and communicate with friends. We’re thinking apps and websites, messaging bots, universal share flows on iOS and Android, etc. We can’t build all of this cool shit ourselves (though we **are** working on some of them!), so we’d like to engage the community and enable all yinz to make Songlink workflows that help you (and maybe even others!) share music. 

The next section describes how (easy it is) to create Songlink URLs. Please reach out to kurt@songlink.io with any questions or comments, or to show off a new integration you’ve built. I’ll make a gif of any cool shit you build and highlight it in the [How to use Songlink](#how-to-use-songlink) section above. 

## Songlink as a service
At its core, Songlink is a service that renders Songlink URLs. There are 2 types of Songlink URLs, each of which are easy to compose:

1. **Full Songlink URLs**
2. **ID-only Songlink URLs**

### Full Songlink URLs

These are the easiest to create. A full Songlink URL is composed by appending the song’s share URL to the root Songlink domain. For example: 

https://songlink.io/https://itun.es/us/5Gb0-?i=1053825088

Songlink currently supports Spotify, Apple Music, YouTube and Google Play Music urls:

#### Spotify

https://songlink.io/https://open.spotify.com/track/2ALFO1JJBhMo7cNNsKlfHd
https://songlink.io/spotify:track:2ALFO1JJBhMo7cNNsKlfHd

#### Apple Music

https://songlink.io/https://itun.es/us/5Gb0-?i=1053825088

#### YouTube

https://songlink.io/https://www.youtube.com/watch?v=mUYf2yu78Ts
https://songlink.io/https://youtu.be/mUYf2yu78Ts

#### Google Play Music

https://songlink.io/https://play.google.com/music/m/Tup7olbv5amthc2jhaz6vubsrj4

### ID-only Songlink URLs

These are shorter, prettier, cooler Songlink URLs 😎. If you can grab the ID of the song, the rest is 🍰. We support Spotify, Apple Music, YouTube and Google Play Music IDs.

#### Spotify

`https://songlink.io/ + s/ + Spotify ID`

https://songlink.io/s/2ALFO1JJBhMo7cNNsKlfHd

#### Apple Music

`https://songlink.io/ + i/ + Apple Music ID`

https://songlink.io/i/1053825088

#### YouTube

`https://songlink.io/ + y/ + YouTube ID`

https://songlink.io/y/mUYf2yu78Ts

#### Google Play Music

`https://songlink.io/ + g/ + Google Play Music ID`

https://songlink.io/g/Tup7olbv5amthc2jhaz6vubsrj4

## Contributing (Alternate Take)
Songlink has no funding or revenue stream (we think banner ads are bullshit 🤑). We are committed to maintaining (and, of course, constantly improving) the Songlink platform. Unfortunately, servers aren’t free, my Philz coffee addiction is real and we drink a lot of IPAs. If you’d like to help fund our servers, ☕ or 🍺 you can send us a gift via [Venmo](venmo.com/songlink) or [PayPal](paypal.me/songlink).

✌️❤️
