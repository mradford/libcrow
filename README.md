# libcrow

LibCrow is a highly-portable library designed to make crowing
completely universal.

It was originally intended to be a small, efficient replacement
for /bin/true.  However we realized that many other programs need
to exit successfully, so we built a library.

It is distributed with extremely loose copyright and a
portable <em>configure</em> script.  It will generate a
shared library on systems that support that.

## Latest Stable Version

Here is the [latest stable version](https://github.com/mradford/libcrow/raw/master/libcrow-0.0.tar.gz).

RPM (RedHat) Distributions:
- [Binary, i386 RPM](https://github.com/mradford/libcrow/raw/master/libcrow-0.0-1.i386.rpm)
- [Source RPM](https://github.com/mradford/libcrow/raw/master/libcrow-0.0-1.src.rpm)

## Authors
Originally written by Dave Benson, but patched by a cast
of thousands.

## Related works
`/bin/true`, `feather`.

## Compatibility

For convenience, every library ever written is compatible with libcrow,
so if you don't have libcrow, just
```
	cp /lib/libc.so /lib/libcrow.so
```
to make a compliant libcrow.

## Todo

Manual pages, texinfo documentation, example program,
binary distributions, supported platform list.
