# short-drama-script — une compétence Claude pour écrire des séries courtes

🇫🇷 Français · [🇬🇧 English below](#english)

Cette compétence (« skill ») pour Claude écrit des scripts de **séries courtes verticales**, prêts pour [Higgsfield Short Drama](https://higgsfield.ai/short-drama) :

- des questions **une par une**, avec des **choix numérotés** (réponds par un chiffre, quelques mots, ou « choisis pour moi ») ;
- un **choc dans les 2 premières secondes**, un **rebondissement à chaque scène**, un **cliffhanger** à la fin de chaque épisode ;
- des personnages décrits une fois, pour qu'ils gardent le même visage dans chaque scène ;
- uniquement des histoires originales : elle reprend des ambiances, jamais des intrigues, et ne cite aucune œuvre, marque ou personne réelle.

Créée pour la vidéo de [@fabstech](https://www.youtube.com/@fabstech) « Claude fait des séries IA pendant que je dors ».

## Installer

1. Télécharge **[short-drama-script.zip](https://github.com/fabstech-lab/short-drama-skill/releases/latest/download/short-drama-script.zip)**.
2. Dans Claude : **Paramètres → Capacités → Compétences** (Skills), puis **Importer** et choisis le zip. Les noms des menus peuvent varier selon la version.
3. Dans une nouvelle conversation :
   ```
   Utilise ma compétence short-drama-script. Je veux écrire une série courte.
   ```

## Générer les épisodes avec Higgsfield

- **Sur le site** : dépose le script sur [higgsfield.ai/short-drama](https://higgsfield.ai/short-drama), choisis le style, fais un brouillon, corrige, puis génère.
- **Dans Claude** : branche Higgsfield depuis [higgsfield.ai/mcp](https://higgsfield.ai/mcp), puis :
  ```
  Utilise Higgsfield pour lancer /short-drama. Génère une série courte à partir du script final ci-dessus.
  ```
  Higgsfield fait **un épisode par lancement**. Il demande la qualité (brouillon 480p, 720p ou 1080p) et le mode (pas à pas, ou automatique sans aucune question), et affiche le plan et son prix avant de dépenser quoi que ce soit.

## Mode direct (sans questions)

Si ta demande donne déjà tout, la compétence écrit directement. Exemple :
```
Avec la compétence short-drama-script, écris 3 épisodes originaux d'une minute, style cinématographique, sur le thème du sommeil.
```

---

<a id="english"></a>
# short-drama-script — a Claude skill for writing short dramas

This Claude skill writes **vertical short drama** scripts, ready for [Higgsfield Short Drama](https://higgsfield.ai/short-drama):

- questions **one at a time**, with **numbered options** (reply with a number, a few words, or "choose for me");
- a **shock in the first 2 seconds**, a **twist in every scene**, a **cliffhanger** at the end of every episode;
- characters described once, so they keep the same face in every scene;
- original stories only: it takes moods, never plots, and never names existing works, brands or real people.

## Install

1. Download **[short-drama-script.zip](https://github.com/fabstech-lab/short-drama-skill/releases/latest/download/short-drama-script.zip)**.
2. In Claude: **Settings → Capabilities → Skills**, then **Upload** and pick the zip. Menu names may vary by version.
3. In a new chat:
   ```
   Use the short-drama-script skill. I want to write a short drama.
   ```

## Generate the episodes with Higgsfield

- **On the website**: upload the script at [higgsfield.ai/short-drama](https://higgsfield.ai/short-drama), pick a style, make a draft, fix it, then generate.
- **In Claude**: connect Higgsfield from [higgsfield.ai/mcp](https://higgsfield.ai/mcp), then:
  ```
  Use Higgsfield to run /short-drama. Generate a short drama based on the final script above.
  ```
  Higgsfield makes **one episode per run**. It asks for the quality (480p draft, 720p or 1080p) and the mode (step by step, or full auto with no more questions), and shows the plan and its price before anything is charged.

## License

MIT
