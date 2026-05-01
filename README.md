<h1 align="center">H.E.R.A.L.D</h1>
  <p align="center"><sub><b>HUMAN&nbsp;·&nbsp;EXECUTIVE&nbsp;·&nbsp;REASONING&nbsp;·&nbsp;AGENT&nbsp;·&nbsp;LOCALLY&nbsp;·&nbsp;DEPLOYED</b></sub
  ></p>

  https://github.com/user-attachments/assets/d59a75c6-cc60-43e4-9dee-81413db85ace

  > The AI assistant from the movies. Running on your Mac.

  Always listening. Never in the way.
  A floating orb. You speak. It answers.

  No wake word. No hotkey. No window to click.

  ---

  ### It doesn't just talk. It draws.

  https://github.com/user-attachments/assets/c10a107d-81c9-47a8-aafc-7389ce9dbcb3

  Ask about your portfolio — it renders the chart.
  Ask about today — it pulls your calendar.
  Ask it to fix a bug — it writes the code.

  ---

  ## ⬇ Download

  **[Latest Release](../../releases/latest)**

  `macOS 13+` · `Apple Silicon`

  Free. Bring your own OpenAI key & Claude Code.

  ---

  <details>
  <summary><b>First Launch</b> — bypass Apple's "unverified developer" warning</summary>

  Herald isn't signed with an Apple Developer ID yet. On first launch macOS will block it.

  **Option 1 — System Settings**
  1. Try to open Herald (it will be blocked)
  2. Open `System Settings` → `Privacy & Security`
  3. Scroll down, find Herald, click `Open Anyway`

  **Option 2 — Terminal**
  ```bash
  xattr -dr com.apple.quarantine /Applications/Herald.app

  - Microphone access — for voice detection
  - OpenAI API key — for speech-to-text (gpt-4o-transcribe)
  - Claude Code — for agent reasoning

  Configure all three in Herald's settings panel on first launch.

  이대로 herald-releases README.md에 통째로 붙여넣으면 돼. 영상 두 개 다 자동으로 임베드 플레이어로 렌더링됨.
