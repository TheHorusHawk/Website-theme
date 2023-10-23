### Pelican theme for my Website

A modified version of the pelican theme [notmyidea](https://github.com/getpelican/pelican/tree/master/pelican/themes/notmyidea).


It's very much geared for my personal needs. For example of use, see my website theHorusHawk.github.io/creative

Main changes: 
- Commented out author and date-modified from article_infos 
- Added support for comments with utterances
- Added some padding around article_infos
- Added custom page for about me, without comments
- changed the title for pages, to include a smaller sitename before the page title (articles remain the same)


Should you wish to use it, know it expects these variables on your config file (view usecase in https://github.com/TheHorusHawk/creative)
> - Expects SITENAMESMALL variable to be set in config file.
> - To use UTTERANCES, set UTTERANCES to True on your config file. As well as REPO variable to be set to your repo name
