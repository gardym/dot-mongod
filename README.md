# dot-mongod

Supporting your local mongod scene.

Because managing local data is the last thing you care about `dot-mongod` runs mongo on a unique port and dumps all the files it needs under your current working directory. Use it with it's complementary `dot-mongo` client and never worry about --dbpath again.

## Installation

1. Put the files somewhere in your $PATH

## Running

    # Start a local server
    $ dot-mongod start
    Starting dot-mongo on port: 27017

    # Connect to the local server
    $ dot-mongo

    # Stop the local server
    $ dot-mongod stop

