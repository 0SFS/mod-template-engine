# 0SFS engine mod template

Replace the example manifest with your engine. Keep `public/0sfs-mod.json` at the repository root of the published site.

1. Fork this template.
2. Edit `public/0sfs-mod.json` and add the files it names under `public/`.
3. Run `node scripts/validate-mod.mjs`.
4. Push to your repository and enable GitHub Pages from the `public/` directory.
5. In the simulator, open the Mods tab and add `owner/repo`.

JavaScript is a last resort. A plugin should be Rust compiled to `wasm32-unknown-unknown`.

## Mod

This repository is a 0SFS mod. `public/0sfs-mod.json` is the manifest. GitHub Pages serves the `public/` directory at the site root.

Fork the repository, edit the manifest and the files it names, push, then add the GitHub URL in the simulator's Mods tab.

Topics: `0sfs-mod` and `0sfs-engine`.

## Community

- [Code of conduct](https://github.com/0SFS/.github/blob/main/CODE_OF_CONDUCT.md)
- [Contributing](https://github.com/0SFS/.github/blob/main/CONTRIBUTING.md)
- [License](LICENSE)
- [Security](https://github.com/0SFS/.github/blob/main/SECURITY.md)
