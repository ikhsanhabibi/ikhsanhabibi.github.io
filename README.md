# How to run?
- Install Ruby version 2.6, gem version 3.0.3
- bundler install
- gem install eventmachine --platform ruby
- bundle exec jekyll serve -w OR bundle exec jekyll serve --watch

# Problem :

-  eventmachine : https://github.com/eventmachine/eventmachine/issues/806
$ gem uninstall eventmachine

Select gem to uninstall:
 1. eventmachine-1.2.5
 2. eventmachine-1.2.5-x64-mingw32
 3. All versions
> 3
Successfully uninstalled eventmachine-1.2.5

You have requested to uninstall the gem:
        eventmachine-1.2.5-x64-mingw32

em-websocket-0.5.1 depends on eventmachine (>= 0.12.9)
If you remove this gem, these dependencies will not be met.
Continue with Uninstall? [yN]  y
Successfully uninstalled eventmachine-1.2.5-x64-mingw32
