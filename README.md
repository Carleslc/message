_Install once. Write your text. Build it. Publish with [Netlify Drop](https://app.netlify.com/drop). Share._


[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/C0C2VFGD)

## Install

Only the first time.

- Install [Pandoc](https://pandoc.org/installing.html) converter.
- Download or clone [this repository](https://github.com/Carleslc/message).

## Build

```bash
mkdir example
pandoc message.md -o example/index.html --css style.css --self-contained --metadata title="Ejemplo"
```

## Deploy

- **Recommended**: Use an online service like [Netlify Drop](https://app.netlify.com/drop) to publish your site for free.

Other options:

- Host in your own server.
- Host for free with a GitHub repository using [GitHub Pages](https://pages.github.com/) (like this page).
- Use a cloud service like [Dropbox](https://www.dropbox.com/) or [pCloud](https://www.pcloud.com/) to generate an online URL.

## Example

- [https://carleslc.me/message/example/](https://carleslc.me/message/example/) using [GitHub Pages](https://pages.github.com/).
- [https://eager-elion-4ce525.netlify.com/](https://eager-elion-4ce525.netlify.com/) using [Netlify](https://app.netlify.com/drop).
