# Video player

This player has the functionality to zoom-in and zoom-out with the mouse wheel and slider.

## Installation

Use the package manager [npm](#) to install react-zoom-pan-pinch.

```bash
npm i react-zoom-pan-pinch
```

## react-zoom-pan-pinch

```python
import { TransformWrapper, TransformComponent } from "react-zoom-pan-pinch";

<TransformWrapper>
   <TransformComponent>
      <video id="video" ref={videoEl} src={videolink} onLoadedMetadata={initializeVideo} muted autoPlay></video>
   </TransformComponent>
</TransformWrapper>

```
## How to use video player
Just save it as a component in your code then,

```python
import VideoPlayerNew from './VideoPlayerNew';

<VideoPlayerNew src="http://upload.wikimedia.org/wikipedia/commons/7/79/Big_Buck_Bunny_small.ogv"/>

```
## Contributing
To build player in js:

https://freshman.tech/custom-html5-video/

To review library:

https://www.npmjs.com/package/react-zoom-pan-pinch

For zoom using input type range (slider):

https://codesandbox.io/s/loving-mccarthy-2ejsz?file=/src/App.js:0-2852
