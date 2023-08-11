<!doctype HTML>
<html>
<script src="https://aframe.io/releases/0.9.2/aframe.min.js"></script>
<script src="https://raw.githack.com/jeromeetienne/AR.js/2.0.5/aframe/build/aframe-ar.js"></script>

<body style='margin : 0px; overflow: scroll;'>
  <a-assets>
    <video src="http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/BigBuckBunny.mp4"></video>
    <a-sound src="/Macintosh HD/Users/andybohmfalk/Music/Music/Media/Music/Tentacles/Dance/01 Bubbles.mp3" id="sound"></a-sound>
  </a-assets>
  <a-scene embedded arjs>
   <a-marker preset='hiro'>
       <a-plane src="http://127.0.0.1:5500/windows95.html" depth="2" width="4" height="2" rotation="-90 -90 90"></a-plane>
      </a-marker>
      <a-entity raycaster="objects: .interactable" cursor="fuse: true; fuseTimeout: 500" position="0 0 -1"></a-entity>
      <a-entity camera></a-entity>
    </a-scene>
    <script>
    </script>
    
    
  </a-scene>
</body>
</html>
