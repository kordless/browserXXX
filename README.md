# BrowserXXX

A Chrome extension that lets AI agents interact with web pages.

## What It Does

- Natural language commands control your browser
- Runs locally - your data stays on your machine
- Works with OpenAI GPT-5 (more models coming)

## Install
```bash
git clone git@github.com:kordless/browserxxx.git
cd browserxxx
npm install
npm run build
```

Load `dist/` in Chrome via `chrome://extensions/` (enable Developer Mode → Load unpacked)

Add your OpenAI API key in the extension settings.

## Status

Alpha. Works, but rough around the edges. Complex SPAs and dynamic content can be problematic.

## Testing
```bash
npm run build:testtool
```

Load `tests/tools/e2e` to test individual tools.

## License

Apache 2.0 (derived from OpenAI's Codex)
