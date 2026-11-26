# Douyin Creator Analyst

A DesireCore Agent for turning creator videos into timestamped evidence, account reports and practical exercises. Start with a creator page, individual video links, or local files. Examples are generic and all analysis is scoped to the media available to the user.

Creator Research, Douyin Video Download, and Rea-Video are enabled at install. The Agent uses the authorized browser session to verify profile listings. The downloader handles individual share links or video IDs for works the user is allowed to save. User-supplied files can go straight to analysis.

The Agent prefers DesireCore's managed uv, Python 3.13, and FFmpeg toolkit, and uses Git from its execution environment. On the first run, uv provisions the pinned Rea-Video CLI and Python dependencies in an isolated environment. Local recognition models download as needed. Video analysis runs locally by default. Optional external services need separate setup and permission and may cost extra.

Original Agent content is MIT licensed. The bundled Rea-Video Skill is Apache-2.0. See [third-party notices](THIRD_PARTY_NOTICES.md) and [中文说明](README.zh-CN.md).
