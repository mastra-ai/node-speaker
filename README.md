# node-speaker

This is a republishing of [JasonBenn's fork](https://github.com/JasonBenn/node-speaker) of the original [TooTallNate/node-speaker](https://github.com/TooTallNate/node-speaker) package. JasonBenn's fork addressed the following CoreAudio buffer underflow errors, but was never published to npm:

```
[../deps/mpg123/src/output/coreaudio.c:81] warning: Didn't have any audio data in callback (buffer underflow)
[../deps/mpg123/src/output/coreaudio.c:81] warning: Didn't have any audio data in callback (buffer underflow)
[../deps/mpg123/src/output/coreaudio.c:81] warning: Didn't have any audio data in callback (buffer underflow)
[../deps/mpg123/src/output/coreaudio.c:81] warning: Didn't have any audio data in callback (buffer underflow)
[../deps/mpg123/src/output/coreaudio.c:81] warning: Didn't have any audio data in callback (buffer underflow)
```

## Why This Package

This package exists to make JasonBenn's fixes available on npm, as the original fork was never published. No additional modifications have been made to JasonBenn's code. This package is primarily used for Mastra's voice demos.

## License

This project is licensed under dual MIT and LGPL-2.1-only licenses, respecting the original author's license terms.

## Credits

- Original author: [Nathan Rajlich](https://github.com/TooTallNate)
- CoreAudio fixes: [Jason Benn](https://github.com/JasonBenn)
- npm publishing: [Mastra AI](https://github.com/mastra-ai)
