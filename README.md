# swirl-ssv

> This is a package for swirl short videos which can be installed and used in react projects.

[![NPM](https://img.shields.io/npm/v/swirl-ssv.svg)](https://www.npmjs.com/package/swirl-ssv) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install  swirl-short-videos --force
```

## Usage

```jsx
import React from 'react'
import { SwirlShortVideos } from 'swirl-short-videos';

const YourComponent = () => {
    return (
        <SwirlShortVideos dataCode="your-data-code" dataPlalistCode="your-playlist-code" />
    )
}

export default YourComponent
```

## Add this link tag globally in public/index.html
```jsx
<link rel="stylesheet" href="https://apigoswirl.com/short_video/react/v12/swirl-short-videos-v1.min.css">
```
```jsx
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your React App</title>
   <link rel="stylesheet" href="https://apigoswirl.com/short_video/react/v12/swir-short-videos-v1.min.css">
</head>
<body>
    <noscript>You need to enable JavaScript to run this app.</noscript>
    <div id="root"></div>
</body>
</html>
```

## License

MIT © [goswirl-github](https://github.com/SwirlAdmin/react-short-video-plugin.git)
