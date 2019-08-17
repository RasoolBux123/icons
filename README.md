<p align="center">
  <a href="https://getbootstrap.com/">
    <img src="https://getbootstrap.com/docs/4.3/assets/brand/bootstrap-solid.svg" alt="Bootstrap logo" width="72" height="72">
  </a>
</p>

<h3 align="center">Bootstrap Icons</h3>

<p align="center">
  Official open source icon library for Bootstrap.
  <br>
  <a href="https://icons.getbootstrap.com/"><strong>Explore Bootstrap Icons »</strong></a>
  <br>
  <br>
  <a href="https://getbootstrap.com/docs/4.3/">Bootstrap</a>
  ·
  <a href="https://themes.getbootstrap.com/">Themes</a>
  ·
  <a href="https://blog.getbootstrap.com/">Blog</a>
</p>

## Install

Bootstrap Icons are packaged up and published to npm. We only include the processed SVGs in this package—it's up to you and your team to implement. [Read our docs](https://icons.getbootstrap.com/) at for usage instructions.

```
npm i bootstrap-icons --save
```

## Development

Clone the repo, install dependencies, and start the Hugo server locally.

```
git clone https://github.com/twbs/icons/
cd icons
npm i
npm start
```

Then open `http://localhost:4000` in your browser.

## Publishing

Docs are published via an npm script that builds the Hugo site, creates a temporary Git repo, and force pushes that to our `gh-pages` branch. This circumvents issues with GitHub Pages not working with Hugo.

```
npm run publish
```

## License

MIT

## Author

@mdo