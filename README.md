<body>
<header><div class="wrap">
  <h1 class="logo">K<b>O</b>TH</h1>
  <div class="sub">Installation</div>
  <p class="intro">Voici comment installer le jeu et rejoindre le serveur. Cela prend environ dix minutes.</p>
</div></header>

<main class="wrap">
  <section class="step"><div class="n">1</div><div>
    <h2>Avoir Minecraft Java</h2>
    <p>Il faut un compte Minecraft Java Edition lié à votre compte Microsoft. Lancez le jeu une première fois en version 1.20.1 pour vérifier que tout fonctionne.</p>
    <a class="btn" href="https://www.minecraft.net/" target="_blank" rel="noopener">Minecraft.net</a>
  </div></section>

  <section class="step"><div class="n">2</div><div>
    <h2>Installer CurseForge</h2>
    <p>L'application CurseForge installe Forge et les mods à votre place, sans manipuler de fichiers. C'est la méthode la plus simple.</p>
    <a class="btn" href="https://www.curseforge.com/download/app" target="_blank" rel="noopener">Télécharger CurseForge</a>
  </div></section>

  <section class="step"><div class="n">3</div><div>
    <h2>Télécharger le pack KOTH</h2>
    <p>Le pack contient tous les mods et leurs réglages. Vous n'avez rien à ajouter à la main : CurseForge télécharge tout lors de l'importation.</p>
    <a class="btn g" href="{{download_url}}">Télécharger KOTH-1.0.zip</a>
    <p style="margin-top:12px;font-size:16px">Ne le décompressez pas : gardez le fichier .zip tel quel.</p>
  </div></section>

  <section class="step"><div class="n">4</div><div>
    <h2>Importer le pack dans CurseForge</h2>
    <p>Dans l'application CurseForge, choisissez Minecraft, puis :</p>
    <ul class="help">
      <li>cliquez sur « Créer un profil personnalisé » ;</li>
      <li>choisissez « Importer » et sélectionnez le fichier <b>KOTH-1.0.zip</b> ;</li>
      <li>attendez la fin du téléchargement des mods, puis cliquez sur « Jouer ».</li>
    </ul>
    <div class="tip"><b>Astuce :</b> dans les réglages du profil, donnez-lui 4 Go de mémoire ou plus. Le pack utilise Minecraft 1.20.1 et Forge 47.4.28.</div>
    <details class="inc"><summary>Voir les mods inclus dans le pack</summary>
    <table>
      <tr><td>Superb Warfare <span class="ver">par Mercurows</span></td><td><a class="btn" href="https://www.curseforge.com/minecraft/mc-mods/superb-warfare" target="_blank" rel="noopener">CurseForge</a></td></tr>
      <tr><td>TACZ (Timeless and Classics Zero) <span class="ver">par nekocrane</span></td><td><a class="btn" href="https://www.curseforge.com/minecraft/mc-mods/timeless-and-classics-zero" target="_blank" rel="noopener">CurseForge</a></td></tr>
      <tr><td>AshVehicles <span class="ver">par Arusan</span></td><td><a class="btn" href="https://www.curseforge.com/minecraft/mc-mods/ashvehicles" target="_blank" rel="noopener">CurseForge</a></td></tr>
      <tr><td>Fracture Point (Tactical Military Armory) <span class="ver">par Raiiiden</span></td><td><a class="btn" href="https://www.curseforge.com/minecraft/mc-mods/fracture-point" target="_blank" rel="noopener">CurseForge</a></td></tr>
      <tr><td>Curios API <span class="ver">par TheIllusiveC4</span></td><td><a class="btn" href="https://www.curseforge.com/minecraft/mc-mods/curios" target="_blank" rel="noopener">CurseForge</a></td></tr>
      <tr><td>Kotlin for Forge <span class="ver">par thedarkcolour</span></td><td><a class="btn" href="https://www.curseforge.com/minecraft/mc-mods/kotlin-for-forge" target="_blank" rel="noopener">CurseForge</a></td></tr>
      <tr><td>Embeddium <span class="ver">par FiniteReality</span></td><td><a class="btn" href="https://www.curseforge.com/minecraft/mc-mods/embeddium" target="_blank" rel="noopener">CurseForge</a></td></tr>
      <tr><td>Oculus <span class="ver">par Asek3</span></td><td><a class="btn" href="https://www.curseforge.com/minecraft/mc-mods/oculus" target="_blank" rel="noopener">CurseForge</a></td></tr>
      <tr><td>Distant Horizons <span class="ver">par James_Seibel</span></td><td><a class="btn" href="https://www.curseforge.com/minecraft/mc-mods/distant-horizons" target="_blank" rel="noopener">CurseForge</a></td></tr>
      <tr><td>wonderland.jar real one <span class="ver">par user_le8m7rhxoijn78gt</span></td><td><a class="btn" href="https://www.curseforge.com/minecraft/mc-mods/wonderland-jar-real-one" target="_blank" rel="noopener">CurseForge</a></td></tr>
    </table>
    <p style="margin:18px 0 6px"><b>Shaders inclus (facultatifs)</b></p>
    <table>
      <tr><td>BSL Shaders <span class="ver">par capttatsu</span></td><td><a class="btn" href="https://www.curseforge.com/minecraft/shaders/bsl-shaders" target="_blank" rel="noopener">CurseForge</a></td></tr>
      <tr><td>Complementary Shaders - Reimagined <span class="ver">par EminGT</span></td><td><a class="btn" href="https://www.curseforge.com/minecraft/shaders/complementary-reimagined" target="_blank" rel="noopener">CurseForge</a></td></tr>
    </table>
    </details>
  </div></section>

  <section class="step"><div class="n">5</div><div>
    <h2>Rejoindre le serveur</h2>
    <p>Lancez votre profil depuis CurseForge. Dans Minecraft, ouvrez « Multijoueur », cliquez sur « Ajouter un serveur » et entrez l'adresse :</p>
    <div class="addr"><code id="ip">{{server_address}}</code><button class="btn g" onclick="copyIp()" id="cp">Copier</button></div>
    <p style="margin-top:14px">Choisissez votre équipe et votre classe, et c'est parti.</p>
  </div></section>

  <section class="step" style="border-bottom:0"><div class="n">?</div><div>
    <h2>Un problème ?</h2>
    <ul class="help">
      <li><b>« Mods incompatibles » à la connexion :</b> réimportez le pack KOTH-1.0.zip dans un nouveau profil, sans ajouter d'autres mods.</li>
      <li><b>Le jeu plante au lancement :</b> augmentez la mémoire à 4 Go ou plus dans les réglages du profil.</li>
      <li><b>Connexion refusée :</b> vérifiez que votre compte possède Minecraft Java et que vous êtes en version 1.20.1.</li>
      <li><b>Toujours bloqué :</b> demandez de l'aide au staff sur le Discord.</li>
    </ul>
    <p style="margin-top:12px">{{discord_button}}</p>
  </div></section>
</main>
<div class="wrap fine">KOTH est un serveur indépendant, non affilié à Mojang ni à Microsoft.</div>
<script>
function copyIp(){var t=document.getElementById('ip').textContent,b=document.getElementById('cp');function ok(){b.textContent='Copié';setTimeout(function(){b.textContent='Copier';},1500);}if(navigator.clipboard){navigator.clipboard.writeText(t).then(ok,ok);}else{ok();}}
</script>
</body>
</html>
