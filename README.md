# **THIS REPO IS ARCHIVED!!!**

**Please follow the link below to the new location of the code**

**https://github.com/bonanitech/node-red-contrib-theme-midnight-red**

# Midnight Node-RED theme

![Project Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

[![GitHub Activity][commits-shield]][commits]
[![GitHub Last Commit][last-commit-shield]][commits]

[![Buy me a coffee][buymeacoffee-shield]][buymeacoffee]

## About

This is a dark theme for [Node-RED][node-red] based on the [midnight theme][ha-midnight-theme] for [Home Assistant][home-assistant].

![screenshot](https://raw.githubusercontent.com/bonanitech/midnight-red/master/images/screenshot.png)

## Install

Copy `midnight.css` and `theme-tomorrow.js` into the same directory of your `settings.js` file.

Add the folowing to the `editorTheme` section of your `settings.js`.

```js
editorTheme: {
    page: {
        css: "<config-path>/midnight.css",
        scripts: "<config-path>/theme-tomorrow.js"
    }
}
```

Replace `<config-path>` with the directory where your `settings.js` file is located. For example, `/config/node-red`.

For more details on the configuration please refer to the [Node-RED official documentation][node-red-doc].

Restart Node-RED.

Enjoy!

## License

MIT License

Copyright (c) 2019 Mauricio Bonani

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

[bonanitech]: https://github.com/bonanitech
[buymeacoffee-shield]: https://www.buymeacoffee.com/assets/img/guidelines/download-assets-sm-2.svg
[buymeacoffee]: https://www.buymeacoffee.com/mbonani
[commits-shield]: https://img.shields.io/github/commit-activity/y/bonanitech/midnight-red.svg?style=for-the-badge
[commits]: https://github.com/bonanitech/midnight-red/commits/master
[contributors]: https://github.com/bonanitech/midnight-red/graphs/contributors
[discord-shield]: https://img.shields.io/discord/330944238910963714.svg
[ha-midnight-theme]: https://community.home-assistant.io/t/midnight-theme/28598
[home-assistant]: https://home-assistant.io
[issue]: https://github.com/bonanitech/midnight-red/issues
[last-commit-shield]: https://img.shields.io/github/last-commit/bonanitech/midnight-red.svg?style=for-the-badge
[license-shield]: https://img.shields.io/github/license/bonanitech/midnight-red.svg?style=for-the-badge
[maintenance-shield]: https://img.shields.io/maintenance/no/2019.svg?style=for-the-badge
[master-branch]: https://github.com/bonanitech/midnight-red/tree/master
[node-red-doc]: https://nodered.org/docs/configuration
[node-red]: https://nodered.org/
