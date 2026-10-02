# IPTV Action (aka sparkSammy TV backend.)

GitHub Action that auto-creates American (as in USA) IPTV playlists, checking the contents of the source M3Us, and then use only use the seemingly working parts of the source lists' contents. List contents brought to you by our comrades at: [FreeTuxTV](https://database.freetuxtv.net), @Free-TV, @iptv-org, and @junguler.

## Disclaimer

This project just gathers and aggregate publicly available data from the internet. As far as we know, these sources are legally published with permission from the copyright holder. If you must shut down a source listed in the "list.m3u" file, send takedown notice to THESE services, not this project. Note that linking (which is what we do via the M3U file) does not directly infringe copyright because no copy is made on the site providing the link, and thus this is not a valid reason to send a DMCA notice to GitHub. However, if you were to put the illegal source(s) in "Issues" providing proof we'll gladly remove it. Just keep in mind I do this as a hobby, so I cannot guarantee I'll be online 24/7. :-)

## M3U Sources

```
SOURCES=(
          		"https://raw.githubusercontent.com/iptv-org/iptv/refs/heads/master/streams/us.m3u"
              "https://raw.githubusercontent.com/Free-TV/IPTV/refs/heads/master/playlists/playlist_usa.m3u8"
              "https://database.freetuxtv.net/WebStreamExport/index?format=m3u&type=1&status=2&country=us&isp=all"
          		"https://raw.githubusercontent.com/iptv-org/iptv/refs/heads/master/streams/uk.m3u"
              "https://github.com/Free-TV/IPTV/raw/refs/heads/master/playlists/playlist_uk.m3u8"
              "https://database.freetuxtv.net/WebStreamExport/index?format=m3u&type=1&status=2&country=gb&isp=all"
          		"https://raw.githubusercontent.com/iptv-org/iptv/refs/heads/master/streams/au.m3u"
              "https://github.com/Free-TV/IPTV/raw/refs/heads/master/playlists/playlist_australia.m3u8"
          		"https://raw.githubusercontent.com/iptv-org/iptv/refs/heads/master/streams/mx.m3u"
              "https://github.com/Free-TV/IPTV/raw/refs/heads/master/playlists/playlist_mexico.m3u8"
          		"https://raw.githubusercontent.com/junguler/m3u-radio-music-playlists/refs/heads/main/radio_matik/checked/usa.m3u"
          		"https://raw.githubusercontent.com/junguler/m3u-radio-music-playlists/main/radio_matik/checked/united-kingdom.m3u"
          		"https://github.com/junguler/m3u-radio-music-playlists/raw/refs/heads/main/+checked+/j/japan.m3u"
          		"https://github.com/junguler/m3u-radio-music-playlists/raw/refs/heads/main/+checked+/j/japanese.m3u"
          		"https://github.com/junguler/m3u-radio-music-playlists/raw/refs/heads/main/+checked+/j/j_pop.m3u"
          		"https://github.com/junguler/m3u-radio-music-playlists/raw/refs/heads/main/fm_cube/checked/mexico.m3u"
          		"https://raw.githubusercontent.com/junguler/m3u-radio-music-playlists/main/streema/checked/Mexico.m3u"
          		)
```

## Playlist link

```https://tv.sparksammy.com```

## Rules for this repo

1. No pirated sources!
2. If you notice a pirated source and have proof, feel free to open an issue!
3. Read the disclaimer carefully.
4. No poorly maintained sources.
5. Sources must be at least 4 months old.

## License

Published under public domain with ❤️  with the CC0 1.0 License! Enjoy!
