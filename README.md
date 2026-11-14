# JSON Buddy

A lightweight, beginner-friendly JSON formatter, validator and minifier. JSON Buddy runs entirely in your browser using plain HTML, CSS and JavaScript. It has no dependencies, build step, server or account requirement.

**GitHub Pages URL (after enabling Pages):** https://razorjetinz.github.io/json-buddy/

## Features

- Format JSON with 1-space, 2-space, 4-space or tab indentation.
- Validate JSON and display parsing errors with line and column details when available.
- Minify JSON by removing unnecessary whitespace.
- Open a local `.json` file.
- Copy formatted output to the clipboard.
- Download output as `formatted.json`.
- Switch between light and dark themes.
- Responsive layout for desktop and mobile.
- No network requests or third-party libraries. Your JSON is processed locally in your browser.

## Use it locally

1. Clone or download this repository.
2. Open `index.html` in a modern web browser.
3. Paste JSON or choose **Open file**.
4. Select **Format JSON**, **Minify** or **Validate**.

There is no installation or build command.

## Publish with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**.
4. Save the settings.

GitHub Pages will publish the app at:

https://razorjetinz.github.io/json-buddy/

The first deployment may take a few minutes. Check **Settings → Pages** for the deployment status.

## Project structure

```text
json-buddy/
├── index.html
├── README.md
├── LICENSE
└── .gitignore
```

## Privacy

JSON Buddy does not send your JSON to a server. The application has no analytics, tracking, external scripts or network API calls. Your data remains in the browser unless you choose to download or copy it.

## Contributing

Suggestions, bug reports and pull requests are welcome. For larger changes, open an issue first to discuss the proposed feature.

## License

Released under the MIT License. See [LICENSE](LICENSE).
