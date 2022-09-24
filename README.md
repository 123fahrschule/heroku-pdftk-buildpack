THIS IS NOT AN OFFICIAL HEROKU PRODUCT!

# What is it

Custom buildpack that will install pdftk-java into /app/bin on Heroku. Supports **heroku-18**, **heroku-20**, **heroku-22**.


# How to use

1. Add this buildpack to your app. 
2. Use /app/bin/pdftk. The folder /app/bin is added to the path, so you should be able to just call pdftk.

# Changelog
[2022-09-24]
- Switch from pdftk 2.02 to the maintained fork pdftk-java version 3.3.3

# How to upgrade PDFTK

Change the $tarball_url variable in bin/compile to the binary you want to download
