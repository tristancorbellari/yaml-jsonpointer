# Fork information

This is a fork of the yaml-jsonpointer package which primarily serves one purpose: to add wildcards to expressions.

Using the FindAll() function, one can now use a wildcard "*" to match all child nodes found. For an example, see the 'ExampleFindAll_wildcard' test case [here](yptr_test.go#L80).

**It should be noted that this repository is no longer actively maintained by VMware, so tread with caution about using this package in a production environment.** I mostly just created this fork with the intention of solving a very specific problem to be used in another project.

#

[![](https://godoc.org/github.com/github.com/tristancorbellari/yaml-jsonpointer?status.svg)](https://pkg.go.dev/github.com/tristancorbellari/yaml-jsonpointer?tab=doc)
[![Go Report Card](https://goreportcard.com/badge/github.com/tristancorbellari/yaml-jsonpointer)](https://goreportcard.com/report/github.com/tristancorbellari/yaml-jsonpointer)
![](https://github.com/tristancorbellari/yaml-jsonpointer/workflows/CI/badge.svg)


# yaml-jsonpointer

Package yptr is a Go package with a JSONPointer implementation that can walk though a yaml.Node tree.

## Documentation

Read full doc on the [Go package documentation page](https://pkg.go.dev/github.com/tristancorbellari/yaml-jsonpointer?tab=doc).

## Contributing

The yaml-jsonpointer project team welcomes contributions from the community. Before you start working with yaml-jsonpointer, please
read our [Developer Certificate of Origin](https://cla.vmware.com/dco). All contributions to this repository must be
signed as described on that page. Your signature certifies that you wrote the patch or have the right to pass it on
as an open-source patch. For more detailed information, refer to [CONTRIBUTING.md](CONTRIBUTING.md).

## License

yaml-jsonpointer is available under the [BSD-2 license](LICENSE).
