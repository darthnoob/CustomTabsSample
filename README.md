# CustomTabsSample
Chrome Custom Tabs sample for Android

##Set up

Use sparse-checkout submodule for gradle build.

```
$ git clone git@github.com:sakebook/CustomTabsSample.git
$ cd CustomTabsSample/
$ git submodule init
$ git submodule update
$ cd custom-tabs-client/
$ git config core.sparsecheckout true
$ echo -e shared/\\ncustomtabs/ > ../.git/modules/custom-tabs-client/info/sparse-checkout
$ git checkout master
$ cd ..
$ git read-tree -mu master
```

## Demo App
https://play.google.com/store/apps/details?id=com.sakebook.android.sample.customtabssample

## Slide
https://speakerdeck.com/sakebook/make-full-use-of-chrome-custom-tabs

