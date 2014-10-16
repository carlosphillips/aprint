# aprint: awesome print

![screenshot](https://raw.github.com/razum2um/repl-color/master/doc/screenshot.png)

## Usage

[![Clojars Project](http://clojars.org/aprint/latest-version.svg)](http://clojars.org/aprint)

    (use 'aprint.core)
    (aprint object)

    ;; or just like (pp)
    (ap)

## Why not just clojure.pprint/pprint?

Look, I have some data:

![data](https://raw.github.com/razum2um/repl-color/master/doc/raw.png)

With `pprint` it takes 3+ awful screens:

![pprint1](https://raw.github.com/razum2um/repl-color/master/doc/pprint1.png)

![pprint2](https://raw.github.com/razum2um/repl-color/master/doc/pprint2.png)

![pprint3](https://raw.github.com/razum2um/repl-color/master/doc/pprint3.png)

![pprint4](https://raw.github.com/razum2um/repl-color/master/doc/pprint4.png)

With `aprint`:

![aprint](https://raw.github.com/razum2um/repl-color/master/doc/aprint.png)

Awesome, yeah?

## Notes

If you'd like to get same layout without color codes:

    ;; n stands for "normalized" print
    (nprint issues)

## Hint

Add this to your `~/.lein/profiles.clj`

    {:user {:injections [(use 'aprint.core)]}}

## Acknoledgements

- @hlship for awesome [jline2](https://github.com/jline/jline2)
- @jdillon for thinking in similar way: [pretty](https://github.com/AvisoNovate/pretty)

## License

Copyright © 2014 Vlad Bokov

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
