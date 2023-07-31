# dcp-docs

[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

DCP&#39;s documentation at <https://docs.dcp.dev>

The repo has just the built HTML hosted at <https://docs.dcp.dev>. The build
process requires access to closed source code to autogenerate the API
documentation with [`sphinx-js`](https://github.com/mozilla/sphinx-js). In the
future, we'll open source the source code for the docs, while using secrets in
the CI workflow to handle automating the build of the website.

## Install

Clone the repo.

```console
git clone https://github.com/Distributive-Network/dcp-docs.git
```

## Usage

Serve the files using a web server. For example,

```console
npx --yes serve build
```

## Maintainers

[@bryan-hoang](https://github.com/bryan-hoang)

## Contributing

If you find an issue with the docs, please file an issue!

See [`CONTRIBUTING.md`](./CONTRIBUTING.md) for more information.

Small note: If editing the README, please conform to the
[standard-readme](https://github.com/RichardLitt/standard-readme) specification.

## License

UNLICENSED.
