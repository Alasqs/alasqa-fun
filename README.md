# alasqa-fun

Personal business card website of **Alasqa**, a backend web developer.

**Live:** [alasqa.fun](https://alasqa.fun)

## Stack

Plain HTML and CSS: no build step, no dependencies. Fonts are self-hosted.

## Run locally

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Structure

```
index.html   page markup
css/         reset, base styles and the links panel
fonts/       Unbounded, Manrope and JetBrains Mono (woff2) with their licenses
images/      avatar, background and favicons
```

## Deploy

Every push to `main` is published automatically with GitHub Pages.

## Credits

- Project structure inspired by [LittleLink](https://github.com/sethcottle/littlelink).
- Fonts are licensed under the [SIL Open Font License 1.1](fonts/LICENSES).

## License

Code is released under the [MIT License](LICENSE).
