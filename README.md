# &lt;soundcloud-player&gt;

[Web Component](http://www.w3.org/TR/components-intro/) wrapper for SoundCloud player using [Polymer](http://www.polymer-project.org/).

## [Demo](http://6.github.io/soundcloud-embed-polymer/)

## Usage

1. Import Web Components polyfill:

  ```html
  <script src="bower_components/platform/platform.js"></script>
  <link rel="import" href="bower_components/polymer/polymer.html">
  ```

2. Import Custom Element:

  ```html
  <link rel="import" href="elements/soundcloud-player.html">
  ```

3. Start using it!

  ```html
  <soundcloud-player track-id="126873817"></soundcloud-player>
  ```

## Options

Attribute      | Default  | Description
---            | ---      | ---
`track-id`     | None     | The ID of the SoundCloud track
`playlist-id`  | None     | The ID of the SoundCloud playlist
`color`        | `ff6600` | The HEX color of the player controls
`auto-play`    | `false`  | Whether or not to start playing song automatically
`show-artwork` | `true`   | Whether or not to show album picture

Note that either `track-id` or `playlist-id` must be provided.

## License

[MIT License](http://opensource.org/licenses/MIT)
