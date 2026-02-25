_Install once. Write your text. Build it. Publish with [Netlify Drop](https://app.netlify.com/drop). Share._

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/C0C2VFGD)

## Install

Only the first time.

- Install [Pandoc](https://pandoc.org/installing.html) converter.

- Download or [clone](https://github.com/Carleslc/message.git) this repository (optional).

## Build

```bash
pandoc example/message.md -o example/index.html --css styles/style.css --standalone --embed-resources --metadata title="Ejemplo"
```

You can also use styles directly from url: `--css https://carleslc.me/message/styles/style.css`

## Deploy

- **Recommended**: Use an online service like [Netlify Drop](https://app.netlify.com/drop) to publish your site for free.

Other options:

- Host in your own server.
- Host for free with a GitHub repository using [GitHub Pages](https://docs.github.com/pages) (like this page).
- Use a cloud service like [Dropbox](https://www.dropbox.com/) or [pCloud](https://www.pcloud.com/) to generate an online URL.

## [Examples](https://github.com/Carleslc/message/tree/master/example)

Using [Netlify Drop](https://app.netlify.com/drop):

- [https://message-example.netlify.app/](https://message-example.netlify.app/)
- [https://message-example.netlify.app/gantt](https://message-example.netlify.app/gantt)

Using [GitHub Pages](https://docs.github.com/pages):

- [https://carleslc.me/message/example/](https://carleslc.me/message/example/)
- [https://carleslc.me/message/example/gantt](https://carleslc.me/message/example/gantt)
