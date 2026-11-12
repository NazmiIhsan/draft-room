# MLBB Draft Room

MLBB draft practice for ranked and MPL formats, in English and Bahasa Melayu.
Patch 2.2.23 data (11 Nov 2026). © 2026 Mican.

## Put it online (free)

**Netlify Drop (easiest)**
1. Go to app.netlify.com/drop and sign in.
2. Drag this whole `mlbb-app` folder onto the page.
3. You get a link like `https://your-name.netlify.app`. Done.

**GitHub Pages**
1. Create a new GitHub repository and upload everything inside this folder.
2. In the repository, open Settings → Pages.
3. Under "Branch", pick `main` and `/ (root)`, then Save.
4. After a minute your app is live at `https://<username>.github.io/<repo>/`.

The site must be on `https://` for the install button and offline mode to work. Netlify and GitHub Pages do this for you.

## Install on your phone

- **Android (Chrome):** open your link, tap the ⋮ menu, then "Install app" or "Add to Home screen".
- **iPhone (Safari):** open your link, tap Share, then "Add to Home Screen".

It opens full screen like a normal app and still works without internet after the first visit.

## Update the app later

Replace `index.html` with the new version and upload again. To make sure phones pick up the change quickly, also change `draft-room-v1` to `draft-room-v2` (and so on) at the top of `sw.js`.

---

## Letak dalam internet (percuma)

**Netlify Drop (paling senang):** pergi ke app.netlify.com/drop, log masuk, dan tarik folder `mlbb-app` ini ke halaman itu. Anda akan dapat pautan sendiri.

**GitHub Pages:** buat repository baru, muat naik semua fail dalam folder ini, kemudian pergi ke Settings → Pages, pilih branch `main` dan `/ (root)`, dan tekan Save.

## Pasang di telefon

- **Android (Chrome):** buka pautan anda, tekan menu ⋮, kemudian "Install app" atau "Add to Home screen".
- **iPhone (Safari):** buka pautan anda, tekan Share, kemudian "Add to Home Screen".

Fan-made, not affiliated with Moonton. Hero badges are original designs; no game artwork is included.

## Optional: hero and item pictures

The app shows original badges by default. If you add your own pictures, they show automatically:

- Hero pictures: `images/heroes/<name>.png`
- Item pictures: `images/items/<name>.png`
- Emblem and talent pictures: `images/emblems/<name>.png`
- Battle spell pictures: `images/spells/<name>.png`

Names are lowercase with dashes. Any missing picture just falls back to the badge. Note: official MLBB artwork belongs to Moonton. Adding it to a public site is your own choice and risk.

Hero file names:
`aamon.png`, `akai.png`, `aldous.png`, `alice.png`, `alpha.png`, `alucard.png`, `angela.png`, `argus.png`, `arlott.png`, `atlas.png`, `aulus.png`, `aurora.png`, `badang.png`, `balmond.png`, `bane.png`, `barats.png`, `baxia.png`, `beatrix.png`, `belerick.png`, `benedetta.png`, `brody.png`, `bruno.png`, `carmilla.png`, `cecilion.png`, `change.png`, `chip.png`, `chou.png`, `cici.png`, `claude.png`, `clint.png`, `cyclops.png`, `diggie.png`, `dyrroth.png`, `edith.png`, `esmeralda.png`, `estes.png`, `eudora.png`, `fanny.png`, `faramis.png`, `floryn.png`, `franco.png`, `fredrinn.png`, `freya.png`, `gatotkaca.png`, `gloo.png`, `gord.png`, `granger.png`, `grock.png`, `guinevere.png`, `gusion.png`, `hanabi.png`, `hanzo.png`, `harith.png`, `harley.png`, `hayabusa.png`, `helcurt.png`, `hilda.png`, `hirara.png`, `hylos.png`, `irithel.png`, `ixia.png`, `jawhead.png`, `johnson.png`, `joy.png`, `julian.png`, `kadita.png`, `kagura.png`, `kaja.png`, `kalea.png`, `karina.png`, `karrie.png`, `khaleed.png`, `khufra.png`, `kimmy.png`, `lancelot.png`, `lapu-lapu.png`, `layla.png`, `leomord.png`, `lesley.png`, `ling.png`, `lolita.png`, `lukas.png`, `lunox.png`, `luo-yi.png`, `lylia.png`, `marcel.png`, `martis.png`, `masha.png`, `mathilda.png`, `melissa.png`, `minotaur.png`, `minsitthar.png`, `miya.png`, `moskov.png`, `nana.png`, `natalia.png`, `natan.png`, `nolan.png`, `novaria.png`, `obsidia.png`, `odette.png`, `paquito.png`, `pharsa.png`, `phoveus.png`, `popol-and-kupa.png`, `rafaela.png`, `roger.png`, `ruby.png`, `saber.png`, `selena.png`, `silvanna.png`, `sora.png`, `sun.png`, `suyou.png`, `terizla.png`, `thamuz.png`, `tigreal.png`, `uranus.png`, `vale.png`, `valentina.png`, `valir.png`, `vexana.png`, `wanwan.png`, `xborg.png`, `xavier.png`, `yi-sun-shin.png`, `yin.png`, `yu-zhong.png`, `yve.png`, `zetian.png`, `zhask.png`, `zhuxin.png`, `zilong.png`

Item file names (items used in the builds):
`antique-cuirass.png`, `arcane-boots.png`, `athenas-shield.png`, `berserkers-fury.png`, `blade-of-despair.png`, `blade-of-the-heptaseas.png`, `blood-wings.png`, `clock-of-destiny.png`, `concentrated-energy.png`, `corrosion-scythe.png`, `demon-hunter-sword.png`, `divine-glaive.png`, `dominance-ice.png`, `enchanted-talisman.png`, `endless-battle.png`, `feather-of-heaven.png`, `flask-of-the-oasis.png`, `fleeting-time.png`, `genius-wand.png`, `glowing-wand.png`, `golden-staff.png`, `haass-claws.png`, `holy-crystal.png`, `hunter-strike.png`, `ice-queen-wand.png`, `immortality.png`, `lightning-truncheon.png`, `malefic-gun.png`, `malefic-roar.png`, `oracle.png`, `queens-wings.png`, `radiant-armor.png`, `rose-gold-meteor.png`, `swift-boots.png`, `thunder-belt.png`, `tough-boots.png`, `war-axe.png`, `wind-of-nature.png`, `windtalker.png`, `winter-crown.png`

Emblem file names (in `images/emblems/`):
`agility.png`, `assassin.png`, `bargain-hunter.png`, `brave-smite.png`, `concussive-blast.png`, `fatal.png`, `festival-of-blood.png`, `fighter.png`, `firmness.png`, `focusing-mark.png`, `impure-rage.png`, `inspire.png`, `killing-spree.png`, `lethal-ignition.png`, `mage.png`, `marksman.png`, `pull-yourself-together.png`, `quantum-charge.png`, `rupture.png`, `seasoned-hunter.png`, `support.png`, `swift.png`, `tank.png`, `tenacity.png`, `thrill.png`, `unbending-will.png`, `vitality.png`, `war-cry.png`, `weakness-finder.png`, `weapons-master.png`

Battle spell file names (in `images/spells/`):
`flicker.png`, `ice-retribution.png`, `inspire.png`
