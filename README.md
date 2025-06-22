<h1 align="center">Welcome to Kais 🧀</h1>
<div align="center">

</div>

# 📄Description

![Conversations with different models](https://github.com/user-attachments/assets/4e17f3b6-7b6a-4437-9da1-3ca03bc4b1fa)

Kais is a ChatGPT client designed to serve multiple platforms. Built using Tauri and React, this client places significant emphasis on data privacy and security. It ensures this through local data storage practices, thereby reinforcing data safety.

With Rust in its development stack, Kais also makes the most of high-speed execution and robust security.

# ✨Features
- **🔒Privacy**  
Kais prioritizes data privacy. Your credentials and chat data are never sent to our servers. They are stored locally and securely on your device.*
- **💻Cross-platform**  
Kais is designed to work across multiple platforms, including Windows, macOS, and Linux.
- **💂Security**  
The core part of Kais is built using Rust, ensuring high-speed execution and robust security. Plus, we delibrately limit the privileges of the client to the minimum necessary. You can view the list of permissions required in the `tauri.conf.json` file.
- **🤖Support for multiple providers**
  - OpenAI (ChatGPT)
  - Azure
  - Anthropic (Claude)
  - Ollama
- **📚Support for multiple models from the same provider**
  - Want to use GPT-3.5 and GPT-4 at the same time? No problem!
  - Switching models in a conversation(🚧work in progress)
- **🪜Built-in proxy**  
Kais supports proxy settings. You can set up a proxy to bypass your network restrictions.
- **🧩Prompt templates**  
CoT or COSTAR, your favorite prompt templates are available here. You can also create your own.
- **🌓Dual themes**  
Kais supports both light and dark themes.


_*: When you use online models, data is still sent to your model provider's APIs. If that bothers you, consider using Ollama's models locally_

# 📦Installation
Go to [Release](https://github.com/0xfrankz/Kais/releases) page for latest installers.

# 🛠️Built from source
1. Install Node.js
2. Install pnpm
3. Install Rust
4. Run the following commands:
```
pnpm i
pnpm tauri build
```

# 👍Development
1. Install Node.js
2. Install pnpm
3. Install Rust
4. Run the following commands:
```
pnpm i
pnpm tauri dev
```
