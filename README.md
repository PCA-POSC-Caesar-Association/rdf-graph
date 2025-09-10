# rdf-graph

An open source library for visualizing RDF as a graph network.

## Packages

| Package  | Version | Description |
| ------------- | ------------- | ------------- |
| [@posccaesar/rdf-graph](libs/core/) | [![core version](https://img.shields.io/npm/v/@posccaesar/rdf-graph)](libs/core/CHANGELOG.md) | Core library |
| [@posccaesar/rdf-graph-go](libs/go/) | [![go version](https://img.shields.io/npm/v/@posccaesar/rdf-graph-go)](libs/go/CHANGELOG.md) | GoJS UI Implementation |
| [@posccaesar/rdf-graph-cy](libs/cy/) | [![cy version](https://img.shields.io/npm/v/@posccaesar/rdf-graph-cy)](libs/cy/CHANGELOG.md) | Cytoscape.js UI Implementation |
| [@posccaesar/rdf-graph-fg3d](libs/fg3d/) | [![fg3d version](https://img.shields.io/npm/v/@posccaesar/rdf-graph-fg3d)](libs/fg3d/CHANGELOG.md) | 3D Force-Directed UI Implementation |

## Releasing a new version
1. Update package number for the relevant `package.json` located in a subfolder of the `libs` folder.
2. Create a PR with the changes.

## Demo

Spin up the development application for a demonstration of the library and different UI implementations/packages:

```sh
# Clone repo
git clone git@github.com:PCA-POSC-Caesar-Association/rdf-graph.git

# Install pnpm (if not already installed)
# https://pnpm.io/installation

# Install dependencies
cd rdf-graph && pnpm install

# Open development app
pnpm nx serve playground
```

## Contribute

See our [contributing guide](CONTRIBUTING.md).

## License

The core of this project is open source, but the [@posccaesar/rdf-graph-go](https://www.npmjs.com/package/@posccaesar/rdf-graph-go) package requires a GoJS [software license](https://gojs.net/latest/license.html).