script.watchlist
================

Script to provide watchlist functionality in Kodi library view

INFORMATION FOR SKINNERS
========================

Include the following in your addon.xml

<import addon="script.watchlist" version="0.0.1"/>

Use with

<onclick>ActivateWindow(Videos,plugin://script.watchlist?type=[type],return)</onclick>

Where type is one of the following:
-   movies
-   episodes


CREDITS
=======
This script was created by Unfledged. Script is based upon service.library.data.provider, itself based upon service.skin.widgets
