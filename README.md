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

## Licence et conditions d'usage (FR)

### Licence du modèle

Les fichiers de poids sont publié sous **AGPL-3.0** (voir [`LICENSE`](./LICENSE)).

- Un programme qui charge l'un de ces fichiers n'en devient pas une œuvre dérivée : l'AGPL ne s'étend pas au code qui l'utilise, et l'article 13 ne s'applique pas à votre application si les poids sont utilisés tels quels. [Piper](https://github.com/rhasspy/piper), la bibliothèque qui exécute le modèle, est sous licence MIT et n'impose rien.
- La **redistribution** du fichier de poids reste soumise à l'AGPL-3.0 et à ses obligations de mention.
- Toute **modification des poids** — fine-tuning, quantization, conversion de format — constitue une œuvre dérivée : sa source doit être proposée aux utilisateurs, conformément à l'article 13, dès lors que le résultat est distribué ou exposé en réseau.

### Autorisation d'usage de la voix

Ce modèle reproduit une **voix humaine réelle**. Cet usage relève des droits de la personnalité et fait l'objet d'une autorisation **distincte de la licence logicielle**.

Cette autorisation est accordée gratuitement, aux conditions suivantes :

1. Tout modèle de voix entraîné, affiné ou reconstruit à partir des poids **ou de l'audio produit** doit être publié sous AGPL-3.0. Cette condition est attachée à l'autorisation d'usage de la voix, indépendamment de la portée de l'AGPL.
2. La voix ne doit être présentée ni comme celle d'une personne réelle, ni comme celle d'une personne identifiée. L'identité de l'auteur ne doit être ni mentionnée dans les services utilisant ce modèle, ni communiquée à leurs utilisateurs finaux. Les mentions de copyright et de licence attachées au fichier restent à conserver ; elles concernent le fichier et sa source, pas vos interfaces.

**Tout usage ne respectant pas ces conditions n'est pas autorisé.**

Pour un usage incompatible avec ces conditions, ouvrez une issue ou contactez l'auteur pour discuter d'une licence spécifique.


## License and terms of use (EN)
### Model license
The weight files are released under **AGPL-3.0** (see [`LICENSE`](./LICENSE)).
- A program that loads one of these files does not become a derivative work of it: the AGPL does not extend to the code using it, and Section 13 does not apply to your application as long as the weights are used as-is. [Piper](https://github.com/rhasspy/piper), the library that runs the model, is MIT-licensed and imposes nothing.
- **Redistribution** of the weight files remains subject to AGPL-3.0 and its notice requirements.
- Any **modification of the weights** — fine-tuning, quantization, format conversion — constitutes a derivative work: its source must be offered to users, in accordance with Section 13, whenever the result is distributed or made available over a network.
### Voice usage authorization
This model reproduces a **real human voice**. Such use falls under personality rights and is subject to an authorization **separate from the software license**.
This authorization is granted free of charge, under the following conditions:
1. Any voice model trained, fine-tuned, or reconstructed from the weights **or from the generated audio** must be released under AGPL-3.0. This condition is attached to the voice usage authorization itself, independently of the scope of the AGPL.
2. The voice must not be presented as belonging to a real person, nor to an identified person. The author's identity must neither be mentioned in services using this model, nor disclosed to their end users. The copyright and license notices attached to the files must be preserved; they pertain to the files and their source, not to your interfaces.
**Any use that does not comply with these conditions is not authorized.**
