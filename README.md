# CyberdropBunkrDownloader
Simple downloader for cyberdrop.me and bunkr.ru


# Usage

Before using install requirements with ```pip3 install -r requirements.txt```

Basic usage: ```python3 dump.py -u [url]```

---

```
usage: ['--help'] [-h] -u U [-e E] [-s [S]] [-i] [-p P] [-w] [-cfs] [-css]

optional arguments:
  -h, --help  show this help message and exit
  -u U        Url to fetch
  -e E        Extensions to download (comma separated)
  -p P        Path to custom downloads folder
  -w          Export url list (ex: for wget)
  -css        Check server status before downloading
  ```
