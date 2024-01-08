# _Carmen Nova_ HTML Representation

This directory contains code to render the HTML version of Carmen Nova from TEI XML using [CETEIcean](https://github.com/TEIC/CETEIcean/).

## Usage

Launch your preferred local web server from the project root directory (`..` from here).

For example, using Python:

```bash
python -m http.server
```

Then, navigate to the `web/` directory in your browser, e.g. http://localhost:8000/web/.

This development mode is automatically recognised and will load your local copy of the TEI file.
You can ensure you are running in development mode by checking your browser’s development console. You should see a message like:

```
🚧 Development mode: Using local XML file.
```

## Development

When making changes, ensure that you are using the [Prettier formatter](https://prettier.io/) as configured in `web/.prettierrc`.
Please format your code before committing.

Install dependencies with:

```bash
npm install
```

Format code with:

```bash
npx prettier . --write
```

It is recommended to configure your editor to automatically format on save.
