[![Build Status](https://travis-ci.org/pid/speakingurl.png)](https://travis-ci.org/pid/speakingurl) [![NPM version](https://badge.fury.io/js/speakingurl.png)](http://badge.fury.io/js/speakingurl)

# Speaking URL
Generate of so called "static" or "nice-looking" or "SpeakingURL" or "slug" from a string.


## Contribution
The current state is definitely not complete - we need you to improve it! 

started with the transformation table taken from https://github.com/dypsilon/js-replace-diacritics (AMD)


## Installation

```bash
$ npm install speakingurl
```

## Running tests

[![Build Status](https://travis-ci.org/pid/speakingurl.png)](https://travis-ci.org/pid/speakingurl)

```bash
$ npm test
```

## Usage

```js

    var makeUrl = require('speakingurl'),
        url, string;

    string = "Möchtest du eine schöne URL?";
    slug = makeUrl(string);

    console.log(url); // Output: moechtest-du-eine-schoene-url


    string = "Première neige repéré!!";
    slug = makeUrl(string);

    console.log(url); // Output: premiere-neige-repere

```

## License
[BSD](https://raw.github.com/pid/speakingurl/master/LICENCE)

The BSD 3-Clause License (BSD3)

Copyright (c) 2013 Sascha Droste <sascha.droste@gmail.com>
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
* Neither the name of the author nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.