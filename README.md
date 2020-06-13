# node-speaker
```
[../deps/mpg123/src/output/coreaudio.c:81] warning: Didn't have any audio data in callback (buffer underflow)
[../deps/mpg123/src/output/coreaudio.c:81] warning: Didn't have any audio data in callback (buffer underflow)
[../deps/mpg123/src/output/coreaudio.c:81] warning: Didn't have any audio data in callback (buffer underflow)
[../deps/mpg123/src/output/coreaudio.c:81] warning: Didn't have any audio data in callback (buffer underflow)
[../deps/mpg123/src/output/coreaudio.c:81] warning: Didn't have any audio data in callback (buffer underflow)
```

If your terminal looks like that when using [node-speaker](https://github.com/TooTallNate/node-speaker), and you're on MacOs, this fork should fix it.

This is exactly the same as the [source](https://github.com/TooTallNate/node-speaker), except
I commented out an annoying warning in the libmpg123 code in `coreaudio.c`, which handles audio output for MacOS using Apple's API for it.