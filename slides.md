---
theme: seriph
background: ../images/landact.jpg

title: Initiation et Sensibilisation à la Cyber-Sécurité

class: text-center

highlighter: shiki

drawings:
  persist: false

transition: slide-left

mdc: true
---

# Initiation et Sensibilisation à la Cyber-Sécurité

LAND'ACT

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Par xxx XXXXX - XXXXX</span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/YehneeN" target="_blank" alt="My_GitHub" title="YehneeN"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
A l'ère de la révolution numérique dans laquelle nous sommes ; la cybersécurité est devenue un enjeu central pour les organisations de toutes tailles.
Les risques et menaces sont de plus en plus sophistiqués et peuvent être la cause de dommages importants : financiers, juridiques ou réputationnels.
Aujourd'hui dans prêt de 80% des cas, les problèmes de sécurité proviennent d'erreur humaine. (Brain Hacking)

C'est pour cette raison que cette Sensibilisation est une nécessite de premier ordre en 2024.

Cette présentation par acculturation aura pour but de casser certaines de vos croyances et de vous donner des conseils quant aux best practices à connaitre.
-->

---
transition: slide-left
---

# Plan de formation

Les points importants à tout utilisateurs pour réduire les surface d'attaques sont :
<br>
<br>
- 🔐 **L'authentification** - Comprendre ce que c'est et comment la renforcer
- 💻 **L'hygiène informatique** - Maintenir son système et ses applications à jour
- 🌐 **Maitriser sa navigation** - et rester vigilant sur les menaces du WEB
- 📧 **Connaitre les risques liés à la messagerie** - et ne pas tomber dans les pièges d'aujourd'hui
- 📵 **le BYOD** - Comprendre ce que c'est, et le limiter au mieux.
<br>
<br>

Attention, ceci est la base de tout mais ne garantira jamais une protection à 100% !


<!--

-->

<style>
h1 {
  color: #2B90B6;
}
</style>

<!--

-->


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

  - Multipliez les mots de passe et en avoir un pour chaque service différent
  - N'utilisez que des mots de passe suffisamment longs et complexes
  - Il ne faut pas que l'on puisse les deviner
  - Ne les communiquez jamais à des tiers
  - Utilisez un gestionnaire de mots de passe pour les stocker de manière sécurisée
  - Et privilégiez un mot de passe d'autant plus robuste pour la messagerie !
</div>
::right::
<div class="right1"><v v-click="1">
Ce genre de mot de passe ne devraient pas exister :

    - azerty(uiop)
    - password
    - 123456(7890)
    - toto1234
    - Julie1992
</v v-click></div>

<div class="right"><v v-click="2">
Préferez plutôt : 

    - GmanG4p0m7semN!
    - Gqeoij#351à*12
    - Ms.GmanG4p0m7semN!
    - GmanG4p0m7semN!.Inst
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
</style>