# Coral Heights

An original open-world third-person shooter that runs in the browser (three.js r147, WebGL).

**Play locally:** serve this folder over HTTP (the character models are loaded with fetch), e.g.

    cd game && python3 -m http.server 8000

then open http://localhost:8000.

## Features
- Procedural coastal city: downtown glass towers, pastel beachfront, parks, palms, street lamps, beach and ocean
- PBR materials, physical sky, image-based reflections, soft shadows, bloom, ACES tone mapping, color grade, FXAA
- Full day/night cycle (lit windows, street lights, headlights, stars)
- Rigged, animated human characters (idle / walk / run, retargeted at load), procedural aiming
- On-foot shooting (pistol, carbine), headshots, blood, impacts, tracers
- Drivable cars with drift handbrake, carjacking, traffic AI, pedestrians that panic and flee
- Wanted system with police cruisers and armed officers, explosions, courier jobs for cash, pickups, minimap

## Controls
WASD move/drive · Mouse look · Shift sprint · Space jump/handbrake · RMB aim · LMB shoot · R reload · 1/2 weapons · F enter/exit car · T skip time · P graphics quality · Esc pause

## Credits
- `heroine.glb` (the main character): Microsoft Rocketbox avatar `Female_Adult_03` (github.com/microsoft/Microsoft-Rocketbox), MIT License, converted from FBX to glTF with textures downscaled to 1024px. See `models/ROCKETBOX-LICENSE.txt`.

The civilian and police models come from the three.js example assets (github.com/mrdoob/three.js, `examples/models/gltf`):
- `Michelle.glb` and `Soldier.glb`: Mixamo characters and animations
- `readyplayer.me.glb`: Ready Player Me avatar

Check each source's license terms before redistributing them outside personal use.
