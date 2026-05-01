# Herald

A personal AI voice assistant for macOS. Always-on, always listening — powered by Claude.

## Download

Go to [Releases](https://github.com/evan-moon/herald-releases/releases) and download the latest `Herald-vX.X.X-arm64.dmg`.

**Requires macOS 13 or later, Apple Silicon (M1+)**

## First Launch

Apple has not yet verified this app. To open it:

1. Open the downloaded `.dmg` and drag Herald to Applications
2. Try to open Herald — macOS will block it
3. Go to **System Settings → Privacy & Security**, scroll down, click **Open Anyway**

Or run this once in Terminal:

```
xattr -cr /Applications/Herald.app
```

## Setup

On first launch Herald will ask for:
- **Microphone access** — required for voice detection
- **OpenAI API key** — for speech-to-text transcription
- **Anthropic API key** — for Claude AI responses
