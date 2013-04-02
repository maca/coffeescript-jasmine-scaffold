
JS lib or jQuery plugin project generator with jasmine specs, phantomjs command line spec runner, automatic coffeescript compilation and automatic phantomjs test running.
 
Usage:

    $ bash <(curl -L http://git.io/js-scaffold-0.1) -j my_lib
    $ cd my_lib
    $ guard

The generated Guardfile watches and compiles coffeescript files located in src/ to lib/ and if phantomjs is available runs specs using phantomjs after compilation or after editing specs.

Not passing `-j` option won't download jquery and jasmine-jquery

Dependencies:
Ruby
guard-shell gem
optionally phantomjs
