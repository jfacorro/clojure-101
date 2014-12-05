Clojure 101
===========

This is the presentation done at Inaka as part of its friday's talks.
The presentation was built as a [Gorilla REPL][gorilla] worksheet.

## Usage

You can load the worsheet in the online viewer using the following link:
[Clojure 101][online].

To be able to edit the worksheet you need to run it locally. First install
leiningen (see the instructions below) and then run `lein gorilla`.


## Installing Leiningen

### OS X / Linux

Run the following from the command line:

    curl https://raw.githubusercontent.com/technomancy/leiningen/stable/bin/lein > lein
    chmod +x lein
    mv lein /usr/local/bin
    lein upgrade

### Windows

Download [this script][lein-bat], put it in your path and your done.

  [gorilla]: http://gorilla-repl.org/index.html
  [online]: http://viewer.gorilla-repl.org/view.html?source=github&user=jfacorro&repo=clojure-101&path=clojure_101
  [lein-bat]: https://raw.githubusercontent.com/technomancy/leiningen/stable/bin/lein.bat
