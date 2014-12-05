Clojure 101
===========

This is the presentation done at Inaka as part of its friday's talks.
The presentation was built as a [Gorilla REPL][gorilla] worksheet.

## Usage

You can load the worsheet in the online viewer using the following link:
[Clojure 101][online].

To be able to edit the worksheet you need to run it locally. First install
[leiningen][lein] (see the instructions below) and then run `lein gorilla`. This will
print some messages to the console and then show a local url where a Gorilla
REPL will be running.

    Gorilla-REPL: 0.3.3
    Started nREPL server on port 54618
    Running at http://localhost:54620/worksheet.html .
    Ctrl+C to exit.

Open that url in your browser, press <kbd>CTRL</kbd>+<kbd>G</kbd>
<kbd>CTRL</kbd>+<kbd>L</kbd> and select the file `clojure_101.clj`.

## Installing Leiningen

### OS X / Linux

Run the following from the command line:

    curl https://raw.githubusercontent.com/technomancy/leiningen/stable/bin/lein > lein
    chmod +x lein
    mv lein /usr/local/bin
    lein upgrade

### Windows

Download [this script][lein-bat], put it in your path and your done.

### Interesting Projects & Resources

- [NightMod](https://nightmod.net/) - IDE for Games
- [4Clojure](http://www.4clojure.com/) - Solve little Clojure problems. Really useful for learning.
- [TryClojure](http://www.tryclj.com/) - Run Clojure code online.


  [gorilla]: http://gorilla-repl.org/index.html
  [online]: http://viewer.gorilla-repl.org/view.html?source=github&user=jfacorro&repo=clojure-101&path=clojure_101.clj
  [lein-bat]: https://raw.githubusercontent.com/technomancy/leiningen/stable/bin/lein.bat
  [lein]: https://github.com/technomancy/leiningen/
