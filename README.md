# tableflisp

Because desperate times call for desperate functions!

## Quick start

Require tableflisp in your namespace header:

(ns example.core
  (:use [tableflisp.core]))

## Usage

```clojure
;; Friends don't let friends use the IBM JDK
(when (re-find #"IBM" (System/getProperty "java.vm.name"))
  (<╯°□°>╯︵┻━┻))

;; One processor? What decade is this?!
(when (= 1 (.availableProcessors (Runtime/getRuntime)))
  (<╯°□°>╯︵┻━┻))

;; FFFFFFFUUUUUUUUUUUU...
(try
  (apply str (repeat 7 "F") (repeat "U"))
  (catch OutOfMemoryError e
    (<╯°□°>╯︵┻━┻)))
```

## License

Copyright © 2013 FIXME

Distributed under the Eclipse Public License, the same as Clojure.
