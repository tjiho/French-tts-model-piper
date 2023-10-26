# French-tts-model-piper

French TTS models for pipers

First one train both on https://git.bksp.space/Tjiho/newspaper-sentences and https://git.bksp.space/Tjiho/baudelaire-sentences

<audio src="./small-example-1.wav"/>
<audio src="./long-example-1.wav"/>

Second one only train on https://git.bksp.space/Tjiho/baudelaire-sentences

<audio src="./small-example-1.wav"/>
<audio src="./long-example-1.wav"/>


You can use them with Piper speech synthetiser https://github.com/rhasspy/piper

```
echo "Je suis un modèle d'intelligence artificielle qui parle français" | ~/bin/piper/piper -m <model> --output_file <your_file>
```
