# Content Hive Plugin: X(Twitter)

An X(Twitter) content parsing plugin for Content Hive. Fetches tweet content, images, videos, and author information via the GraphQL API.

Plugin for [Content Hive](https://github.com/content-hive/content-hive).

## Layout

```
plugin/              # plugin source, installed as plugins/twitter/ by Content Hive
├── manifest.json    # plugin metadata (domain, version, requirements, release_notes)
├── __init__.py
└── ...
contenthive.json     # repository metadata for the Content Hive plugin catalog
```

## Disclaimer

> This plugin fetches content via X(Twitter) public APIs. Please ensure compliance with X's Terms of Service and applicable local laws before use. Platform policy changes may cause the plugin to stop working.
