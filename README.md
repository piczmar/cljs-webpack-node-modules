Following the tutorial of ClojureScript with Webpack at [https://clojurescript.org/guides/webpack](https://clojurescript.org/guides/webpack)

# Quick start

You need to setup ClojureScript dev environment before. Check [here](https://clojurescript.org/guides/quick-start)

## Build

```bash
yarn webpack
clj -m cljs.main -co build.edn -v -c
```

## Run

```bash
clj -m cljs.main -s
```
