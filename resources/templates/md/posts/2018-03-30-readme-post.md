{:title  "Readme First Post!"
 :layout :post
 :date   "2016-01-01"
 :tags   ["tag1" "tag3"]}

# fin-calc-pw
This repo is a work-in-progress to consolidate learning ClojureScript and to showcase techniques learned.

`shadow-cljs` is a build tool for ClojureScript.

`proto-repl` is a Clojure(Script) dev env for [Atom](https://atom.io/)

`re-frame` is a is a pattern for writing SPAs in ClojureScript, using Reagent. [Reagent](https://github.com/reagent-project/reagent).

## Setup And Run
#### Copy repository
```shell
git clone https://github.com/jacekschae/shadow-re-frame.git && cd shadow-re-frame
```

#### Install dependencies
```shell
yarn install || npm install
```

#### Run dev server
```shell
yarn dev || npm run dev
```

#### Compile an optimized version

```shell
yarn release || npm run release
```
Based on https://github.com/jacekschae/learn-re-frame-course-files
and https://github.com/rahulpilani/mort-calc

#### TBD to deploy google hosting.
