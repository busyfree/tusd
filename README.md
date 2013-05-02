# tusd

tusd is the official reference implementation of the [tus resumable upload
protocol](http://www.tus.io/protocols/resumable-upload.html).

This means it is meant for client authors to verify their implementations as
well as server authors who may look at it for inspiration.

In the future tusd may be extended with additional functionality to make it
suitable as a standalone production upload server, but for now this is not a
priority.

**Protocol version:** 0.1 (upgrade to 0.2 will be ready soon)

## Getting started

**Requirements:**

* [Go 1.0](http://golang.org/doc/install)

**Installing tusd:**

Clone the git repository and `cd` into it.

```bash
git clone git@github.com:tus/tusd.git
cd tusd
```

**Running tusd:**

Run it with go:

```bash
go run src/cmd/tusd/*.go
```

## License

This project is licensed under the MIT license, see `LICENSE.txt`.
