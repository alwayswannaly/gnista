# Gnista

Gnista is a wrapper for the database/hashstore [Sparkey](http://github.com/spotify/sparkey) written for Ruby. Gnista packs all the native features of Sparkey into a shiny red package, easy to use.

This is a fork of the [original](https://github.com/emnl/gnista/) gnista gem.
This fork makes the setup process for gnista simpler on linux fedora/redhat systems and on macOSX m1 systems

## Contributing

__Step-by-step:__

1. Fork it  
    1. Fetch submodules (`git submodule update`)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Write some code
4. Build and test
5. Commit your changes (`git commit -am 'Add some feature'`)
6. Push to the branch (`git push origin my-new-feature`)
7. Create new Pull Request
Use the following commands to build the native extensions and test:
	$ rake make
	$ rake test
