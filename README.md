# anybool

> Tricky and fun utilities for Go programs.

AnyBool is a small utility with an interface for simplifying organization of defaults, settings, and constants in Go programs.

---

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/skeptycal/anybool/Go) ![Codecov](https://img.shields.io/codecov/c/github/skeptycal/anybool)

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v1.4%20adopted-ff69b4.svg)](code-of-conduct.md)

![Twitter Follow](https://img.shields.io/twitter/follow/skeptycal.svg?label=%40skeptycal&style=social) ![GitHub followers](https://img.shields.io/github/followers/skeptycal.svg?style=social)

---

## Getting Started

### Prerequisites

-   [Go](https://golang.org/)
-   [Git](https://git-scm.com/)
-   [GitHub CLI](https://cli.github.com/)
-

Developed with $( go version; ). Go is _extremely_ backwards compatible and semver stable. Nearly any v1.x should work fine.

---

### Installation

To use this repo as a template for your own project:

```sh
gh repo create -y --public --template "https://github.com/skeptycal/anybool"
```

Clone this repo to test and contribute:

```bash
# add repo to $GOPATH (xxxxxx is your computer login username)
go get github.com/xxxxxx/anybool

cd ${GOPATH}/src/github.com/xxxxxx/anybool

# test results and coverage info
./go.test.sh

# install as a utility package
go install

```

Use the [Issues][issues] and [PR][pr] templates on the GitHub repo page to contribute.

---

### Basic Usage

> This is a copy of the example script available in the `cmd/example/anybool` folder:

```go
package main

import "github.com/skeptycal/anybool"

func main() {
    anybool.Example()
}

```

To try it out:

```sh
# change to the sample folder
cd cmd/example/anybool

# run the main.go program
go run ./main.go

# to compile as an executable
go build
```

---

## Code of Conduct and Contributing

Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us. Please read the [Code of Conduct](CODE_OF_CONDUCT.md) for details before submitting anything.

---

## Versioning

We use SemVer for versioning. For the versions available, see the tags on this repository.

---

## Contributors and Inspiration

-   Michael Treanor ([GitHub][github] / [Twitter][twitter]) - Initial work, updates, maintainer
-   [Francesc Campoy][campoy] - Inspiration and great YouTube videos!

See also the list of contributors who participated in this project.

---

## License

Licensed under the MIT <https://opensource.org/licenses/MIT> - see the [LICENSE](LICENSE) file for details.

[twitter]: (https://www.twitter.com/skeptycal)
[github]: (https://github.com/skeptycal)
[campoy]: (https://github.com/campoy)
[fatih]: (https://github.com/fatih/color)
[issues]: (https://github.com/skeptycal/anybool/issues)
[pr]: (https://github.com/skeptycal/anybool/pulls)
