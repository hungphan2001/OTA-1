# ion #

### device_codename.json template ###
```bash

{
  "error": false,
  "id": "b2a83561a00022dc12847939990b273607fed6c556fac55ed86ffb5d4bcbf23f",
  "filename": "ion-2.x.a/b-{device}-{YYYYmmdd}-{HHMM}-OFFICIAL-Release.zip",
  "datetime": 1674574271,
  "version": "v2.x.a/b",
  "size": 1321094201,
  "url": "https://sourceforge.net/projects/i-o-n/files/device/{brand}/{device}/ion-2.x.a/b-{device}-{YYYYmmdd}-{HHMM}-OFFICIAL-Release.zip/download",
  "filehash": "722160da4ae76a288f71b2fbdbc2576d",
  "website_url": "https://sourceforge.net/projects/i-o-n/files/device",
  "news_url": "https://t.me/ion_OS",
  "donate_url": "https://Paypal.me/AnkitGourav",
  "maintainer": "AnkitGourav",
  "maintainer_url": "https://github.com/Ankit-Gourav",
  "forum_url": "https://t.me/i_o_n"
}

```

### device_codename.json ###
| Param | Description | Required |
|--|--|--|
| id | Build file (.zip)  hash | Yes |
| filename | Build file (.zip) name | Yes |
| datetime | Build file (.zip) time | Yes |
| version | ion version | Yes |         
| filesize | Build file (.zip) size (in bytes) | Yes |
| file url | Build file url | Yes |
| filehash | Build file (.zip) md5 hash | Yes |
| website_url | https://sourceforge.net/projects/i-o-n/files/device | Yes |
| news_url | https://t.me/ion_OS | Yes |
| maintainer | your name | Yes |
| forum_url | XDA Thread | Yes |

### device_codename.md template ###
```bash

^ion
 "Changelog"

```

Note: Add Changelog from second line only
