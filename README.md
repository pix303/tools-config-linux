# .config folder for linux

Tools used in linux distro in wsl2 managed by [Mise En Place](https://mise.jdx.dev)

For install LSPs for html, js, ts, css, json or other js stuff don't use Mise En Place but `pnpm i -g`.

The packages managed by pnpm are:
- tailwindcss-language-server 0.0.1
- typescript-language-server 5.1.2
- vscode-langservers-extracted 4.10.0

It's not a good idea manage npm packages with Mise En Place using `npm:name-of-package`: this cause problems in first installation after cloning this repo and it's better for Helix that immediately find LSPs.
