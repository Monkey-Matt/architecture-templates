Fork of [Android Architecture Starter Templates](https://github.com/android/architecture-templates) that doesn't require bash 4 (can be setup on default mac environment)

Architecture starter template (multimodule)
==================

This template is compatible with the latest **stable** version of Android Studio.

![Screenshot](https://github.com/Monkey-Matt/architecture-templates/raw/main/screenshots.png)

## Features

* Room Database
* Hilt
* ViewModel, read+write
* UI in Compose, list + write (Material3)
* Navigation
* Repository and data source
* Kotlin Coroutines and Flow
* Unit tests
* UI tests using fake data with Hilt

## Usage

1. Clone the repository, optionally choosing a branch. For example, to check out the `base` branch:

```
git clone https://github.com/Monkey-Matt/architecture-templates.git --branch multimodule
```

2. Set customizer script to executable:

```
cd Documents/GitHub/architecture-templates
sudo chmod 755 'customizer.sh'
```

3. Run the customizer script:

```
./customizer.sh your.package.name YourAppName
```

* `your.package.name` is your app ID (should be lowercase)
* `YourAppName` is a name for your application (should be in PascalCase).

# License

This code is distributed under the terms of the Apache License (Version 2.0). See the
[license](LICENSE) for more information.
