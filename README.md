# mobile-frameworks-comparison-data
JSON for the Mobile Frameworks Comparison Chart

## Participate

Would you like to add your framework to the comparison chart? Do you want to contribute to the data that is already gathered?

No Problem! All you have to do is create a pull request and let me know what you would like to change.

Below you find the documentation for the JSON file.

## Meta

```json
"framework": Name of the framework
"url": Website of your framework
"framework_current_version": What is the frameworks current version?
"comparison_data_last_update": When did you last update this JSON file?
"tutorial_url": You can link to a tutorial here
"license": What license applies to your framework? Please use identifiers from https://tldrlegal.com/ because I love their efforts. (e.g. for MIT: https://tldrlegal.com/license/mit-license => "mit-license")
"video_url": You can link to an introduction video here
"book": Enter ISBN code here
"documentation_url": Where can the docs be found?
```

## Platform

### Available platforms to support. If you need more, let me know.

```json
"android"
"bada"
"blackberry"
"ios"
"maemo"
"meego"
"symbian"
"webos"
"windowsmobile"
"windowsphone"
```

## Target

### What type of app would you like to create with the framework?

```json
"mobilewebsite": A mobile Website is technically the same as a regular website except that it's size is adjusted to the smaller screen. It has a responsive layout.
"webapp": A WebApp is like a regular mobile website but it behaves and is used like a native app. The user interface looks like a native app but technologies used are those of the web.
"nativeapp": A native app is created for a specific platform and uses the required technologies such as an specific SDK or development language.
"hybridapp": A HybridApp is a WebApp that is compiled into a native app. Additional native features can be added to the WebApp which is then distributed as a native app.
```

## Language

### What programming languages does your framework support?

```json
"actionscript"
"cplusplus"
"csharp"
"css"
"html"
"java"
"js"
"lua"
"php"
"python"
"ruby"
"xml"
```

### Hardware Features

```json
"accelerometer": Provides access to the device's motion sensor.
"camera": Provides access to the devices's camera and photo library.
"capture": Provides access to the device's audio, image and video capture capabilities.
"compass": Provides access to the device's direction.
"connection": Provides access to the device's cellular and wifi connection information.
"contacts": Provides access to the device's contacts database.
"device": Provides access to device specific information such as the name, plattform or version.
"nativeevents": Provides access to the device's native events like a back or volume button.
"file": Provides access to the device's file system (crud).
"geolocation": Provides access to the device's GPS data or aided location specific information.
"notification": Provides access to the device's visual or audible device notifications.
"storage": Provides access to the device's storage capabilites/database.
"gestures_multitouch": The framework provides callbacks for gestures and multitouch events.
"messages_telephone": Provides additional access to the device's message and telephone capabilites such as triggering a call or sending a message.
"bluetooth": Provides access to the device's bluetooth network.
"nfc": Provides access to the device's near field communication capabilities
"vibration": Provides access to the device's vibration feature.
```

### User Interface

```json
"cd": The framework allows for adjustment of the GUI to fit corporate design requirements.
"widgets": The framework provides ready-to-use mobile GUI widgets such as datepickers or sliders.
"accessibility": The framework produces accessible apps or uses technologies such as WAI-ARIA suite.
```

### Other

```json
"sdk": Provides its own SDK.
"ads": Supports advertisement such as AdMob, iAd or Google Mobile Ads or provides services for any other adserver.
"encryption": Provides tools for the encryption of either stored data or communication.
```

## License

### Which terms apply to the framework?

```json
"free"
"opensource"
```

## Values

Possible values for those attributes are:

```json
true: your framework supports this attribute (platform, hardware feature, ...).
false: your framework does NOT support this attribute (platform, hardware feature, ...).
"partially": your framework supports a certain attribute only partially. E.g.: it is true that your framework supports access to information about the current network but maybe only for wlan and not about 3G.
"via": your framework supports a certain attribute but only via plugin.
"soon": your framework does not support this attribute but it is already on your roadmap and will be implemented soon.
"none": you cannot provide any information about this attribute or a certain attribute is not applicable.
```

Missing attributes or empty values will be interpreted as "false". Saves bandwidth for all attributes you want to be "false".
