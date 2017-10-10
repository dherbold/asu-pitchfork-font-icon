# ASU Pitchfork Font Icon

ASU's pitchfork (shocker) hand sign logo thingy as a font. Originally intended for use with banner and inline marketing material for ASU's Mary Lou Fulton Teachers College. 

## Getting Started

Fork or Clone https://github.com/dherbold/asu-pitchfork-font-icon.git

**Local machine use:** 

Install the TTF font for use on your local machine. In order to copy the character associated with each icon, refer to the text box at the bottom right corner of each glyph in demo.html. The character inside this text box may be invisible; but it can still be copied. See this guide for more info: [IcoMoon.io](https://icomoon.io/#docs/local-fonts)

You won't need any of the files located under the *demo-files* directory when including the generated font in your own projects.

You can import *selection.json* back to the IcoMoon app using the *Import Icons* button (or via Main Menu → Manage Projects) to retrieve this icon selection so you can tweak to taste however you want.

Ive added the original shocker vector file as an additional resource. 


### Prerequisites

No real Prerequisites here, but do access [IcoMoon.io](https://icomoon.io/) for more utilities related to it. 


### Installing

```css
@font-face {
  font-family: 'asu_shocker';
  src: url('../fonts/asu_shocker/asu_shocker.eot');
  src: url('../fonts/asu_shocker/asu_shocker.eot#iefix') format('embedded-opentype'), url('../fonts/asu_shocker/asu_shocker.ttf') format('truetype'), url('../fonts/asu_shocker/asu_shocker.woff') format('woff'), url('../fonts/asu_shocker/asu_shocker.svg#asu_shocker') format('svg');
  font-weight: normal;
  font-style: normal;
}
```
```css
.shocker {
  font-family: 'asu_shocker' !important;
  speak: none;
  font-style: normal;
  font-weight: normal;
  font-variant: normal;
  text-transform: none;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
```
```css
.shocker-asu_shocker:before {
  content: "\e900";
  color: white;
  font-size: 100px;
  vertical-align: middle;
}
```
```html
<i class="shocker shocker-asu_shocker"></i>
```

[Sample Use]: https://github.com/dherbold/asu-pitchfork-font-icon/blob/master/screenshot.gif "Used in header"



## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc
