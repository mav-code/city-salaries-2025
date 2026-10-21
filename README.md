# First steps into NYC's best-paid public jobs

84 ways to start a City of New York career, covering every job title that paid someone at least
$200,000 in fiscal-year 2025. Pay figures come from the NYC Office of Payroll Administration's
[Citywide Payroll Data (Fiscal Year)](https://data.cityofnewyork.us/d/k397-673e).

A static page built with Eleventy. The root `index.html` is the Nunjucks page template; its header and footer are in `_includes/`. The card data remains embedded in `index.html` as `const DATA = [...]`.

## Working Locally

Requires Node.js 18 or newer.

```sh
npm install
npm start
```

Eleventy serves the site locally and watches for changes. To generate the deployable static site in `_site/`, run:

```sh
npm run build
```

For Vercel, use `npm run build` as the build command and `_site` as the output directory.

## License

MIT (see `LICENSE`). The payroll figures are NYC Open Data, published by the City of New York.
