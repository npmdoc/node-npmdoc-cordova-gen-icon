# api documentation for  [cordova-gen-icon (v0.4.6)](https://bitbucket.org/ntakimura/cordova-gen-icon#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-cordova-gen-icon.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cordova-gen-icon) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cordova-gen-icon.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cordova-gen-icon)
#### Apache Cordova Icon Generator

[![NPM](https://nodei.co/npm/cordova-gen-icon.png?downloads=true)](https://www.npmjs.com/package/cordova-gen-icon)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cordova-gen-icon/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-cordova-gen-icon_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cordova-gen-icon/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cordova-gen-icon/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cordova-gen-icon/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Naoki Takimura"
    },
    "bin": {
        "cordova-gen-icon": "bin/cordova-gen-icon"
    },
    "dependencies": {
        "commander": "*",
        "dom-js": "*",
        "imagemagick": "*"
    },
    "description": "Apache Cordova Icon Generator",
    "devDependencies": {
        "mocha": "*"
    },
    "directories": [
        "bin",
        "libs",
        "hooks"
    ],
    "dist": {
        "shasum": "86a327ee627f4255f09148294d0e87f6949613b0",
        "tarball": "https://registry.npmjs.org/cordova-gen-icon/-/cordova-gen-icon-0.4.6.tgz"
    },
    "homepage": "https://bitbucket.org/ntakimura/cordova-gen-icon#readme",
    "keywords": [
        "cordova",
        "hooks",
        "icon"
    ],
    "license": {
        "type": "WTFPL",
        "url": "http://www.wtfpl.net/about/"
    },
    "main": "index.js",
    "maintainers": [
        {
            "name": "ntakimura",
            "email": "n.takimura@gmail.com"
        }
    ],
    "name": "cordova-gen-icon",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "mercurial",
        "url": "git+ssh://git@bitbucket.org/ntakimura/cordova-gen-icon.git"
    },
    "scripts": {
        "jsdoc": "jsdoc -d jsdoc index.js libs/*.js",
        "test": "mocha -R spec tests/runner.js"
    },
    "version": "0.4.6"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module cordova-gen-icon](#apidoc.module.cordova-gen-icon)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.</span>CordovaGenIcon (options)](#apidoc.element.cordova-gen-icon.CordovaGenIcon)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.</span>CordovaGenIcon.super_ ()](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.</span>generate (options, clbk)](#apidoc.element.cordova-gen-icon.generate)
1.  object <span class="apidocSignatureSpan">cordova-gen-icon.</span>CordovaGenIcon.prototype
1.  object <span class="apidocSignatureSpan">cordova-gen-icon.</span>CordovaGenIcon.super_.prototype
1.  object <span class="apidocSignatureSpan">cordova-gen-icon.</span>GenIcon
1.  object <span class="apidocSignatureSpan">cordova-gen-icon.</span>PhoneGapGenIcon

#### [module cordova-gen-icon.CordovaGenIcon](#apidoc.module.cordova-gen-icon.CordovaGenIcon)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.</span>CordovaGenIcon (options)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.CordovaGenIcon)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.</span>super_ ()](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_)

#### [module cordova-gen-icon.CordovaGenIcon.prototype](#apidoc.module.cordova-gen-icon.CordovaGenIcon.prototype)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.prototype.</span>generateAmazonFireOSIcon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.prototype.generateAmazonFireOSIcon)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.prototype.</span>generateAndroidIcon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.prototype.generateAndroidIcon)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.prototype.</span>generateFirefoxOSIcon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.prototype.generateFirefoxOSIcon)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.prototype.</span>generateIOSIcon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.prototype.generateIOSIcon)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.prototype.</span>generateWindowsPhone8Icon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.prototype.generateWindowsPhone8Icon)

#### [module cordova-gen-icon.CordovaGenIcon.super_](#apidoc.module.cordova-gen-icon.CordovaGenIcon.super_)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.</span>super_ ()](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.super_)

#### [module cordova-gen-icon.CordovaGenIcon.super_.prototype](#apidoc.module.cordova-gen-icon.CordovaGenIcon.super_.prototype)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>convert (src, dest, width, height, options, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.convert)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>generate (clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generate)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>generateAmazonFireOSIcon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generateAmazonFireOSIcon)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>generateAndroidIcon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generateAndroidIcon)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>generateFirefoxOSIcon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generateFirefoxOSIcon)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>generateIOSIcon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generateIOSIcon)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>generateWindowsPhone8Icon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generateWindowsPhone8Icon)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>mkdir (dir, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.mkdir)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>prepare (clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.prepare)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>resize (src, dests, options, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.resize)

#### [module cordova-gen-icon.GenIcon](#apidoc.module.cordova-gen-icon.GenIcon)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.</span>GenIcon ()](#apidoc.element.cordova-gen-icon.GenIcon.GenIcon)

#### [module cordova-gen-icon.PhoneGapGenIcon](#apidoc.module.cordova-gen-icon.PhoneGapGenIcon)
1.  [function <span class="apidocSignatureSpan">cordova-gen-icon.</span>PhoneGapGenIcon (options)](#apidoc.element.cordova-gen-icon.PhoneGapGenIcon.PhoneGapGenIcon)



# <a name="apidoc.module.cordova-gen-icon"></a>[module cordova-gen-icon](#apidoc.module.cordova-gen-icon)

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.</span>CordovaGenIcon (options)](#apidoc.element.cordova-gen-icon.CordovaGenIcon)
- description and source-code
```javascript
function CordovaGenIcon(options) {
  this.verbose = (options && options.verbose !== undefined && options.silent === undefined) ?
      options.verbose : false;
  this.silent = (options && options.silent !== undefined) ?
      options.silent : false;
  this.project = (options && options.project !== undefined) ?
      options.project : ".";
  this.icon = (options && options.icon !== undefined) ?
      options.icon : undefined;

  this.targets = [];
  if (options && options.android === true) {
    this.targets.push("android");
  }
  if (options && options.ios === true) {
    this.targets.push("ios");
  }
  if (options && options.firefoxos === true) {
    this.targets.push("firefoxos");
  }
  if (options && options.amazonfireos === true) {
    this.targets.push("amazon-fireos");
  }
  if (options && options.windowsphone8 === true) {
    this.targets.push("wp8");
  }
}
```
- example usage
```shell
...
 * @param {Function} clbk callback function
 */
function generate(options, clbk) {
  if (clbk === undefined) {
    clbk = options;
  }

  var generator = new genicon.CordovaGenIcon(options);
  generator.generate(function(err) {
    if (typeof clbk === "function") {
      clbk(err);
    }
  });
}
...
```

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.super_"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.</span>CordovaGenIcon.super_ ()](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_)
- description and source-code
```javascript
function GenIcon() {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova-gen-icon.generate"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.</span>generate (options, clbk)](#apidoc.element.cordova-gen-icon.generate)
- description and source-code
```javascript
function generate(options, clbk) {
  if (clbk === undefined) {
    clbk = options;
  }

  var generator = new genicon.CordovaGenIcon(options);
  generator.generate(function(err) {
    if (typeof clbk === "function") {
      clbk(err);
    }
  });
}
```
- example usage
```shell
...
/**
* @file
* cordova-gen-icon is Apache Cordova Icon Generator node module.
* It generates the icon files for your project.
*
* @example
* var genicon = require("cordova-gen-icon");
* genicon.generate(function(err) {
*   if (err) {
*     console.error(err);
*   }
* });
* @author Naoki Takimura <n.takimura@gmail.com>
*/
...
```



# <a name="apidoc.module.cordova-gen-icon.CordovaGenIcon"></a>[module cordova-gen-icon.CordovaGenIcon](#apidoc.module.cordova-gen-icon.CordovaGenIcon)

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.CordovaGenIcon"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.</span>CordovaGenIcon (options)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.CordovaGenIcon)
- description and source-code
```javascript
function CordovaGenIcon(options) {
  this.verbose = (options && options.verbose !== undefined && options.silent === undefined) ?
      options.verbose : false;
  this.silent = (options && options.silent !== undefined) ?
      options.silent : false;
  this.project = (options && options.project !== undefined) ?
      options.project : ".";
  this.icon = (options && options.icon !== undefined) ?
      options.icon : undefined;

  this.targets = [];
  if (options && options.android === true) {
    this.targets.push("android");
  }
  if (options && options.ios === true) {
    this.targets.push("ios");
  }
  if (options && options.firefoxos === true) {
    this.targets.push("firefoxos");
  }
  if (options && options.amazonfireos === true) {
    this.targets.push("amazon-fireos");
  }
  if (options && options.windowsphone8 === true) {
    this.targets.push("wp8");
  }
}
```
- example usage
```shell
...
 * @param {Function} clbk callback function
 */
function generate(options, clbk) {
  if (clbk === undefined) {
    clbk = options;
  }

  var generator = new genicon.CordovaGenIcon(options);
  generator.generate(function(err) {
    if (typeof clbk === "function") {
      clbk(err);
    }
  });
}
...
```

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.super_"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.</span>super_ ()](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_)
- description and source-code
```javascript
function GenIcon() {
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cordova-gen-icon.CordovaGenIcon.prototype"></a>[module cordova-gen-icon.CordovaGenIcon.prototype](#apidoc.module.cordova-gen-icon.CordovaGenIcon.prototype)

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.prototype.generateAmazonFireOSIcon"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.prototype.</span>generateAmazonFireOSIcon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.prototype.generateAmazonFireOSIcon)
- description and source-code
```javascript
generateAmazonFireOSIcon = function (name, src, platforms, clbk) {
  var dests = [{
      dest: platforms + "/amazon-fireos/res/drawable/icon.png",
      width: 96, height: 96
  }, {
      dest: platforms + "/amazon-fireos/res/drawable-ldpi/icon.png",
      width: 48, height: 48
  }, {
      dest: platforms + "/amazon-fireos/res/drawable-mdpi/icon.png",
      width: 48, height: 48
  }, {
      dest: platforms + "/amazon-fireos/res/drawable-hdpi/icon.png",
      width: 72, height: 72
  }, {
      dest: platforms + "/amazon-fireos/res/drawable-xhdpi/icon.png",
      width: 96, height: 96
  }];

  this.resize(src, dests, clbk);
}
```
- example usage
```shell
...
    _generate(err);
  });
} else if (target === "ios") {
  self.generateIOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "amazon-fireos") {
  self.generateAmazonFireOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "firefoxos") {
  self.generateFirefoxOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "wp8") {
...
```

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.prototype.generateAndroidIcon"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.prototype.</span>generateAndroidIcon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.prototype.generateAndroidIcon)
- description and source-code
```javascript
generateAndroidIcon = function (name, src, platforms, clbk) {
  var dests = [{
      dest: platforms + "/android/res/drawable/icon.png",
      width: 96, height: 96
  }, {
      dest: platforms + "/android/res/drawable-ldpi/icon.png",
      width: 36, height: 36
  }, {
      dest: platforms + "/android/res/drawable-mdpi/icon.png",
      width: 48, height: 48
  }, {
      dest: platforms + "/android/res/drawable-hdpi/icon.png",
      width: 72, height: 72
  }, {
      dest: platforms + "/android/res/drawable-xhdpi/icon.png",
      width: 96, height: 96
  }];

  this.resize(src, dests, clbk);
}
```
- example usage
```shell
...
        if (exists) {
if (!self.silent) {
  console.log();
  console.log("Generate " + target + " icon image files");
}

if (target === "android") {
  self.generateAndroidIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "ios") {
  self.generateIOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "amazon-fireos") {
...
```

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.prototype.generateFirefoxOSIcon"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.prototype.</span>generateFirefoxOSIcon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.prototype.generateFirefoxOSIcon)
- description and source-code
```javascript
generateFirefoxOSIcon = function (name, src, platforms, clbk) {
  var self = this,
      dests = [{
      dest: platforms + "/firefoxos/www/img/icon-30.png",
      width: 30, height: 30
  }, {
      dest: platforms + "/firefoxos/www/img/icon-60.png",
      width: 60, height: 60
  }, {
      dest: platforms + "/firefoxos/www/img/icon-128.png",
      width: 128, height: 128
  }];

  this.resize(src, dests, {
    circle: true
  }, function(err) {
    var i, dest;

    if (!self.silent) {
      if (err === null || err === undefined) {
        console.log("Insert 'icons' field into '" + platforms + "/firefoxos/www/manifest.web'.");
        console.log();
        console.log("\"icons:\": {");
        for (i in dests) {
          dest = dests[i];
          console.log("  \"" + dest.width + "\": " +
              dest.dest.replace(platforms + "/firefoxos/www", "") +
              ((Number(i) === dests.length - 1) ? "" : ","));
        }
        console.log("}");
        console.log();
      }
    }
    clbk(err);
  });
}
```
- example usage
```shell
...
    _generate(err);
  });
} else if (target === "amazon-fireos") {
  self.generateAmazonFireOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "firefoxos") {
  self.generateFirefoxOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "wp8") {
  self.generateWindowsPhone8Icon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else {
...
```

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.prototype.generateIOSIcon"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.prototype.</span>generateIOSIcon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.prototype.generateIOSIcon)
- description and source-code
```javascript
generateIOSIcon = function (name, src, platforms, clbk) {
  var dests = [{
      dest: platforms + "/ios/" + name + "/Resources/icons/icon.png",
      width: 57, height: 57
  }, {
      dest: platforms + "/ios/" + name + "/Resources/icons/icon-40.png",
      width: 40, height: 40
  }, {
      dest: platforms + "/ios/" + name + "/Resources/icons/icon-50.png",
      width: 50, height: 50
  }, {
      dest: platforms + "/ios/" + name + "/Resources/icons/icon-57.png",
      width: 57, height: 57
  }, {
      dest: platforms + "/ios/" + name + "/Resources/icons/icon-60.png",
      width: 60, height: 60
  }, {
      dest: platforms + "/ios/" + name + "/Resources/icons/icon-72.png",
      width: 72, height: 72
  }, {
      dest: platforms + "/ios/" + name + "/Resources/icons/icon-76.png",
      width: 76, height: 76
  }, {
      dest: platforms + "/ios/" + name + "/Resources/icons/icon-small.png",
      width: 29, height: 29
  }, {
      dest: platforms + "/ios/" + name + "/Resources/icons/iTunesArtwork.png",
      width: 512, height: 512
  }, {
      dest: platforms + "/ios/" + name + "/Resources/icons/icon@2x.png",
      width: 114, height: 114
  }, {
      dest: platforms + "/ios/" + name + "/Resources/icons/icon-40@2x.png",
      width: 80, height: 80
  }, {
      dest: platforms + "/ios/" + name + "/Resources/icons/icon-50@2x.png",
      width: 100, height: 100
  }, {
      dest: platforms + "/ios/" + name + "/Resources/icons/icon-57@2x.png",
      width: 114, height: 114
  }, {
      dest: platforms + "/ios/" + name + "/Resources/icons/icon-60@2x.png",
      width: 120, height: 120
  }, {
      dest: platforms + "/ios/" + name + "/Resources/icons/icon-72@2x.png",
      width: 144, height: 144
  }, {
      dest: platforms + "/ios/" + name + "/Resources/icons/icon-76@2x.png",
      width: 152, height: 152
  }, {
      dest: platforms + "/ios/" + name + "/Resources/icons/icon-small@2x.png",
      width: 58, height: 58
  }, {
      dest: platforms + "/ios/" + name + "/Resources/icons/iTunesArtwork@2x.png",
      width: 1024, height: 1024
  }];

  this.resize(src, dests, { roundCorner: true }, clbk);
}
```
- example usage
```shell
...
}

if (target === "android") {
  self.generateAndroidIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "ios") {
  self.generateIOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "amazon-fireos") {
  self.generateAmazonFireOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "firefoxos") {
...
```

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.prototype.generateWindowsPhone8Icon"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.prototype.</span>generateWindowsPhone8Icon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.prototype.generateWindowsPhone8Icon)
- description and source-code
```javascript
generateWindowsPhone8Icon = function (name, src, platforms, clbk) {
  var dests = [{
      dest: platforms + "/wp8/ApplicationIcon.png",
      width: 62, height: 62
  }];

  this.resize(src, dests, clbk);
}
```
- example usage
```shell
...
    _generate(err);
  });
} else if (target === "firefoxos") {
  self.generateFirefoxOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "wp8") {
  self.generateWindowsPhone8Icon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else {
  if (!self.silent) {
    console.log("Ignore " + target);
  }
  _generate();
...
```



# <a name="apidoc.module.cordova-gen-icon.CordovaGenIcon.super_"></a>[module cordova-gen-icon.CordovaGenIcon.super_](#apidoc.module.cordova-gen-icon.CordovaGenIcon.super_)

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.super_"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.</span>super_ ()](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.super_)
- description and source-code
```javascript
function GenIcon() {
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cordova-gen-icon.CordovaGenIcon.super_.prototype"></a>[module cordova-gen-icon.CordovaGenIcon.super_.prototype](#apidoc.module.cordova-gen-icon.CordovaGenIcon.super_.prototype)

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.convert"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>convert (src, dest, width, height, options, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.convert)
- description and source-code
```javascript
convert = function (src, dest, width, height, options, clbk) {
  if (this.verbose) {
    console.log();
  }
  if (!this.silent) {
    console.log(dest);
  }
  if (this.verbose) {
    console.log("resize");
    console.log("from  : " + src);
    console.log("dest  : " + dest);
    console.log("width : " + width);
    console.log("height: " + height);
  }

  if (clbk === undefined) {
    clbk = options;
    options = {};
  }

  var self = this,
      dir = path.dirname(dest);
  this.mkdir(dir, function(err) {
    if (err && err.code !== "EEXIST") {
      return clbk(err);
    }
    imagemagick.resize({
      srcPath: src,
      dstPath: dest,
      width: width,
      height: height + "!",
    }, function(err) {
      if (err) {
        clbk(err);
      }

      if (options && options.roundCorner === true ) {
        if (self.verbose) {
          console.log("convert round corner image");
          console.log("from  : " + dest);
          console.log("dest  : " + dest);
          console.log("round : " + (height / 6.4));
        }
        imagemagick.convert([
          "-size", width + "x" + height,
          "xc:none",
          "-fill", dest,
          "-draw",
          "roundRectangle 0,0 " + width + "," + height + " " + (width / 6.4) + "," + (height / 6.4),
          dest
        ], function(err) {
          clbk(err);
        });
      } else if (options && options.circle === true) {
        if (self.verbose) {
          console.log("convert circle image");
          console.log("from  : " + dest);
          console.log("dest  : " + dest);
          console.log("radius: " + (width / 2));
        }
        imagemagick.convert([
          "-size", width + "x" + height,
          "xc:none",
          "-fill", dest,
          "-draw",
          "circle " + (width / 2) + "," + (width / 2) + " " + (width / 2) + ",1",
          dest
        ], function(err) {
          clbk(err);
        });
      } else {
        clbk(err);
      }
    });
  });

}
```
- example usage
```shell
...
      if (options && options.roundCorner === true ) {
if (self.verbose) {
  console.log("convert round corner image");
  console.log("from  : " + dest);
  console.log("dest  : " + dest);
  console.log("round : " + (height / 6.4));
}
imagemagick.convert([
  "-size", width + "x" + height,
  "xc:none",
  "-fill", dest,
  "-draw",
  "roundRectangle 0,0 " + width + "," + height + " " + (width / 6.4) + "," + (height / 6.4),
  dest
], function(err) {
...
```

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generate"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>generate (clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generate)
- description and source-code
```javascript
generate = function (clbk) {
  var self = this,
      src,
      platformDir;

  if (clbk === undefined) {
    clbk = function(){};
  }

  platformDir = self.project + "/platforms";

  self.prepare(function(err) {
    if (err) {
      return clbk(err);
    }

    if (!self.silent) {
      console.log("Generate cordova icons with");
      console.log("project: " + self.project);
      console.log("icon   : " + self.icon);
      console.log("target : " + self.targets);
    }

    var targets = [].concat(self.targets);
    (function _generate(err){
      if (err) {
        return clbk(err);
      }

      var target = targets.shift();
      if (target === null || target === undefined) {
        return clbk();
      }

      fs.exists(platformDir + "/" + target, function(exists) {
        if (exists) {
          if (!self.silent) {
            console.log();
            console.log("Generate " + target + " icon image files");
          }

          if (target === "android") {
            self.generateAndroidIcon(self.name, self.icon, platformDir, function(err) {
              _generate(err);
            });
          } else if (target === "ios") {
            self.generateIOSIcon(self.name, self.icon, platformDir, function(err) {
              _generate(err);
            });
          } else if (target === "amazon-fireos") {
            self.generateAmazonFireOSIcon(self.name, self.icon, platformDir, function(err) {
              _generate(err);
            });
          } else if (target === "firefoxos") {
            self.generateFirefoxOSIcon(self.name, self.icon, platformDir, function(err) {
              _generate(err);
            });
          } else if (target === "wp8") {
            self.generateWindowsPhone8Icon(self.name, self.icon, platformDir, function(err) {
              _generate(err);
            });
          } else {
            if (!self.silent) {
              console.log("Ignore " + target);
            }
            _generate();
          }
        } else {
          console.log("platform \"" + target + "\" does not exist.");
          _generate();
        }
      });
    })();

  });

}
```
- example usage
```shell
...
/**
* @file
* cordova-gen-icon is Apache Cordova Icon Generator node module.
* It generates the icon files for your project.
*
* @example
* var genicon = require("cordova-gen-icon");
* genicon.generate(function(err) {
*   if (err) {
*     console.error(err);
*   }
* });
* @author Naoki Takimura <n.takimura@gmail.com>
*/
...
```

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generateAmazonFireOSIcon"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>generateAmazonFireOSIcon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generateAmazonFireOSIcon)
- description and source-code
```javascript
generateAmazonFireOSIcon = function (name, src, platforms, clbk) {
  clbk("this method must be implemented by child class.");
}
```
- example usage
```shell
...
    _generate(err);
  });
} else if (target === "ios") {
  self.generateIOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "amazon-fireos") {
  self.generateAmazonFireOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "firefoxos") {
  self.generateFirefoxOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "wp8") {
...
```

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generateAndroidIcon"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>generateAndroidIcon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generateAndroidIcon)
- description and source-code
```javascript
generateAndroidIcon = function (name, src, platforms, clbk) {
  clbk("this method must be implemented by child class.");
}
```
- example usage
```shell
...
        if (exists) {
if (!self.silent) {
  console.log();
  console.log("Generate " + target + " icon image files");
}

if (target === "android") {
  self.generateAndroidIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "ios") {
  self.generateIOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "amazon-fireos") {
...
```

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generateFirefoxOSIcon"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>generateFirefoxOSIcon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generateFirefoxOSIcon)
- description and source-code
```javascript
generateFirefoxOSIcon = function (name, src, platforms, clbk) {
  clbk("this method must be implemented by child class.");
}
```
- example usage
```shell
...
    _generate(err);
  });
} else if (target === "amazon-fireos") {
  self.generateAmazonFireOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "firefoxos") {
  self.generateFirefoxOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "wp8") {
  self.generateWindowsPhone8Icon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else {
...
```

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generateIOSIcon"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>generateIOSIcon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generateIOSIcon)
- description and source-code
```javascript
generateIOSIcon = function (name, src, platforms, clbk) {
  clbk("this method must be implemented by child class.");
}
```
- example usage
```shell
...
}

if (target === "android") {
  self.generateAndroidIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "ios") {
  self.generateIOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "amazon-fireos") {
  self.generateAmazonFireOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "firefoxos") {
...
```

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generateWindowsPhone8Icon"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>generateWindowsPhone8Icon (name, src, platforms, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.generateWindowsPhone8Icon)
- description and source-code
```javascript
generateWindowsPhone8Icon = function (name, src, platforms, clbk) {
  clbk("this method must be implemented by child class.");
}
```
- example usage
```shell
...
    _generate(err);
  });
} else if (target === "firefoxos") {
  self.generateFirefoxOSIcon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else if (target === "wp8") {
  self.generateWindowsPhone8Icon(self.name, self.icon, platformDir, function(err) {
    _generate(err);
  });
} else {
  if (!self.silent) {
    console.log("Ignore " + target);
  }
  _generate();
...
```

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.mkdir"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>mkdir (dir, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.mkdir)
- description and source-code
```javascript
mkdir = function (dir, clbk) {
  var self = this;
  fs.exists(path.dirname(dir), function(exists) {
    if (!exists) {
      self.mkdir(path.dirname(dir), function(err) {
        if (err) {
          return clbk(err);
        }
        self.mkdir(dir, function(err) {
          clbk(err);
        });
      });
    } else {
      fs.mkdir(dir, function(err) {
        clbk(err);
      });
    }
  });
}
```
- example usage
```shell
...
if (clbk === undefined) {
  clbk = options;
  options = {};
}

var self = this,
    dir = path.dirname(dest);
this.mkdir(dir, function(err) {
  if (err && err.code !== "EEXIST") {
    return clbk(err);
  }
  imagemagick.resize({
    srcPath: src,
    dstPath: dest,
    width: width,
...
```

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.prepare"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>prepare (clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.prepare)
- description and source-code
```javascript
prepare = function (clbk) {
  var self = this;

  fs.readFile(self.project + "/www/config.xml", function(err, data) {
    if (err) {
      return clbk(err);
    }
    (new domjs.DomJS()).parse(data.toString(), function(err, dom) {
      if (err) {
        return clbk(err);
      }

      var i;

      if (!self.icon) {
        for (i in dom.children) {
          if (dom.children[i].name === "icon" &&
              dom.children[i].attributes["gap:platform"] === undefined) {
            self.icon = self.project + "/www/" + dom.children[i].attributes.src;
            break;
          }
        }
        if (self.icon === undefined) {
          self.icon = self.project + "/www/img/logo.png";
        }
      }

      for (i in dom.children) {
        if (dom.children[i].name === "name") {
          self.name = dom.children[i].children[0].text;
        }
      }
      if (self.name === undefined) {
        return clbk("config.xml does not have \"name\" tag");
      }

      if (self.targets !== undefined && self.targets.length > 0) {
        clbk();
      } else {
        fs.readdir(self.project + "/platforms", function(err, platforms) {
          if (err) {
            return clbk(err);
          }
          self.targets = [].concat(platforms);
          clbk();
        });
      }
    });
  });
}
```
- example usage
```shell
...

  if (clbk === undefined) {
clbk = function(){};
  }

  platformDir = self.project + "/platforms";

  self.prepare(function(err) {
if (err) {
  return clbk(err);
}

if (!self.silent) {
  console.log("Generate cordova icons with");
  console.log("project: " + self.project);
...
```

#### <a name="apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.resize"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.CordovaGenIcon.super_.prototype.</span>resize (src, dests, options, clbk)](#apidoc.element.cordova-gen-icon.CordovaGenIcon.super_.prototype.resize)
- description and source-code
```javascript
resize = function (src, dests, options, clbk) {
  var self = this,
      targets = [].concat(dests);

  if (clbk === undefined) {
    clbk = options;
    options = undefined;
  }

  (function _resize(err) {
    if (err) {
      return clbk(err);
    }
    var target = targets.shift();
    if (target === null || target === undefined) {
      return clbk(err);
    }

    self.convert(src, target.dest, target.width, target.height, options, function(err) {
      _resize(err);
    });
  })();
}
```
- example usage
```shell
...
     dest: platforms + "/amazon-fireos/res/drawable-hdpi/icon.png",
     width: 72, height: 72
 }, {
     dest: platforms + "/amazon-fireos/res/drawable-xhdpi/icon.png",
     width: 96, height: 96
 }];

 this.resize(src, dests, clbk);
};

/**
* generateFirefoxOSIcon generates the Firefox OS icon image files.
* Thats images are trimed as circle automatically.
* @summary Generate Firefox OS Icon.
* @param {String} name projectn name.
...
```



# <a name="apidoc.module.cordova-gen-icon.GenIcon"></a>[module cordova-gen-icon.GenIcon](#apidoc.module.cordova-gen-icon.GenIcon)

#### <a name="apidoc.element.cordova-gen-icon.GenIcon.GenIcon"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.</span>GenIcon ()](#apidoc.element.cordova-gen-icon.GenIcon.GenIcon)
- description and source-code
```javascript
function GenIcon() {
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cordova-gen-icon.PhoneGapGenIcon"></a>[module cordova-gen-icon.PhoneGapGenIcon](#apidoc.module.cordova-gen-icon.PhoneGapGenIcon)

#### <a name="apidoc.element.cordova-gen-icon.PhoneGapGenIcon.PhoneGapGenIcon"></a>[function <span class="apidocSignatureSpan">cordova-gen-icon.</span>PhoneGapGenIcon (options)](#apidoc.element.cordova-gen-icon.PhoneGapGenIcon.PhoneGapGenIcon)
- description and source-code
```javascript
function PhoneGapGenIcon(options) {
  this.verbose = (options && options.verbose !== undefined) ?
      options.verbose : false;
  this.project = (options && options.project !== undefined) ?
      options.project : ".";
  this.icon = (options && options.icon !== undefined) ?
      options.icon : this.project + "/www/img/logo.png";

  this.target = [];
  if (options && options.android === true) {
    this.target.push("android");
  }
  if (options && options.ios === true) {
    this.target.push("ios");
  }
  if (options && options.firefoxos === true) {
    this.target.push("firefoxos");
  }
  if (options && options.amazonfireos === true) {
    this.target.push("amazonfireos");
  }

  if (this.verbose) {
    console.log("generate cordova icons with");
    console.log("project: " + this.project);
    console.log("icon   : " + this.icon);
    console.log("target : " + this.target);
    console.log();
  }

}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
