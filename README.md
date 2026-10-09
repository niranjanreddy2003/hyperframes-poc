# hyperframes-poc

Panda facts video. HyperFrames + Kokoro TTS. 30s, 5 scenes.

## Play
```
npx hyperframes preview --background
```

## Voice
Kokoro ONNX `af_heart`, speed 0.85. Regen:
```
./.venv-tts/bin/python tts.py
```
Models (310MB) download once to `models/`, gitignored.

## Render
```
npx hyperframes render --quality looks --output out.mp4
```
