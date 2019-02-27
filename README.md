# dsc_extractor

Extractor dyld shared cache armxx.

# Compile

```sh
clang++ dyld/launch-cache/dsc_extractor.cpp dyld/launch-cache/dsc_iterator.cpp -o dsc_extractor
```

# Usage

```sh
./dsc_extractor dyld_shared_cache_arm64 arm64
```

# Tips

## Can't work on Xcode10

On Apple Developer Forums:[dyld_shared_cache_extract_dylibs failed](https://forums.developer.apple.com/thread/108917).

Error information:

```sh
$ ./dsc_extractor dyld_shared_cache_arm64 arm64
Error: dyld shared cache code signature for page 0 is incorrect.
dyld_shared_cache_extract_dylibs_progress() => -1
```

So the [dsc_extractor.bundle](https://github.com/madordie/dsc_extractor/blob/master/dsc_extractor.bundle) is the Xcode9 version.
