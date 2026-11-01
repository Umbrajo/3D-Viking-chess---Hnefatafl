# 3D-Viking-chess - Hnefatafl

## 🇬🇧 English

**Joann Delacroix, original idea and project direction.**

Recently, I noticed the arrival of [Traversal](https://www.traversalgame.com/), an alternative to chess. It reminded me of a project I had imagined back in high school, and I decided to use AI to bring that project to life.

### The game

I adapted Hnefatafl to a **7 × 7 × 7 cube**: one king, 24 defenders, 54 attackers, and twelve exits. Play solo against the computer or with two players on the same screen. The full rules of this variant are available in the game.

The defenders (white) must lead the king to one of the 12 exits (yellow dots). The attackers (black) must surround the opposing king with their pieces.

Pieces can move any number of squares in a straight line. To capture an opposing piece, sandwich it between two of your own pieces.

**Suggested pronunciation:** “neffa-taffle”, approximate Old Norse transcription **[ˈhne.vɑˌtɑvl]**.

To discover the traditional game on a two-dimensional board, visit [A Rule Book for Hnefatafl](http://tafl.cyningstan.com/page/20/a-rule-book-for-hnefatafl), a site specializing in traditional games (in English). The historical rules have not survived in their entirety; modern variants are based on reconstructions. This cubic adaptation does not claim to reproduce the historical rules.

The graphical interface is based on [https://www.chess3d.co](https://www.chess3d.co). This code was created with the help of ChatGPT.

### Running the site

You can play online at https://umbrajo.github.io/3D-Viking-chess---Hnefatafl/.

Alternatively, download the project folder and serve the site statically from that folder with:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

Enjoy!

*This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.*

*This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.*

*You should have received a copy of the GNU General Public License along with this program. If not, see [https://www.gnu.org/licenses/](https://www.gnu.org/licenses/).*

---

## 🇫🇷 Français

**Joann Delacroix, idée et direction du projet.**

Récemment, j’ai constaté l’apparition de [Traversal](https://www.traversalgame.com/), qui se trouve être une alternative au jeu d’échecs. Cela m’a rappelé un projet que j’avais imaginé à l’époque du lycée et j’ai décidé de profiter de l’IA pour réaliser ce projet.

### Le jeu

J’ai fait une adaptation de Hnefatafl sur un cube de **7 × 7 × 7 cases** : un roi, 24 défenseurs, 54 attaquants et douze sorties. Jouez en solo contre l’ordinateur ou à deux sur le même écran. Les règles complètes de cette variante sont accessibles dans le jeu.

Le but de la défense (en blanc) est d’emmener le roi vers une des 12 sorties (points jaunes). Le but de l’attaque (en noir) est d’encadrer le roi adverse avec des pions.

Les pions peuvent bouger d’autant de cases qu’ils veulent en ligne droite. Le moyen de saisir un pion est d’encadrer le pion adverse avec deux de vos propres pions.

**Prononciation indicative :** « neffa-taffle », transcription approximative du vieux norrois **[ˈhne.vɑˌtɑvl]**.

Pour découvrir le jeu traditionnel sur un plateau à deux dimensions : [A Rule Book for Hnefatafl](http://tafl.cyningstan.com/page/20/a-rule-book-for-hnefatafl), un site spécialisé dans les jeux traditionnels (en anglais). Les règles historiques ne nous sont pas parvenues intégralement ; les variantes actuelles reposent sur des reconstructions. Cette adaptation cubique ne prétend pas reproduire les règles historiques.

L’interface graphique est tirée du site [https://www.chess3d.co](https://www.chess3d.co). Ce code a été réalisé à l’aide de ChatGPT.

### Lancer le site

Vous pouvez vous connecter en ligne sur https://umbrajo.github.io/3D-Viking-chess---Hnefatafl/.

Sinon, vous pouvez télécharger le dossier et lancer le site de manière statique depuis ce dossier avec :

```sh
python3 -m http.server 8000
```

Et vous connecter sur http://localhost:8000.

Profitez bien !

*Ce programme est un logiciel libre : vous pouvez le redistribuer et/ou le modifier selon les termes de la licence publique générale GNU telle que publiée par la Free Software Foundation, soit la version 3 de la licence, soit (à votre choix) toute version ultérieure.*

*Ce programme est distribué dans l’espoir qu’il sera utile, mais SANS AUCUNE GARANTIE, sans même la garantie implicite de COMMERCIALISABILITÉ ou d’ADÉQUATION À UN USAGE PARTICULIER. Voir la licence publique générale GNU pour plus de détails.*

*Vous devriez avoir reçu une copie de la licence publique générale GNU avec ce programme. Si ce n’est pas le cas, consultez [https://www.gnu.org/licenses/](https://www.gnu.org/licenses/).*
