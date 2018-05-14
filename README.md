# Community Hass.io Add-ons for Home Assistant

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

[![GitLab CI][gitlabci-shield]][gitlabci]
[![Bountysource][bountysource-shield]][bountysource]
![Awesome][awesome-shield]

[![Discord][discord-shield]][discord]
[![Community Forum][forum-shield]][forum]

## About

Hass.io allows anyone to create add-on repositories to share their add-ons for
Hass.io easily. This repository is one of those repositories, providing extra
Home Assistant add-ons for your Hass.io installation.

The primary goal of this project is to provide you (as a Hass.io /
Home Assistant user) with additional, high quality, add-ons that allow you to
take your automated home to the next level.

## Installation

Adding this add-ons repository to your Hass.io Home Assistant instance is
pretty easy. Follow [the official instructions][third-party-addons] on the
website of Home Assistant, and use the following URL:

```txt
https://github.com/hassio-addons/repository
```

## Add-ons provided by this repository

### &#10003; [IDE][addon-ide]

![Latest Version][ide-version-shield]
![Supports armhf Architecture][ide-armhf-shield]
![Supports aarch64 Architecture][ide-aarch64-shield]
![Supports amd64 Architecture][ide-amd64-shield]
![Supports i386 Architecture][ide-i386-shield]
![Docker Pulls][ide-pulls-shield]

Advanced IDE for Home Assistant, based on Cloud9 IDE

[:books: IDE add-on documentation][addon-doc-ide]

## Releases

Add-on releases are **NOT** based on [Semantic Versioning][semver], unlike
all our other repositories. The latest build commit SHA hash of each
add-on, represents the version number.

## Support

Got questions?

You have several options to get them answered:

- The Home Assistant [Community Forum][forum].
- The Home Assistant [Discord Chat Server][discord].
- Join the [Reddit subreddit][reddit] in [/r/homeassistant][reddit]

You could also open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: IDE][ide-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it.

We have set up a separate document containing our
[contribution guidelines](CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

## Adding a new add-on

Have you created an add-on that you want to list in the Community Repository?
Contact [Franck Nijhof][frenck]:

- Drop him an email: frenck@addons.community
- Chat with him on [Discord Chat][discord]: Frenck#4484 (@frenck)
- Message him via the forums: [frenck][forum-frenck]

He will set up a GitHub repository and all the other plumbing,
and of course, give you developer access to your contribution.

## License

MIT License

Copyright (c) 2017 Franck Nijhof

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[ide-issue]: https://github.com/hassio-addons/addon-ide/issues
[ide-version-shield]: https://img.shields.io/badge/version-v0.2.0-blue.svg
[ide-pulls-shield]: https://img.shields.io/docker/pulls/hassioaddons/ide-amd64.svg
[ide-aarch64-shield]: https://img.shields.io/badge/aarch64-no-red.svg
[ide-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[ide-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[ide-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[forum-frenck]: https://community.home-assistant.io/u/frenck/?u=frenck
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[forum]: https://community.home-assistant.io?u=frenck
[frenck]: https://github.com/frenck
[gitlabci-shield]: https://gitlab.com/hassio-addons/repository/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/hassio-addons/repository/pipelines
[issue]: https://github.com/hassio-addons/repository/issues
[license-shield]: https://img.shields.io/github/license/hassio-addons/repository.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2018.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[reddit]: https://reddit.com/r/homeassistant
[semver]: http://semver.org/spec/v2.0.0.html
[third-party-addons]: https://home-assistant.io/hassio/installing_third_party_addons/
