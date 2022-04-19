{
  "assets": [
      { "id": "cityModel", "src": "https://cdn.aframe.io/test-models/models/glTF-2.0/virtualcity/VC.gltf"}
  ],
  "entities": [
      { "id":"city", "gltf-model": "#cityModel"}
  ],
  "embeds":[
    { "id":"video", "position": { "x": 3, "y": 4, "z": 19 }, "rotation": { "x": 0, "y": 180, "z": 0}, "scale": 45, "html": "<video autoplay loop='true' crossorigin='anonymous' src='https://xrpanet.s3-us-west-1.amazonaws.com/proudmary.mp4' type='video/mp4' playsinline webkit-playsinline style='position: absolute;z-index: -1000;'></video>" }
  ]
}
