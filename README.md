# deps-cljr-test1
ClojureCLR project for testing cljr git coordinates

This project is used for the test suite for the Deps.Cljr project.
It can be referred to directly, if desired.
It is used from the deps-cljr-test1 project to test chaining of references in deps.edn.

## Releases

Latest release: 1.0.0

[CLI/deps.edn](https://clojure.org/reference/deps_and_cli) dependency information:

```
io.github.dmiller/deps-cljr-test1 {:git/tag "v1.0.0" :git/sha "1234567"}
```

## Example usage

```
(require '[dct1.test :as t1])

(t1/g 12)
```
