# hls-js-player-loader
Wrapper for loading [HLS.js player](https://github.com/video-dev/hls.js/). Inspired by [youtube-iframe](https://github.com/Prinzhorn/youtube-iframe).

# Install
```
npm install hls-js-player-loader
```
```
yarn add hls-js-player-loader
```

# Usage
```
import HlsJsPlayerLoader from 'hls-js-player-loader';

HlsJsPlayerLoader.load((Hls) => {
    const hls = new Hls();
}, 'latest');
```

