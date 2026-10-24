<div align="center">

<img src="banner.svg" alt="Cœur 3D en particules" width="100%">

<br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=900&color=FF2D75&center=true&vCenter=true&width=520&lines=2+600+particules+lumineuses+%F0%9F%92%97;Un+c%C5%93ur+qui+tourne+en+3D;Il+bat+toutes+les+1%2C2+secondes;Cod%C3%A9+en+quelques+lignes+%E2%9C%A8" alt="Texte animé">

<br><br>

<a href="https://kaneeekii.github.io/coeur-3d/"><img src="https://img.shields.io/badge/▶_Voir_la_démo-ff2d75?style=for-the-badge" alt="Voir la démo"></a>
<a href="https://www.tiktok.com/@kaneeekii"><img src="https://img.shields.io/badge/TikTok-@kaneeekii-000000?style=for-the-badge&logo=tiktok&logoColor=white" alt="TikTok"></a>

<br>

<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML">
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">

</div>

-----

## 💗 Le projet

Un cœur en 3D fait de **2 600 particules** qui brillent. Il tourne sur lui-même, il bat comme un vrai cœur, et les particules s’échappent puis reviennent se poser dessus.

Tout tient dans **un seul fichier**, sans rien à installer.

## 🚀 Essaie-le

1. Télécharge le fichier [`index.html`](index.html)
1. Ouvre-le dans ton navigateur
1. Regarde ton cœur battre 💗

Ou regarde-le directement en ligne : **[kaneeekii.github.io/coeur-3d](https://kaneeekii.github.io/coeur-3d/)**

## 🧠 Ce que tu apprends

|Langage       |Ce qu’il fait ici                                 |
|--------------|--------------------------------------------------|
|**HTML**      |La balise `<canvas>`, une zone où on peut dessiner|
|**CSS**       |`drop-shadow` pour la lueur néon rose             |
|**JavaScript**|Les maths du cœur, la rotation 3D et l’animation  |

### La formule magique du cœur

```js
const x = 16 * Math.sin(t) ** 3;
const y = 13 * Math.cos(t)
  - 5 * Math.cos(2 * t)
  - 2 * Math.cos(3 * t)
  - Math.cos(4 * t);
```

Quand `t` fait le tour de 0 à 2π, ces deux lignes dessinent la forme d’un cœur. On place une particule à chaque point, et le tour est joué.

## 🎨 Personnalise-le

|Tu veux…                  |Change ça                         |
|--------------------------|----------------------------------|
|Une autre couleur         |`#ff2d75` → `#3b82f6` pour du bleu|
|Plus de particules        |`2600` → `4000`                   |
|Qu’il tourne plus vite    |`0.012` → `0.03`                  |
|Des particules plus folles|`0.5` → `1`                       |

-----

<div align="center">

**Apprends à coder avec Kaneeekii** 💻

Si ça t’a plu, laisse une ⭐ et abonne-toi sur [TikTok](https://www.tiktok.com/@kaneeekii) pour le prochain projet !

</div>
