player-ladder-om
=================
[![Build Status](https://travis-ci.org/minimal/player-ladder.svg?branch=master)](https://travis-ci.org/minimal/player-ladder)
[![Dependencies Status](http://jarkeeper.com/minimal/player-ladder/status.svg)](http://jarkeeper.com/minimal/player-ladder)

A player ladder for any 1v1 game (e.g. table tennis).

Originally forked from [React Tutorial Om](https://github.com/jalehman/react-tutorial-om)

Frontend written in [Om](https://github.com/swannodette/om).

## Installation

Clone this repo

    git clone git@github.com:minimal/react-tutorial-om.git

Clone submodule

    git submodule update --init

Install submodules

    cd checkouts/ranking-algorithms
    lein install

    cd ../ring-middleware-format
    lein install

    cd ../..

Compile with figwheel with auto browser refresh:

    lein figwheel


Or with cljsbuild Compile js

    lein cljsbuild once dev
    # or for development
    lein cljsbuild auto dev


Run server
    lein repl
    (go)

Point Browser to

    http://localhost:3000
