# Songlink
Songlink is the best way to share music (we think). But, with your help, we can make it even better. 🙏🏼

* [How to use Songlink](#how-to-use-songlink)
* [Contributing](#contributing)
* [Songlink as a service](#songlink-as-a-service)
  * [Full Songlink URLs](#full-songlink-urls)
  * [ID-only Songlink URLs](#id-only-songlink-urls)
* [Contributing (Alternate Take)](#contributing-alternate-take)

## How to use Songlink
Sharing Songlinks is powerful. When someone clicks on a Songlink, it is quick and easy for them to start listening to the song in the app they love:

![Songlink listen flow gif](https://s3-us-west-1.amazonaws.com/songlinkio/songlink_listen.gif)

It is easy to create and share Songlinks. Just head to our website:

![Songlink webapp flow gif](https://s3-us-west-1.amazonaws.com/songlinkio/songlink_webapp.gif)

Or, you can use a little copy and paste wizardry:

![Song spotify copy manual gif](https://s3-us-west-1.amazonaws.com/songlinkio/songlink_spotify_copy_manual.gif)

If you use Facebook Messenger, you can talk to [Songlink Bot](https://www.messenger.com/t/songlinkbot/), and he (she? it?) will find you the Songlink to share.

If you use the iOS app Workflow, there's some dope workflows like [this one](https://workflow.is/workflows/561b08115edf48d1b205dbf422ca426c).

For more info about all the ways to create Songlink URLs, see the [Songlink as a service](#songlink-as-a-service) section below

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
