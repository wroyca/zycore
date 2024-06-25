# libzycore-tests - An executable

The `libzycore-tests` executable is a <SUMMARY-OF-FUNCTIONALITY>.

Note that the `libzycore-tests` executable in this package provides `build2` metadata.


## Usage

To start using `libzycore-tests` in your project, add the following build-time
`depends` value to your `manifest`, adjusting the version constraint as
appropriate:

```
depends: * libzycore-tests ^<VERSION>
```

Then import the executable in your `buildfile`:

```
import! [metadata] <TARGET> = libzycore-tests%exe{<TARGET>}
```


## Importable targets

This package provides the following importable targets:

```
exe{<TARGET>}
```

<DESCRIPTION-OF-IMPORTABLE-TARGETS>


## Configuration variables

This package provides the following configuration variables:

```
[bool] config.libzycore_tests.<VARIABLE> ?= false
```

<DESCRIPTION-OF-CONFIG-VARIABLES>
