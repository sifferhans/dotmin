# Dotmin.js

I think every JS developer can agree; there is a lot of typing involved in creating an app.
Thus I decided to create this much needed JavaScript library.

## Installation

First of all you need to download the code.
Done? Great.
Now you need to add the script to your application.

```
<script src="path/to/file/dotmin.js"></script>

// Other scripts here
```
Make sure you put the dotmin script BEFORE other script tags.

## Getting Started

This library contains many functions that will spare you a whole lot of time when creating JavaScript applications.

### console.log()

The ```console.log(value);``` method is simply shortened to ```cl(value);```

### document.querySelector()

The block of code ```var myElement = document.querySelector('.myElement');``` will be shortened by a lot;
```
var myElement = dq('.myElement');
```
Is that shorter, or what?

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/sifferhans/dotmin/tags).

## Authors

* **Sigve Hansen** - *Creator* - [sifferhans](https://github.com/sifferhans)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Inspiration

* Inspired by [cl.js](https://github.com/johnchinjew/cl.js)
