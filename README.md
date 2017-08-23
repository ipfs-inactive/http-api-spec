# PSA - This specification is out of date, please use [API Docs](https://ipfs.io/docs/api/) for a up to date reference.

We working towards generating Apiary compliant HTTP API documentation automatically and tests the different implementations to see if they are compliant. Until that happens, we have a docs generation tool that grabs the endpoints from go-ipfs and generates the documentation.

The tool is [http-api-docs](https://github.com/ipfs/http-api-docs) and generated docs are stored in the [Website Repo](https://github.com/ipfs/website/blob/master/content/docs/api.md)

---------------------------------------------------------------------------
---------------------------------------------------------------------------

# Apiary IPFS HTTP API description

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](http://ipn.io)
[![](https://img.shields.io/badge/project-IPFS-blue.svg?style=flat-square)](http://ipfs.io/)
[![](https://img.shields.io/badge/freenode-%23ipfs-blue.svg?style=flat-square)](http://webchat.freenode.net/?channels=%23ipfs)
[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

> Apiary IPFS HTTP API description

[Live API](http://docs.ipfs.apiary.io/#)

This is the IPFS HTTP API spec, currently based on using the [go-ipfs](https://github.com/ipfs/go-ipfs) implementation. You can find the official API spec at [the specs repo](https://github.com/ipfs/specs/tree/master/public-api).

## Usage

Go look at the [Live API](http://docs.ipfs.apiary.io/#), or check out the [apiary.apib](apiary.apib) source in this repository. If you would like to run the `curl` commands, please have an `ipfs daemon` running. For more on that, go to [go-ipfs](https://github.com/ipfs/go-ipfs).

## Contribute

Feel free to join in. All welcome. Open an [issue](https://github.com/ipfs/http-api-spec/issues)!

This repository falls under the IPFS [Code of Conduct](https://github.com/ipfs/community/blob/master/code-of-conduct.md).

### Want to hack on IPFS?

[![](https://cdn.rawgit.com/jbenet/contribute-ipfs-gif/master/img/contribute.gif)](https://github.com/ipfs/community/blob/master/contributing.md)

## License

MIT
