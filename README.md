# AVDC-API Backend Server

This code is no longer maintained, for anyone looking for an alternative implementation, please see [this project](https://github.com/javtube).

[CLI Version](https://github.com/yoshiko2/AV_Data_Capture)

![](https://img.shields.io/badge/build-passing-brightgreen.svg?style=flat)
![](https://img.shields.io/github/license/yoshiko2/av_data_capture.svg?style=flat)
![](https://img.shields.io/github/release/yoshiko2/av_data_capture.svg?style=flat)
![](https://img.shields.io/badge/Python-3.8-yellow.svg?style=flat&logo=python)

[GUI Version](https://github.com/moyy996/AVDC)

![](https://img.shields.io/badge/build-passing-brightgreen.svg?style=flat)
![](https://img.shields.io/github/license/moyy996/avdc.svg?style=flat)
![](https://img.shields.io/github/release/moyy996/avdc.svg?style=flat)
![](https://img.shields.io/badge/Python-3.6-yellow.svg?style=flat&logo=python)
![](https://img.shields.io/badge/Pyqt-5-blue.svg?style=flat)

API Version

![](https://img.shields.io/badge/build-passing-brightgreen.svg?style=flat)
![](https://img.shields.io/github/license/xjasonlyu/avdc-api.svg?style=flat)
![GitHub last commit](https://img.shields.io/github/last-commit/xjasonlyu/avdc-api)
![](https://img.shields.io/badge/Python-3.9-yellow.svg?style=flat&logo=python)
![](https://img.shields.io/badge/Flask-1.1.x-blue.svg?style=flat)

## Features

- Flask-based server is compatible with [Jellyfin.Plugin.AVDC](https://github.com/xjasonlyu/jellyfin-plugin-avdc)
- Cover image can be cropped based on [Google Vision](https://cloud.google.com/vision/docs/detecting-faces)
- Metadata can be stored in Database (e.g. Sqlite, Mysql)

## Document

Document can be found at [Wiki](https://github.com/xjasonlyu/avdc-api/wiki)

## API

| Endpoint | Description |
| --- | ----------- |
| `/actress/<name>` | Retrieve Actress Metadata|
| `/metadata/<vid>` | Retrieve Movie Metadata |
| `/image/actress/<name>` | Retrieve `2:3` Scale Actress Avatar |
| `/image/primary/<vid>` | Retrieve `2:3` Scale Movie Poster |
| `/image/thumb/<vid>` | Retrieve `16:9` Scale Movie Thumbnail |
| `/image/backdrop/<vid>` | Retrieve Full Scale Movie Backdrop |

## License

This software is released under the [GPL-3.0](LICENSE) open-source license.
