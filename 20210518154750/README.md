# `go get` is Now `go get -d` (Does Not Install)

Just ran across this in the Go documentation for `get` that really is
going to make a lot of Install sections of `README.md` files all over
just plain wrong. To be clear, `go get` will no longer be able to be
used to install Go commands (and even packages). This is fucking huge.
That is a *major* change of expectations from the entire community.

> The -d flag instructs get not to build or install packages. get will
  only update go.mod and download source code needed to build packages.
>
> Building and installing packages with get is deprecated. In a future
  release, the -d flag will be enabled by default, and 'go get' will be
  only be used to adjust dependencies of the current module. To install
  a package using dependencies from the current module, use 'go
  install'. To install a package ignoring the current module, use 'go
  install' with an @version suffix like "@latest" after each argument.

