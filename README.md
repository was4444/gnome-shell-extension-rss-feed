# RSS Feed GNOME Shell extension

*This is a fork from https://github.com/todevelopers/gnome-shell-extension-rss-feed. I have taken over maintainership of this project for extensions.gnome.org.*

Simple RSS Feed reader extension for GNOME Shell.

This extension adds button (RSS icon) to the GNOME Shell panel. After click on it, you can see your RSS Feeds in popup menu and navigate through them. When you click on some article, extension opens your default browser with it. Bottom bar contains buttons for navigating, refreshing and Settings tab.

You can add URL links of your RSS sources in Settings tab. Also you can adjust refreshing interval in minutes or set how many RSS Feeds will be displayed per page.

#### Supported formats:

* RSS 1.0 (RDF) format
* RSS 2.0 format
* Atom format

## Future plans

* Support for different content encoding then UTF-8
* Verification of RSS source availability in Settings widget
* Rework of Settings widget
* Notifications for new articles
* Mark articles read / unread
* Categories for RSS Feeds

## Installation

### Through extensions.gnome.org

Go to https://extensions.gnome.org/extension/948/rss-feed/ and install it from there.

### Manual installation

Download latest release (https://github.com/maweki/gnome-shell-extension-rss-feed/archive/master.zip) and unpack the `rss-feed@gnome-shell-extension.todevelopers.github.com` folder into to this directory `~/.local/share/gnome-shell/extensions/`. Restart the gnome shell by `ALT+F2`, type `r` and hit `Enter`.

## Screenshots

![](http://i.imgur.com/EzCf7ih.png)
![](http://i.imgur.com/YohFb6F.png)
