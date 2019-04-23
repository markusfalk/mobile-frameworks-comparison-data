# mobile-frameworks-comparison-data

JSON for the Mobile Frameworks Comparison Chart

<img src="https://raw.githubusercontent.com/markusfalk/mobile-frameworks-comparison-data/master/mfcc.png" alt="mobile frameworks comparison chart">

## Participate

Would you like to add your framework to the comparison chart? Do you want to contribute to the data that is already gathered?

No Problem! All you have to do is create a pull request and let me know what you would like to change.

Below you find the documentation for the JSON file.

## JSON

```javascript
{
  "book": "string", // url
  "documentation": "string", // url
  "languages": "string[]", // array of strings: ["actionscript", "cplusplus", "csharp", "java", "javascript", "lua", "php", "python", "ruby", "visual"]
  "name": "string",
  "platforms": "string[]", // array of strings: ["android", "blackberryos", "firefoxos", "ios", "tizen", "watchos", "windowsphone", "windows", "macos", "linux", "raspberry"]
  "tutorial": "string", // url
  "video": "string", // url
  "website": "string" // url
}
```

If you have any questions feel free to contact me at https://twitter.com/mFrameworks.
