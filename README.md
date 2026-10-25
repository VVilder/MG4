# MG4
## Devlog
FloatAnimation makes the food bob up and down. In Start(), _timer gets set to _switchSpeed, so it starts counting from there. Then Update() runs every frame. If _up is true it moves the food up, and if it's false it moves it down. Every frame _timer also goes down by Time.deltaTime, and once it hits 0 it resets back to _switchSpeed and flips _up to the opposite. So the food goes up for a bit, then down for a bit, and keeps switching.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)