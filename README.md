# Foursquare Simple Lists
A little helper webapp that allows you to quickly view your foursquare lists and get their permalinks.

Sometimes I'd like to send people a URL to one of my (or my friends'!) Foursquare lists, so they can have a look. As this is currently (as of May 2015) not possible inside the iOS app, and the 4SQ web interface is comparably slow and clumsy, I made this tool.

## Demo

You can preview how this app is going to look on your server, or simply use it as is. No personal data from the API is ever stored on the server, as you can see when you check the code.

[http://foursquarelists.arnorichter.de/](http://foursquarelists.arnorichter.de/)

I'm also referencing the [blog post](http://oelna.de/blog/4105) I wrote about this, in case I do more follow-up there.

## Installation

- go to Foursquare and register the app using the URL you put the `index.html` file:  [foursquare.com/developers/apps](https://foursquare.com/developers/apps)
- note the `Client ID` they give you.
- enter the `Client ID` in the `index.html` file, roughly on line 147.
- open the app in your browser; you should be able to log in now.

## Usage

Once you have looged in, the app shows a list of you and your friends. You can browse your own and your friends lists from here. If needed, you can also view the venues (and get their URLs) that are on a list. On iOS you can copy the URLs of the lists by pressing and holding on one of the links. A menu offerns the option to copy to clipboard. After that, share whichever way you like.

Update: I added the option to render venue links as native URLs that open in the Foursquare app, instead of regular links to the website. If this is what you want, check the option at the bottom of the page. It is saved in localstorage, so it should stick. The only issue is, if venues are visible at the time the option is checked, the links are not re-rendered. Instead, tap the list a second time to refresh.

## Support my work

If you'd like to support what I do, please consider tipping.  
[![Gittip](https://www.dropbox.com/s/23emy7ngeqdnrrc/logo_gittip.png?raw=1)](https://www.gittip.com/oelna/)  [![Flattr](https://www.dropbox.com/s/20legqru72ffddw/logo_flattr.png?raw=1)](https://flattr.com/submit/auto?user_id=oelna&url=https%3A%2F%2Fgithub.com%2Foelna%2Ffoursquare-simple-lists&title=foursquare-simple-lists&language=en&tags=github&category=software)
