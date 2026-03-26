# Muscle Orchestra

Your face has 52 muscles. Each one is now an instrument.

**[Play it](https://ashleywolf.github.io/muscle-orchestra/)**

MediaPipe's FaceLandmarker tracks all 52 facial blendshapes in real time. Raise an eyebrow, twitch your cheek, open your jaw -- each muscle triggers a different note. Freeplay mode lets you experiment. Song mode gives you a scrolling note highway to follow.

Combo system rewards consecutive hits. Your face is the controller, the instrument, and the show.

## How it works

- MediaPipe FaceLandmarker with 478-point facial mesh and 52 blendshapes
- Web Audio API oscillators generate notes in real time
- Scrolling note highway with hit detection
- 8 instrument lanes mapped to muscle groups
- Canvas rendering with split-screen layout (camera + highway)
- Single HTML file, no external assets
