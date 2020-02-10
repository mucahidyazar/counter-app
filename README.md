<p align="center">
 <img src="https://img.shields.io/badge/License-MIT-blue.svg">
  <a href="#"><img src="https://img.shields.io/badge/all_contributors-31-orange.svg?style=flat-square)"></a>
   <a href="#"><img src="https://travis-ci.org/taniarascia/takenote.svg?branch=master"></a>
</p>

<!-- > **Warning**: TakeNote is still in active development. You can visit [takenote.dev](https://takenote.dev) to see the work in progress, but your account and the notes you create are **temporary** will not be persisted. All data will be lost once GitHub integration is complete. -->

<div align="center">
<img src="./public/assets/img/counter-app.gif">
</div>

### Simple

TakeNote was made by developers for developers - a simple, plain-text note-taking app for the web with Markdown support. What you see is what you paste. No WYSIWIG, no formatting pasted from the web, and no features you don't need or want.

### Organized

Drag-and-drop notes into categories, instantly search through notes, and pin your favorites to the top.

### Beautiful

Beautiful, clean design with light and dark themes.

### Sync to GitHub

In progress!

## Reviews

> _"I think the lack of extra crap is a feature."_ — Craig Lam

## Setup

### Install

```bash
git clone git@github.com:taniarascia/takenote
cd takenote
npm i
```

### Development

In the development environment, an Express server is running on port `5000` to handle all API calls, and a hot Webpack dev server is running on port `3000` for the React front end. To run both of these servers concurrently, run the `dev` command.

```bash
# Run client and server concurrently
npm run dev
```

Go to `localhost:3000` to view the app.

API requests will be proxied to port `5000` automatically.

### Production

In production, the React app is built, and Express redirects all incoming requests to the `dist` directory on port `5000`.

```bash
# Build client for production and start server
npm run build && npm run start
```

Go to `localhost:5000` to view the app.

### Seed data

Not yet

## Testing

Not yet

## Contributing

TakeNote is an open source project, and contributions of any kind are welcome! Open issues, bugs, and enhancements are all listed on the [issues](https://github.com/taniarascia/takenote/issues) tab and labeled accordingly. Feel free to open bug tickets and make feature requests. Easy bugs and features will be tagged with the `good first issue` label.

The project is written in TypeScript, React and Redux. TypeScript is set to strict mode, with no implicit any allowed. The formatting style for the project is set by Prettier.

## Acknowledgements

- A big thank you to [Mucahid Yazar](https://dkbock.com/) for logo design.

## Author

- [Mucahid Yazar](https://github.com/mucahidyazar)

## License

This project is open source and available under the [MIT License](LICENSE).
