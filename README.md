# RepoGates canary: opened-folder hook

**This repository is a harmless test fixture.** It copies the *shape* of the
testmetest campaign (JFrog Security Research, 26 October 2026): hooks for Claude
Code, Gemini CLI, Cursor and VS Code that run `.github/init.js` when the folder
is opened, and an `init.js` padded to 13 MB so GitHub code search does not index it.

Here `init.js` prints one line and does nothing else. It exists so RepoGates
(https://repogates.com) can be shown flagging and blocking the shape before a
clone. Do not copy these hook files into a real project.

Report: https://research.jfrog.com/post/beyond-testmetest-42-hijacked-github-repos/
