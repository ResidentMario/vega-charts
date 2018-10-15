# vega-charts

This is a repository that hangs out in a folder on my Desktop which I use for buiding Vega charts locally.

## Usage

To install this code, clone the package locally, then run `npm install`.

To generate a chart based on a Vega spec, say, `example.json`, run the following command:

```bash
npm run-script vg2png -- example.json example.png
```

You can view the result in any image editor. From the command line it's simplest to just run `open example.png`.
