# 1.0.0-alpha2 (1/4/2018)

* Switches RxJava to 2.x
* Currently only supports Rx2 Observable type
* Adds `rxgroups-processor` to generate resubscription tag without runtime reflection

# 0.3.5 (07/13/2016)

* Fix: Correctly catch `NoClassDefFoundError` in `LifecycleResubscription`

# 0.3.4 (07/11/2016)

* Fix: Prevent crash when Activity is recreated after it's finished and is changing configurations.

# 0.3.3 (06/30/2016)

* Fix: Catch exceptions from reflective call in `LifecycleResubscription#fields()`

# 0.3.2 (06/23/2016)

* Fix: PR #18: GroupLifecycleManager crash when app is backgrounded

# 0.3.1 (06/09/2016)

* Fix: PR #15 - Look for `resubscriptionTag()` method in superclasses

# 0.3.0 (06/09/2016)

* New: `rxgroups-android` module including `AutoResubscribe` and `GroupLifecycleManager`

# 0.2.2 (01/25/2016)

* Adds `ObservableGroup.subscription()`

# 0.2.1 (01/25/2016)

* Makes `ObservableGroup.isDestroyed()` public

# 0.2.0 (01/20/2016)

* Initial release
