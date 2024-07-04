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