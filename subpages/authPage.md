---
transition: slide-left
layout: image-right
image: images/auth.jpg
class: text-justify

---

# L'Authentification

<span v-mark.blue="1">L'authentification est le processus de vérification de l'identité de quelqu'un ou de quelque chose.</span>

<br>
<div v-click="1">Dans notre cas, cette vérification permet de 
s'assurer qu'un utilisateur est bien celui qu'il prétend être
afin de garantir que les données auquelles il accèdes ne sont pas consultées par n'importe qui.
</div>
<br>

<v v-click="2">Dans un système automatisé, ce processus se repose
sur des critères objectifs qu'un ordinateur peut mesurer.
La méthode la plus répandue étant le couple : 
<br>
<span v-mark.circle.blue="3">- Identifiant </span>
<br>
<span v-mark.circle.blue="3">- Mot de passe.</span>

</v click>


<style>
h1 {
  color: #2B90B6;
}
</style>
<!--
-->

---
transition: slide-left

layout: two-cols-header

drawings:
  persist: true
---

# Choisir avec soin ses mots de passe

<br>
📋 Comment est-ce que l'on compose un bon mot de passe ?
::left::
<div class="left">
On suit simplement quelque règles classiques :
<ul style="list-style-type: disc">
  <li>Multipliez les mots de passe et en avoir un pour chaque service différent</li>
  <li>N'utilisez que des mots de passe suffisamment longs et complexes</li>
  <li>Il ne faut pas que l'on puisse les deviner</li>
  <li>Ne les communiquez jamais à des tiers</li>
  <li>Utilisez un gestionnaire de mots de passe pour les stocker de manière sécurisée</li>
  <li>Et privilégiez un mot de passe d'autant plus robuste pour la messagerie !</li>
</ul>
</div>
::right::
<div class="right1"><v v-click="1">
☠️ Ce genre de mot de passe ne devraient pas exister :
<ul class="mdp" style="list-style-type: disc">
  <li>azerty(uiop)</li>
  <li>password</li>
  <li>123456(7890)</li>
  <li>toto1234</li>
  <li>Julie1992</li>
</ul>
</v v-click></div>

<div class="right"><v v-click="2">
✅ Préferez plutôt : 
<ul class="mdp" style="list-style-type: disc">
  <li>Gqeoij#351à*12</li>
  <li><span v-mark.blue="1">GmanG4p0m7semN!</span></li>
  <li><span v-mark.blue="1">Ms.</span>GmanG4p0m7semN!</li>
  <li>GmanG4p0m7semN!<span v-mark.blue="1">.Inst</span></li>
</ul>
</v v-click>
</div>

<style>

h1 {
  color: #2B90B6;
}
.left{
  margin-top: -100px;
  width: 80%;
  font-size: 80%;
  text-align: justify;
}
.right{
  margin-top: 20px;
  width: 80%;
  font-size: 80%;
  text-align: justify;
}
.right1{
  margin-top: -100px;
  width: 80%;
  font-size: 80%;
  text-align: justify;
}
.mdp{
  margin-left: 50px;
}
</style>