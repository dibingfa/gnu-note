https://github.com/coreutils/coreutils/commit/da7a704cd36e1d2015d14247e5139fb1999b2211

```
git ls-files | grep '\.[ch]$' \
    | xargs perl -pi -e 's/for \(;;\)/while (true)/g'
```
