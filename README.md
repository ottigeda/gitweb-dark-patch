# README

A modified gitweb.css with dak theme and Support for displaying README.md and LICENSE files.

On Debian based Systems you need to install the Package *Markdown*

<code>apt-get install markdown</code>

to apply the theme copy the files to */usr/share/gitweb/gitweb.cgi* and */usr/share/gitweb/static/gitweb.css*

Do not forget to configure your <code>/etc/gitweb.conf</code> to support css and javascript

*this theme is hardforked from* [https://github.com/kogakure/gitweb-theme](https://github.com/kogakure/gitweb-theme)

**NOTE: README.md needs to be XML compatible otherwise Gitweb will fail to display correctly**
