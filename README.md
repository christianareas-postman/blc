# Links

The project uses [`linkinator`](https://github.com/JustinBeckwith/linkinator#readme) to find broken links.

## Install

```bash
gh repo clone christianareas-postman/links
npm i
cd links
```
## Find links that return an error

The following command finds links within [http://localhost:3000](http://localhost:3000). Make sure you start your local server (usually, `npm run dev`).

```bash
npm run check-links:local
```
