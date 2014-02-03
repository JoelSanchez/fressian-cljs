fressian-cljs
=============

Read and write fressian data by clojurescript.

## Installation

Add the following to your `project.clj`

```clojure
[net.unit8/fressian-cljs "0.1.0"]
```

## Usage

```clojure
(ns myapp
  (:require [fressian-cljs.core :as fress])

(fress/write {:a 1 :b 2})

```

