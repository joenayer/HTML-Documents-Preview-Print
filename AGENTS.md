# Agent instructions

Read [`.ai-os/README.md`](.ai-os/README.md), [`README.md`](README.md), and the relevant portion of [`index.html`](index.html) before changing this repository.

- Keep the utility client-side and independently runnable unless the task explicitly changes that architecture.
- Treat pasted HTML, CSS, URLs, and rendered iframe content as untrusted input. Do not add credential handling or silently send document content to a service.
- Preserve print and preview behavior across common page sizes. Test both on-screen preview and print output after layout changes.
- Keep changes small and record assumptions that materially affect output.
- Never commit secrets or user documents. Do not deploy or publish unless the task explicitly authorizes it.

The repository is the source of truth for project behavior. Joel AI OS supplies shared working preferences only.
