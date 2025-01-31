# 3D tween (experimental)

<img src="https://asset-resources.gdevelop.io/public-resources/Icons/30bc03f9cf5f2f42960246a605352a6937ae6b603f0177396a83193849a4724a_tennis-ball.svg" class="extension-icon"></img>
Smoothly animate scale and rotation of 3d models.

**Authors and contributors** to this community extension: [D8H](https://gd.games/D8H).

!!! warning
    This is an extension made by a community member — but not reviewed
    by the GDevelop extension team. As such, we can't guarantee it
    meets all the quality standards of official extensions. In case of
    doubt, contact the author to know more about what the extension
    does or inspect its content before using it.

---

Change models proportions and orientation over time to make smooth animations.

!!! tip
    Learn [how to install new extensions](/gdevelop5/extensions/search) by following a step-by-step guide.

## Actions

**Scale volume**  
Change the scale volume.

**Stretch on Y axis**  
Change the stretch on Y axis. The object volume is conseved. A stretch of 2 make the object apear 2 time longer on Y in proportion to the dimension on X and Z.

**Stretch on Z axis**  
Change the stretch on Z axis. The object volume is conseved. A stretch of 2 make the object apear 2 time longer on Z in proportion to the dimension on X and Y.

## Conditions

**Scale volume**  
Compare the scale volume.

**Stretch on Y axis**  
Compare the stretch on Y axis. The object volume is conseved. A stretch of 2 make the object apear 2 time longer on Y in proportion to the dimension on X and Z.

**Stretch on Z axis**  
Compare the stretch on Z axis. The object volume is conseved. A stretch of 2 make the object apear 2 time longer on Z in proportion to the dimension on X and Y.

## Expressions

| Expression | Description |  |
|-----|-----|-----|
| `Tween3D::ScaleVolume(object)` | Return the scale volume. ||
| | _👾 Object_ | Object |
| `Tween3D::StretchY(object)` | Return the stretch on Y axis. The object volume is conseved. A stretch of 2 make the object apear 2 time longer on Y in proportion to the dimension on X and Z. ||
| | _👾 Object_ | Object |
| `Tween3D::StretchZ(object)` | Return the stretch on Z axis. The object volume is conseved. A stretch of 2 make the object apear 2 time longer on Z in proportion to the dimension on X and Y. ||
| | _👾 Object_ | Object |

## 3D tween (experimental) 

Smoothly animate scale and rotation of 3d models. 

### Behavior actions

**Pause a tween**  
Pause the running tween animation.

**Remove a tween**  
Remove the tween animation from the object.

**Resume a tween**  
Resume the tween animation.

**Stop a tween**  
Stop the running tween animation.

**Tween rotation X**  
Tweens an object rotation X from its current value to a new one.

**Tween rotation Y**  
Tweens an object rotation Y from its current value to a new one.

**Tween scale volume**  
Tweens an object scale volume from its current value to a new one. The scale volume can never be 0 or less.

**Tween stretch Y**  
Tweens an object stretch Y from its current value to a new one. The stretch can never be 0 or less.

**Tween stretch Z**  
Tweens an object stretch Z from its current value to a new one. The stretch can never be 0 or less.

### Behavior conditions

**Tween exists**  
Check if the tween animation exists.

**Tween finished playing**  
Check if the tween animation has finished playing.

**Tween is playing**  
Check if the tween animation is currently playing.

**Progress of a tween**  
Compare the progress of a tween (between 0.0 and 1.0).

### Behavior expressions

| Expression | Description |  |
|-----|-----|-----|
| `Object.Tween3D::Progress(string)` | Return the progress of a tween (between 0.0 and 1.0). ||
| | _🔤 Name (String)_ | Tween identifier |

## 3D wobble 

Squash and stretch a 3D model in loop. 

### Behavior actions

**Cycle duration**  
Change the cycle duration of the object.

**Maximum scale volume**  
Change the maximum scale volume of the object.

**Minimum scale volume**  
Change the minimum scale volume of the object.

**Scale cycle offset**  
Change the scale cycle offset of the object.

**Maximum stretch**  
Change the maximum stretch of the object.

**Minimum stretch**  
Change the minimum stretch of the object.

**Stretch cycle offset**  
Change the stretch cycle offset of the object.

**Tween maximum scale volume**  
Tweens the maximum scale volume from its current value to a new one. The scale volume can never be 0 or less.

**Tween minimum scale volume**  
Tweens the minimum scale volume from its current value to a new one. The scale volume can never be 0 or less.

### Behavior conditions

**Cycle duration**  
Compare the cycle duration of the object.

**Maximum scale volume**  
Compare the maximum scale volume of the object.

**Minimum scale volume**  
Compare the minimum scale volume of the object.

**Scale cycle offset**  
Compare the scale cycle offset of the object.

**Maximum stretch**  
Compare the maximum stretch of the object.

**Minimum stretch**  
Compare the minimum stretch of the object.

**Stretch cycle offset**  
Compare the stretch cycle offset of the object.

### Behavior expressions

| Expression | Description |  |
|-----|-----|-----|
| `Object.Wobble::PeriodDuration()` | Return the cycle duration of the object. ||
| `Object.Wobble::ScaleMax()` | Return the maximum scale volume of the object. ||
| `Object.Wobble::ScaleMin()` | Return the minimum scale volume of the object. ||
| `Object.Wobble::ScalePeriodOffset()` | Return the scale cycle offset of the object. ||
| `Object.Wobble::StretchMax()` | Return the maximum stretch of the object. ||
| `Object.Wobble::StretchMin()` | Return the minimum stretch of the object. ||
| `Object.Wobble::StretchPeriodOffset()` | Return the stretch cycle offset of the object. ||

---

*This page is an auto-generated reference page about the **3D tween (experimental)** extension, made by the community of [GDevelop, the open-source, cross-platform game engine designed for everyone](https://gdevelop.io/).* Learn more about [all GDevelop community-made extensions here](/gdevelop5/extensions).