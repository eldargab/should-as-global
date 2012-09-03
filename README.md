# should-as-global

It just requires [should](https://github.com/visionmedia/should.js) and assigns
it to a global var `assert`. So we can pass `--require should-as-global` to
[mocha](https://github.com/visionmedia/mocha) and have `assert.exist()` and
friends automatically available. Note, that you still should specify
[should](https://github.com/visionmedia/should.js) as a dev dependency.

## Installation

Via npm

```
npm install should-as-global
```

## License

MIT