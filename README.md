# Checklist for when putting a Wordpress site live
+ A list of stuff to do when setting a WordPress site live.
+ Avoid putting a site live on a Friday.

## Before going live
+ Check all links, main navigation, sub navigation and mobile navigation.
+ Make a backup of all files. It is always good to have all the files backed up somewhere in the same condition as when the site goes live.
+ Delete unnecessary users and set correct users role. Avoid unnecessary admin accounts.
+ Check if favicon is there and apple-touch-icons as well and displaying correctly.

### SEO
+ Install a SEO Plugin. [WordPress SEO](https://wordpress.org/plugins/wordpress-seo/)
+ Check if `title` tag is displaying friendly titles.


## After going live
+ Check all links, again.
+ Check if system administrator will be doing a scheduled backup of files and database. If not set up a a backup plan. [Updraft Plus](https://wordpress.org/plugins/updraftplus/) is quite a quite good free plugin.

### Security
+ Disallow Dashboard editor for security reasons `define( 'DISALLOW_FILE_EDIT', true )`
+ Install a security plugin. [Wordfence](https://wordpress.org/plugins/wordfence/) is a quite good free plugin.
