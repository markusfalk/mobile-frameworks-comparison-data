<img src="https://raw.githubusercontent.com/markusfalk/mobile-frameworks-comparison-data/master/mfcc.png" alt="mobile frameworks comparison chart">

# mobile-frameworks-comparison-data

In this repository you can find the JSON-data that is used for the  Mobile Frameworks Comparison Chart.

## Please Contribute

Would you like to add your framework to the comparison chart? Do you want to contribute to the data that is already gathered?

No Problem! All you have to do is create a pull request and let me know what you would like to change.

Below you find the documentation for the JSON files.

## JSON

You can find one file per framework in `/json`.

```javascript
{
  "book": "string", // url
  "documentation": "string", // url
  "languages": [""], // array of strings: ["actionscript", "cplusplus", "csharp", "java", "javascript", "lua", "php", "python", "ruby", "visual", "fsharp", "swift", "objectivec"]
  "name": "string",
  "platforms": [""], // array of strings: ["android", "wearos", "blackberryos", "firefoxos", "ios", "tizen", "watchos", "windowsphone", "windows", "macos", "linux""]
  "tutorial": "string", // url
  "video": "string", // url
  "website": "string" // url
}
```

If you have any questions feel free to contact me at https://twitter.com/mFrameworks.
