*This repository is a mirror of the [component](http://component.io) module [component/overlay](http://github.com/component/overlay). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-overlay`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# Overlay

  Page overlay component.

## Installation

```
$ component install component/overlay
```

## API

### overlay([options|element])

  Returns a new `Overlay`.

  Options:

  - `closable`: whether or not a user may click the overlay to close [__false__]
  - `target`: target element to overlay [body]

### Overlay#show()

  Show the overlay.

### Overlay#hide()

  Hide the overlay.

## Events

  - `show` when the overlay is shown
  - `hide` when the overlay is hidden
  - `close` when the overlay is removed (follows hide normally)


## License

  MIT
