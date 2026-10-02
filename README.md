# DownKyi (哔哩下载姬)

A Windows desktop application for downloading and processing Bilibili videos, built with .NET Framework. The historical guide describes video lookup, QR login, resumable downloads, subtitles/danmaku, and media processing.

Original Chinese documentation: [README.zh-CN.md](README.zh-CN.md).

## Requirements

Windows and .NET Framework 4.7.2 or newer. Source development requires Visual Studio with the .NET desktop workload. Media processing uses Aria2 and FFmpeg.

## Getting started

For the historical release and feature guide, see the preserved Chinese README. For source development, open the solution under `src/` in Visual Studio, restore its dependencies, and build the selected configuration.

## Project structure

| Path | Purpose |
| --- | --- |
| `src` | .NET Framework application and supporting projects |
| `images` | Screenshots and documentation images |
| `CHANGELOG.md` | Historical release notes |

## Configuration and limitations

This checkout targets Windows/.NET Framework; a Linux .NET SDK is not a substitute for its desktop runtime. Service APIs and historical download links may have changed. Use media only as permitted by its owners and the service.

## Development and validation

Verify lookup and a permitted sample download on Windows, then inspect the output audio/video. No current cross-platform build or automated integration result is claimed.

## Related projects and attribution

Upstream releases and attribution: [FlySelfLog/downkyi](https://github.com/FlySelfLog/downkyi).

## License

See [LICENSE](LICENSE).
