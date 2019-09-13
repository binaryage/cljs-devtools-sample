# cljs-devtools-sample [![GitHub license](https://img.shields.io/github/license/binaryage/cljs-devtools-sample.svg)](license.txt)

## This repo was moved to [binaryage/cljs-devtools/examples/lein](https://github.com/binaryage/cljs-devtools/tree/master/examples/lein)

---

This project is an example of integration of [**cljs-devtools**](https://github.com/binaryage/cljs-devtools) into a
Leiningen-based ClojureScript project.

![](https://box.binaryage.com/cljs-devtools-sample-full.png)

## Local setup

    git clone https://github.com/binaryage/cljs-devtools-sample.git
    cd cljs-devtools-sample

Build the project and start local demo server:

    lein demo

  * A demo page should be available at [http://localhost:7000](http://localhost:7000).
  * Please visit it with Google Chrome browser with [enabled custom formatters](https://github.com/binaryage/cljs-devtools).
  * Open the web development console under devtools and you should see something similar to the screenshot above.
    Note: you might need to refresh the page again to force re-rendering of custom formatters after opening the console.
