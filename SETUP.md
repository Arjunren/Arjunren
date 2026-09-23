# Repository package setup

Copy the contents of this package into the root of `Arjunren/Arjunren` and commit/push them.

The included workflow runs on the first push, can be run manually, and refreshes the 3D contribution calendar daily. It creates `profile-3d-contrib/`, including the SVGs referenced by `README.md`.

If GitHub blocks the workflow from pushing generated SVG files, set the repository's **Settings → Actions → General → Workflow permissions** to **Read and write permissions**, then run **GitHub-Profile-3D-Contrib** from the Actions tab.
