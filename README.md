# MG4
## Devlog
Start() sets _timer to _switchSpeed. Each frame, Update() moves the food up if _up is true, or down if it is false. It uses Time.deltaTime to keep the movement consistent across different frame rates. Update() also counts down _timer. When the timer reaches zero, it resets and flips _up, making the food switch direction.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)