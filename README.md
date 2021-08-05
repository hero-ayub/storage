# fosite-storage-mongo
[![Coverage Status](https://coveralls.io/repos/github/matthewhartstonge/storage/badge.svg?branch=main)](https://coveralls.io/github/matthewhartstonge/storage?branch=main) [![Go Report Card](https://goreportcard.com/badge/github.com/matthewhartstonge/storage)](https://goreportcard.com/report/github.com/matthewhartstonge/storage) [![Build Status](https://travis-ci.com/matthewhartstonge/storage.svg?branch=main)](https://travis-ci.com/matthewhartstonge/storage) [![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fmatthewhartstonge%2Fstorage.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fmatthewhartstonge%2Fstorage?ref=badge_shield)

fosite-storage-mongo provides a native Go based [Mongo backed database storage][mongo-driver] 
that conforms to *all the interfaces!* required by [fosite][fosite].

**Table of contents**
- [Compatibility](#compatibility)
- [Development](#development)
    - [Testing](#testing)
- [Examples](#examples)
- [Disclaimer](#disclaimer)

## Compatibility
The following table lists the compatible versions of fosite-storage-mongo with
fosite. If you are currently using this in production, it would be awesome to 
know what versions you are successfully paired with.

| storage version | minimum fosite version | maximum fosite version | 
|----------------:|-----------------------:|-----------------------:|
|       `v0.26.X` |              `v0.32.X` |              `v0.34.X` |
|       `v0.25.X` |              `v0.32.X` |              `v0.34.X` |
|       `v0.24.X` |              `v0.32.X` |              `v0.32.X` |
|       `v0.22.X` |              `v0.32.X` |              `v0.32.X` |
|       `v0.21.X` |              `v0.31.X` |              `v0.31.X` |

## Development
To start hacking:
* Install [Go][Go] >1.14
    * Use Go modules!
    * `go build` successfully!

### Testing
Use `go test ./...` to discover heinous crimes against coding!

## Examples
For a quick start check out the following examples based on the `fosite-example`
repo for reference:

- [MongoDB Example](./examples/mongo)

## Disclaimer
* We are currently using this project in house with Storage `v0.26.x` and Fosite
  `v0.32.x` with good success.
* If you are able to provide help in keeping storage up to date, feel free to 
    raise a github issue and discuss where you are able/willing to help. I'm 
    always happy to review PRs and merge code in :ok_hand:

## Licensing
storage is under the Apache 2.0 License.

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fmatthewhartstonge%2Fstorage.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fmatthewhartstonge%2Fstorage?ref=badge_large)

[//]: #
    [mongo-driver]: <https://github.com/mongodb/mongo-go-driver>
    [dep]: <https://github.com/golang/dep>
    [go]: <https://golang.org/dl/>
    [fosite]: <https://github.com/ory/fosite> 
    [hydra]: <https://github.com/ory/hydra>
    [fosite-example-server]: <https://github.com/ory/fosite-example/blob/master/authorizationserver/oauth2.go>
