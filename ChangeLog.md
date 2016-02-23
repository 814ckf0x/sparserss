# 1.7
**2012-10-21**

* added Swedish translation by Lars m
* added support for feeds that only provide enclosures
* fixed gzip support
* added display of author of the articles
* fixed non-asynchronous load of text and images (thanks to Robert Freund for intensive testing)

# 1.6.2
**2012-07-22**

* fixed read status after refresh with disabled efficient feed parsing
* added support for SOCKS proxy
* fixed flickering on entry view on ICS devices (thanks to Daniel Berg for extensive testing)

# 1.6.1
**2012-07-09**

* fixed FC that has been raised when selecting certain refresh interval values in Japanese language

# 1.6
**2012-07-09**

* increased responsiveness on refresh on startup
* added proper handling for user set date and time format
* added option for twice-daily refreshes (Joel Low)
* implemented a progress indicator in the main tab activity that is shown when a refresh is in progress (Joel Low)

# 1.5.2
**2012-04-25**

* correctly stores " (quot)
* added option to reset the feed update-date
* added correct handling of apostrophes
* added proper support for decimal encoded html entities
* fixed baseurl support for feed entries
* improved automated feed url recognition of baseurl feeds in subfolders

# 1.5.1
**2012-04-10**

* fixed stackoverflow on initial start on ICS devices

# 1.5
**2012-04-10**

* added color chooser for widget background
* added guid support
* added option to disable efficient feed parsing to support unordered feeds
* improved feed sorting
* fixed local picture storage
* minor bugfixes (database instantiation speed, rare FCs, ui tweaks)

# 1.4.2_2
**2012-04-04**

* fixed FC on HC/ICS after first start

# 1.4.2
**2012-04-03**

* re-established Android 1.5 compatibility
* added proper support for Android 3 and 4
* fixed support for 'Z'-timezones
* reduced memory consumption for local picture storage

# 1.4.1
**2012-03-03**

* updated widget (delete and re-add on problems)
* updated widget config to allow setting of maximal number of shown entries
* added option to disable gestures
* added option disable download warning for enclosures
* updated Russian translations by Igor Nedoboy
* updated French and Turkish translation by <unnamed>
* updated German and Japanese translation
* improved speed and memory usage while refreshing feeds
* fixed double insertion bug if URL has been autocompleted
* entry background fixes

# 1.4
**2012-02-26**

* entry UI enhancements
* improved automated visual rescaling of pictures
* added experimental podcast (enclosure) support

# 1.3.4
**2012-02-21**

* plenty of entry view UI enhancements
* updated Russian translation by Igor Nedoboy
* fixed refresh bug for wifionly feeds with overridden manual triggers (patch by Pavel Denisov)

# 1.3.3_3
**2012-02-12**

* added workaround for android issue 6191

# 1.3.3_2
**2012-02-12**

* fixed nullpointer exception on certain icons

# 1.3.3
**2012-02-11**

* fixed inconsistent feed icon sizes
* fixed chronological order of feed entries without a specified date
* added Russian translation (thanks to Igor Nedoboy)
* added gesture detection to switch entries with animation

# 1.3.2
**2012-01-08**

* improved support for devices w/o dpad
* added option to delete all entries (not the feeds themselves)
* French and Turkish translation update

# 1.3.1
**2011-12-12**

* added support for devices w/o dpad
* added option to override wifi-only setting on single manual refreshs
* fixed feed parsing if summary and description is present

# 1.3
**2011-11-01**

* improved support for podcast feeds
* stabilized light theme choice
* added option to delete read items
* stabilized feed title view
* added support for link-less rss entries
* improved responsiveness on feed refresh
* changed implementation to a proper threaded implementation (after a suggestion by Peter V. Pretsch)
* added option to copy url from menu
* added option to delete currently viewed entry (feature requested by Roberto Hunger)
* added support for protocol changing redirects (has to be enabled by user)
* added changelog link
* added hint for http <-> https redirect if not enabled
