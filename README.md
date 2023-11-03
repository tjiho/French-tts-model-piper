# French-tts-model-piper

French TTS models for pipers

The first model is trained both on https://git.bksp.space/Tjiho/newspaper-sentences and https://git.bksp.space/Tjiho/baudelaire-sentences


The second one is only trained on https://git.bksp.space/Tjiho/baudelaire-sentences

You can use them with Piper speech synthetiser https://github.com/rhasspy/piper

The third one is trained 300 more epochs than the previous with the same dataset

```
echo "Je suis un modèle d'intelligence artificielle qui parle français" | ~/bin/piper/piper -m <model> --output_file <your_file>
```

Both are trained on 44100hz audio.
