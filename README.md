Single sprite resource file convert to godot4.x AtlasTexture's tres

1. Install:
```
cd free-tex-packer-godot
npm i
```

2. Modify the configuration of the index.js file according to the actual situation.
demo:
```javascript
const IMAGES = [
	"./test/bkgard.png",
	"./test/bkblue.png",
	"./test/bkfall.png",
];
const TEXTURE_NAME = "test_atlas";
```

3. Use:
```
npm run pack
```

4. Copy or move output files to godot project's path after finished. (default path: res://assets/textures/)
