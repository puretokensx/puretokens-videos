# Pure Tokens 视频资料库

Pure Tokens 教程原视频的统一公开分享入口。今后新增视频统一放在本仓库。

[查看全部视频附件](https://github.com/puretokensx/puretokens-videos/releases/tag/v1.0.0)

| 视频 | 文件大小 | 下载 |
| --- | ---: | --- |
| ChatGPT + DeepSeek 原视频 | 173.97 MB | [下载原视频](https://github.com/puretokensx/puretokens-videos/releases/download/v1.0.0/chatgpt-deepseek.mp4) |
| Pure Tokens 客户端使用教程 | 592.26 MB | [下载原视频](https://github.com/puretokensx/puretokens-videos/releases/download/v1.0.0/puretokens-client-usage.mp4) |
| Skill 使用教程 | 380.71 MB | [下载原视频](https://github.com/puretokensx/puretokens-videos/releases/download/v1.0.0/skill.mp4) |
| Codex 安装教程 | 218.55 MB | [下载原视频](https://github.com/puretokensx/puretokens-videos/releases/download/v1.0.0/codex-installation.mp4) |

文件保持原视频内容，不进行压缩或转码。`videos.json` 记录文件名、字节数、SHA-256 与下载地址。MB 按 1,000,000 字节计算。

## 后续上传约定

- 新视频作为本仓库 `v1.0.0` Release 的附件上传，并更新本页和 `videos.json`。
- 使用固定的英文文件名；不同视频使用不同名称，不覆盖已有附件，以保持分享链接稳定。
- MP4 保存在 Release 附件中，不提交到 Git 文件历史。

维护命令示例（macOS/Linux/Windows 安装并登录 GitHub CLI `gh`；无需播放器或转码工具）：

```sh
gh release upload v1.0.0 /path/to/new-video.mp4 --repo puretokensx/puretokens-videos
```

上传前核对文件名是否已存在；上传后核对文件大小、SHA-256 与未登录下载状态，再更新目录。下载仅需可访问 GitHub 的浏览器，不依赖操作系统或 Python 版本。

## 旧入口

最初的 `chatgpt-deepseek-video` 仓库已更名为本视频库。原 `puretokens-client-usage-video` 与 `puretokens-skill-video` 仓库已清理删除；指向这两个旧仓库的历史下载链接不再使用。今后请统一分享本仓库或上方下载地址。
