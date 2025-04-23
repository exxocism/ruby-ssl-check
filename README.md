> [!WARNING]
> This repo is deprecated because `bundle doctor --ssl` now provides information
> to troubleshoot SSL issues. It will still be maintained until all supported
> rubies ship with a version of Bundler providing `bundle doctor --ssl`, because
> many times SSL issues prevent users from upgrading Bundler.

# ruby-ssl-check

This script tries to help you diagnose SSL problems, especially related to certificates or TLS version while connecting to https://rubygems.org.

It can be run by the following:
```
curl -Lks 'https://git.io/rg-ssl' | ruby
```
