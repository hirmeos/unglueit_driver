# Unglue.it Driver
[![Build Status](https://travis-ci.org/hirmeos/unglueit_driver.svg?branch=master)](https://travis-ci.org/hirmeos/unglueit_driver) [![Release](https://img.shields.io/github/release/hirmeos/unglueit_driver.svg?colorB=58839b)](https://github.com/hirmeos/unglueit_driver/releases) [![License](https://img.shields.io/github/license/hirmeos/unglueit_driver.svg?colorB=ff0000)](https://github.com/hirmeos/unglueit_driver/blob/master/LICENSE)

Get API key from [https://unglue.it/api/help](https://unglue.it/api/help)

## Run via crontab
```
0 0 * * 0 docker run --rm --name "unglueit_driver" --env-file /path/to/config.env -v unglueit_cache:/usr/src/app/cache -v metrics:/usr/src/app/output openbookpublishers/unglueit_driver:1
```
