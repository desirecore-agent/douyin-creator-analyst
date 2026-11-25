# Douyin Creator Analyst

A DesireCore Agent for turning creator videos into timestamped evidence, account reports and practical exercises. Start with a creator page, individual video links, or local files. Examples are generic and all analysis is scoped to the media available to the user.

Rea-Video and Creator Research are enabled when the Agent is installed. The first CLI run provisions the pinned Rea-Video version in a uv-managed environment. The machine needs uv, Git, FFmpeg and ffprobe, a writable workspace and network access for first-run packages and models. Video analysis runs locally by default. Retrieval can use an authorized browser session or files supplied by the user. Optional external services require their own setup and permission, and may cost extra.

Original Agent content is MIT licensed. The bundled Rea-Video Skill is Apache-2.0. See [third-party notices](THIRD_PARTY_NOTICES.md) and [中文说明](README.zh-CN.md).
