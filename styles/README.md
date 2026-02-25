### `style.css`

Recommended for clean digital style.

```bash
--css styles/style.css
--css https://carleslc.me/message/styles/style.css
```

Example: [https://carleslc.me/message/example/gantt](https://carleslc.me/message/example/gantt)

### `style-serif.css`

Use for serif typography (more formal, for letters).

```bash
--css styles/style-serif.css
--css https://carleslc.me/message/styles/style-serif.css
```

Example: [https://carleslc.me/message/example/gantt-serif](https://carleslc.me/message/example/gantt-serif)

```bash
pandoc example/gantt.md -o example/gantt-serif.html --css styles/style-serif.css --standalone --embed-resources --metadata title="Diagrama de Gantt (Serif)"
```
