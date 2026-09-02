# Text Diff Checker

Paste two blocks of text and see every added or removed line highlighted at a glance. Runs entirely in your browser.

**Live:** <https://text-diff-checker.slippylabs.com/>

## What it does

- Paste two blocks of text and see every added and removed line highlighted.
- Line-level diff, no upload, no account, no size limit beyond what your browser can hold.

## Run it locally

A static site. No build step, no package manager, no dependencies:

```
git clone git@github.com:slippylabs/text-diff-checker.slippylabs.com.git
cd text-diff-checker.slippylabs.com
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

---

Part of [Slippy Labs](https://slippylabs.com). Every tool is indexed at
[projects.slippylabs.com](https://projects.slippylabs.com).
