# tableflisp

Because desperate times call for desperate functions!

## Usage

```clojure
;; Friends don't let friends use the IBM JDK
(when (re-find #"IBM" (System/getProperty "java.vm.name"))
  (<╯°□°>╯︵┻━┻))

;; One processor? What decade is this?!
(when (= 1 (.availableProcessors (Runtime/getRuntime)))
  (<╯°□°>╯︵┻━┻))
```

## License

Copyright © 2013 FIXME

Distributed under the Eclipse Public License, the same as Clojure.
