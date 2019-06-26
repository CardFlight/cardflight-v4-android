# cardflight-v4-android
CardFlight SDK Version 4 for Android

# How to Install

1. Add the `.aar` files to your `/libs` folder.

2. Add a maven repository for `flatDirs`.
```
repositories {
    flatDir { 'libs' }
}
```

3. Add the dependencies.
```
implementation(name: 'core-1.0.11', ext: 'aar')
implementation(name: 'byod-4.8.10', ext: 'aar')
```

4. Sync your project with Gradle files


# Documentation

Full documentation can be found [here](docs/index.md).
