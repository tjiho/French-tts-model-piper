# French-tts-model-piper

French TTS models for piper

The first model is trained both on https://git.bksp.space/Tjiho/newspaper-sentences and https://git.bksp.space/Tjiho/baudelaire-sentences.

The second one is only trained on https://git.bksp.space/Tjiho/baudelaire-sentences.

The third is trained 300 epochs longer than the previous one with the same dataset.

You can use them with Piper speech synthetiser https://github.com/rhasspy/piper

```
echo "Je suis un modèle d'intelligence artificielle qui parle français" | ~/bin/piper/piper -m <model> --output_file <your_file>
```

Both are trained on 44100hz audio.
