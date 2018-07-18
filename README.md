# dstr

Developer machine dust remover. OK we leave some but remove plenty of your old rubbish.

* **strip** leaves most current version of cache files (ie. Maven repo, Gradle cache) untouched but removes any older version. Leaves all configuraiton files untouched.
* **clean** leaves configuration files untouched but removes all restorable cache files such as Maven repo or Node cache.
* **purge** removes a toolchains traces completely for instance will also delete the `~/.m2` directory for Maven users.
