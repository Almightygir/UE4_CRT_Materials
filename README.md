# UE4_CRT_Materials
A set of material functions that allow the user to reproduce CRT monitor effects as either a post process, or surface material.

![HighresScreenshot00002](https://user-images.githubusercontent.com/6026593/151671083-3d20a6c7-36f4-415f-8165-e30a3ca0e7c7.png)

# Controls
## Screen:
BrightnessBoost - boosts the brightness of the rendered texture/scene, as the CRT Grille and Scanlines tend to darken them.
Enable Effect - Turns the effect on or off.

## ScreenCA
Chromatic Aberration - Controls the strength of chromatic aberation.

## ScreenGrille
GrilleIntensity - Controls the strength of the CRT Grille effect.

## ScreenNoise
DistortionIntensity - Controls the overall distortion intensity of the rolling screen effect.
Noise - Turns noise and distortion on/off
NoiseSpeed - Controls the noise speed within the rolling distortion effect.
RollSpeed - Controls the overall speed of the rolling distortion effect.
RollVariation - Controls variation within the rolling distortion effect.
StaticNoiseIntenisty - Controls the strength of the static noise effect on the screen.

## ScreenPixilation
Pixilate - enables pixilation of the base texture/scene
Pixilation - how pixilated are we making the image

## ScreenScanlines
ScanlineIntensity - How strong is the scanline effect
ScanlineWidth - How wide are the scanlines

## ScreenVignette
VignetteIntensity - How strong is the vignette
VignetteOpacity - How opaque is the vignette

## ScreenWarp
Warp_Amount - how much do we warp the screen at the edges
