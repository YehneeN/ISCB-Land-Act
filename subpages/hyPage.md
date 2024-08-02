---
transition: slide-up
class: text-center
---

# Hygiène Informatique 

<span v-mark.blue="0">Les mesures pour garantir un système sain.</span>

<div class="blc">
<img src="images/hy.jpg">
</div>

<style>
h1 {
  color: #2B90B6;
}
.blc {
    display: flex;
    align-items: center;
    justify-content: center;
}
img {
    height: 35vh;
    border-radius: 100%;
}
</style>


<!-- Parmi les mesures techniques que les utilisateurs doivent prendre pour garantir la sécurité de leurs systèmes d’information, on peut notifier les plus simples d’hygiène informatique, car elles sont l'image dans le monde numérique de règles élémentaires de sécurité sanitaire. <-->

---
transition: slide-up

layout: two-cols-header

class: test-justify

drawings:
  persist: true
---

# Différencier les comptes utilisateurs

On distingue généralement les droits dits <span v-mark.blue="0">**d'utilisateur**</span> et les droits dits <span v-mark.blue="0">**d'administrateur**</span>.


::left::
Votre compte, qu'il soit utilisateur ou administrateur, doit être nominatif. 
C'est votre <span v-mark.blue="0">**identité**</span> sur un service d'information à laquelle on attribue des <span v-mark.blue="0">**rôles**</span> qui détiennent des droits plus ou moins étendus.
<br>
<br>
<div class="blc"><img class="img2" src="images/ACL.png"></div>

::right::
En entreprise, il convient d'autant plus de n'utiliser que des comptes utilisateurs et de réserver les comptes administrateurs aux tâches qui nécessitent d'avoir des droits plus larges.
<br>
<br>
<div class="blc"><img src="images/ID.png"></div>


<style>
img {
    height: 20vh;
}
.img2 {
    height: 15vh;
}
.blc {
    margin-top: 1vh;
    display: flex;
    align-items: center;
    justify-content: center;
}
</style>


---
transition: slide-up

layout: image-right
image: images/software-update.jpg

class: text-justify

drawings:
  persist: true
---

# Installations et mises à jour de logiciels

<span v-mark.blue="0">Appareils numérique ou logiciels<br>
= **nouvelles failles tous les jours**</span>.

<br>
Si aucun système ne gère pour vous les mises à jours de manières automatique, et qu'une notification vous signale des mises à jours du système d'exploitation ; <span v-mark.blue="0"><b>installez-la</b></span>.

<br>
<br>

Ces patch ciblent essentiellement les failles de sécurité de votre appareil. 


<style>

</style>

--- 
transition: slide-up
class: text-justify
layout: two-cols-header
---

# Les cracks "safe", ça n'existe pas
<span v-mark.blue="0">Si c'est gratuit... C'est vous le produit.</span>

::left::
>« J’ai téléchargé la saison 3, tu la veux ? »

>« Un ami m’a installé la dernière version de PS CC. »

>« J’ai l’intégralité du MCU en Full HD. »

>« Oui mais ça va, c’est que des films… »

>« Tu sais où je peux trouver tel logiciel, gratuitement ? »

>« J’ai le crack du dernier Call Of Duty… »

>« T’as pas un site pour télécharger des films ? »

>« J'utilise un VPN, c'est bon. »

>« J'ai jamais eu de problèmes en téléchargeant des séries. »

::right::
![](images/malwares.png)

<br>

<br>

---
transition: slide-up
class: text-justify
layout: image-right
image: images/av.jpg
---

# La nécessité d'avoir un bon anti-virus

L’antivirus est la première base de la protection, peu importe le système d’exploitation. 

* OUI, il est nécessaire d’en avoir un pour détecter, isoler et supprimer les menaces.
* OUI, les programmes malveillants existent sur tous les systèmes d’exploitation (Windows, MacOS, iOS, Android, Linux).


* NON, l’antivirus ne fait pas tout et vous devez rester vigilants. 
* NON, un antivirus n’a pas besoin d’être payant pour être performant. 

---
transition: slide-right
class: text-justify
---

# Où stocker ses données ?

Pour sécuriser ses données, et celle de son entreprise ; il est important de choisir le bon support stockage.

<br>

````md magic-move
```js
1. Sur un serveur de fichier local.

Stockage fiable, durable et sécurisé
Permet de partager les données avec le reste de l’équipe
Les données seront sauvegardées avec l’entièreté du serveur
Adapté pour le stockage de données sensibles
```
```js
2. Sur le Cloud

Permet un travail synchronisé et collaboratif plus avancé
Moins couteux qu’une infrastructure
Ouvre plus facilement l'entreprise à la collaboration externe

/ ! \ Derrière le « Cloud » se cache un ensemble de serveurs de fichiers redondants ; 
MAIS, on ne sait pas vraiment où sont stockées les données.
Aussi, les hébergeurs ne garantissent aucune sauvegarde de vos données. / ! \
```
```ts
3. Sur l'ordinateur directement ?

Vous posez-vous vraiment cette question ? 😉

Ne nécessite aucune authentification, 
Sujet au piratage,
Non adapté au partage, 
Stockage temporaire, 
Si pas de chiffrement = pas de sécurité
```
````