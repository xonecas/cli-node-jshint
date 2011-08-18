# Simple command line interface for JSHINT

If you need more than this, you should take a look at @brentlintner
implemenation: [node-jshint](https://github.com/jshint/node-jshint).
This is a very simple solution. It depends on [jshint](https://github.com/jshint/jshint) 
(do'h!) and, wait for it, [node.js](http://nodejs.org/).

## Instalation

You are going to need jshint, then just drop cli-jshint into that, or run these
two commands:

    git clone https://github.com/jshint/jshint.git
    git clone ...

## Usage

Same as would expect, please head on to [jshint's webby](http://jshint.com/#docs)
 for the full docs. But this will get you started:

    cd jshint
    ./cli-jshint path/to/js/file option:value option:value

## Example
   
With the options set in file:

    ./cli-jshint ./cli-jshint

With options

   ./cli-jshint ./cli-jshint curly:true debug:true node:true

### License?

Please contribute, mangle, cuddle, ... at will.
