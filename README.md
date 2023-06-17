# tinytldr

Minimalist [tldr](https://tldr.sh/) command line client, written in plain C99.

# KILLER FEATURES

* It builds.
* And then works.
* Small.
* Cross platform, tested on Linux, Windows, and FreeBSD.
* Depends on nothing but libcurl and libarchive.

# PREVIEW

![screenshot](screenshot.png)

# QUICK START

## Install package

* [Slackware](https://slackbuilds.org/repository/15.0/misc/tinytldr/?search=tinytldr)

## Install from source

Clone this repository and enter it:

```bash
git clone https://github.com/kovmir/tinytldr
cd tinytldr
```

Compile and install:

```bash
make
sudo make install
```

Run:

```bash
tldr -u
```

To view a page

```bash
tldr cd
tldr windows/scoop # Or one could specify a platform.
```

# LICENSE

Copyright 2023 Ivan Kovmir

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

# CREDITS

Thanks [@bilditup1](https://github.com/bilditup1) for Windows support.

# CONTRIBUTING

When submitting PRs, please maintain the [coding
style](https://suckless.org/coding_style/) used for the project.
