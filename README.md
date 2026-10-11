# cuddly-memory

Sandbox repository for testing Git/GitHub workflows from a Windows workstation.

## Purpose
- Practice the commit/push flow end to end
- Keep short, reusable setup notes for local tooling

## Local AI in VS Code via Ollama (notes)

Requirements: VS Code 1.127 or newer, and Ollama running locally.

1. Pull a model from the Ollama library:

   `ollama pull qwen2.5-coder:3b`n
2. Install the official Ollama extension for VS Code:

   `code --install-extension ollama.ollama`n
3. In VS Code, open Chat and pick the model from the **Ollama** section of the model picker.
   If it is missing, run 'Ollama: Refresh Models' from the Command Palette.

Notes:
- Local (BYOK) models work without signing in to GitHub and without a Copilot plan.
- Inline completions, semantic search and embeddings still require the Copilot service.

