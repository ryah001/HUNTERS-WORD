HUNTERS WORD - site statique

Structure:
- index.html : page d'accueil
- telegram.html : liste des canaux Telegram
- whatsapp.html : liste des chaînes WhatsApp
- services.html : pages des services avec galerie et liens de commande
- css/style.css : styles
- assets/ : place pour vos images (logo, hero, cal1..)

Instructions rapides :
1. Copiez vos images locales dans `assets/` :
   - `hero.jpg` : arrière-plan principal
   - `logo.png` : logo (le site référence `assets/logo.png`)
   - `cal1.jpg`, `cal2.jpg`, `cal3.jpg`, `cal4.jpg` : calendriers
   - `id.jpg` : carte otaku
   - `sched1.jpg`, `sched2.jpg`, `sched3.jpg`, `sched4.jpg` : emplois du temps

2. Pour héberger les images sur GitHub :
   - Initialisez un dépôt git dans le dossier `hunters-word-site` :

```powershell
cd "c:\Users\Crist\Documents\Pro\hunters-word-site"
git init
git add .
git commit -m "Initial commit - HUNTERS WORD site"
# Créez un repo sur GitHub puis associez-le et poussez :
# git remote add origin https://github.com/<votre-compte>/hunters-word-site.git
git push -u origin main
```

3. Après push, vos images seront accessibles via le repo GitHub Pages ou directement via les raw.githubusercontent URLs.

4. Tester en local : ouvrez `index.html` dans votre navigateur.

Remarques :
- Je n'ai pas modifié vos images. Copiez-les simplement dans `assets/` et renommez-les selon la liste ci-dessus.
- Si vous voulez, je peux initialiser le dépôt Git et pousser pour vous, mais j'aurai besoin d'accès GitHub (token) — je ne le ferai pas sans votre autorisation.
