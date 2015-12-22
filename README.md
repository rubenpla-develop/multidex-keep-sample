# multidex-sample

Sample app to demonstrate multidex

## Test `multiDexKeepFile file('multidex.keep')`

```bash
./gradlew clean assembleDebug
```

Check files:

* app/build/intermediates/multi-dex/debug/manifest_keep.txt
* app/build/intermediates/multi-dex/debug/maindexlist.txt

Result:

* 0.14.2 ok
* 0.14.4 ok
* 1.2.3 ok
* 1.3.0 fail
* 1.3.1 fail
* 1.4.0-beta1 cannot build
* 1.4.0-beta2 cannot build
* 1.4.0-beta3 cannot build
* 1.4.0-beta4 cannot build
* 1.4.0-beta5 cannot build
* 1.4.0-beta6 cannot build
* 1.5.0 fail
* 2.0.0-beta1 fail
* 2.0.0-beta3 fail
