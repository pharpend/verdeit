# verdeit

This is a distributed content sharing system, inspired by
[Reddit][1]. Verdeit inspires to have better performance and a better
design than Reddit.

Verdeit is written in the [Haskell programming language][1], and
licensed under the [GNU AGPL][2].

## Installation and Usage

1.  Install [Haskell][2], [Stack][4] and [Git][3].
2.  Run these commands in a terminal:

        git clone git://github.com/pharpend/verdeit.git
        cd verdeit
        stack setup
        stack build
        stack exec -- yesod devel

Navigate to <http://localhost:3000> in your browser, and you should see
the development version of Azulit.

## Contributing

Contributions are welcome and needed! I am terrible at visual design, so
designers are definitely needed.

[1]: https://en.wikipedia.org/wiki/Rss
[2]: https://github.com/bitemyapp/learnhaskell/blob/master/install.md
[3]: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
[4]: https://github.com/commercialhaskell/stack/wiki/Downloads
