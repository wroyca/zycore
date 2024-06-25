# libzycore - A C library

The `libzycore` C library provides platform-independent types, macros, and fallbacks for environments without libc.

## Usage

To start using `libzycore` in your project, add the following `depends` value to your `manifest`, adjusting the version constraint as appropriate:

```
depends: libzycore ^1.5.0
```

Then import the library in your `buildfile`:

```
import libs = libzycore%lib{zycore}
```
