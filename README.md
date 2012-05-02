# PyroCMS Bands In Town Widget

* Author: Michael Giuliana
* Twitter: [@rpnzldesign](http://www.twitter.com/rpnzl)
* Website: [http://rpnzl.com/](http://rpnzl.com/)
* Version: 1.1

## Important

Please review the Bands In Town API v2.0 [Overview](http://www.bandsintown.com/api/overview) and [Best Practices](http://www.bandsintown.com/api/best_practices) before utilizing this widget. **You must choose a custom, descriptive App ID as per Bands In Town's guidelines.**

## Description

This PyroCMS widget interacts with Bands In Town's API v2.0 and will display customized event information *for a single artist* as a table on your site. The current API does not allow for more general search criteria. This widget will be updated if BIT expands their API's capabilities.

This widget now caches API calls for ten minutes with the help of PyroCache.

## Installation

Rename the **pyrocms-widget-bit** folder -> **bandsintown** and drop it into your addons/shared_addons/widgets directory.

## Configuration

Head over to the Admin Widgets module and drag the Bands In Town widget over to a widget area.

**App ID** - You must choose a custom, descriptive App ID.
**Limit** - The max number of events to display.
**MBID** or **Artist Name** - One of these is required to make an API call since we're limited by the API to displaying a single artist's data.
**Artist FB Page ID** - Optional, to be used in combination with the artist's name or MBID.
**Display Options** - Alter columns in the table that will be displayed by the widget.