# MG4
## Devlog
FloatAnimation is what makes the food bob. Start() sets _timer to _switchSpeed so it has something to count down from and Update() runs every frame and moves the food up if _up is true or down if it’s false. It also subtracts Time.deltaTime from _timer, and when it hits 0 it resets and flips _up, so the food just keeps switching between going up and down.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)