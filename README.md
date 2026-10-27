<div align="center">
  <h3>🌍 Choose your language / Choisissez votre langue</h3>
  <a href="#english">🇬🇧 English</a> | <a href="#francais">🇫🇷 Français</a>
</div>

---

<div id="english"></div>
🇬🇧<br>
# 🔐 One link One secret | Bstudio136

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-121013?style=for-the-badge&logo=github&logoColor=white)

A minimalist, zero-knowledge, and fully client-side secret sharing tool. Designed with a premium black and gold theme, smooth animations, and a highly secure architecture where the server never sees your data.

## 🔗 Live Demo
👉 **[Visit the app](https://bstudio136.github.io/OneLink-OneSecret/)**

## ✨ Features

- **100% Zero-Knowledge**: All encryption and decryption happen locally in the browser using the Web Crypto API. Your data never touches a server.
- **Two Sharing Modes**:
  - 🔑 *Password-Protected*: Derives a key using PBKDF2 (1,000,000 iterations) and AES-GCM 256-bit encryption.
  - 🔗 *Link-Only*: Generates a random 256-bit key stored in the URL fragment (after the `#`). Anyone with the link can read it.
- **No Server Logs**: Because the decryption key is in the URL fragment, it is never sent to the hosting server (like GitHub Pages).
- **Premium Design**: Dark mode with a beautiful gold (Aurum) gradient, animated glowing background, and fluid UI transitions.
- **Custom Modal Alerts**: Beautiful, integrated warning modals instead of ugly browser `alert()` popups.
- **100% Responsive**: Adapts perfectly to mobile (prevents iOS auto-zoom), tablet, and desktop screens.

## 🛠️ Tech Stack

- **HTML5**: Semantic structure.
- **CSS3**: CSS Variables, Flexbox, Animations (`@keyframes`), Backdrop filters, Custom modal transitions.
- **JavaScript (Vanilla)**: Web Crypto API (PBKDF2, AES-GCM), URL fragment parsing, Clipboard API, UI state management.

## 🚀 Installation & Usage

This project is a simple standalone HTML file. To run it locally:

1. Clone the repository:
   `git clone https://github.com/Bstudio136/OneLink-OneSecret.git`
2. Open the `index.html` file in your browser.
3. That's it! No dependencies, no build step, no backend required.

## 🎨 Customization

To adapt this tool to your own branding:

1. **Colors**: Modify the CSS variables in `:root` (e.g., `--gold: #d4af37`).
2. **Title**: Change the `<title>` and `<h1>` tags.
3. **Signature**: Update the `<footer class="app-footer">` at the bottom of the HTML file to point to your own website or GitHub.
4. **Iterations**: For better security (but slower performance), you can increase the `ITERATIONS` constant in the JavaScript.

## 👨‍💻 Author

**Bstudio136**

- 🐙 GitHub : [@Bstudio136](https://github.com/Bstudio136)
- 🎵 TikTok : [@bstudio136](https://tiktok.com/@bstudio136)
- 🐦 Twitter / X : [@Bstudio136](https://x.com/Bstudio136)
- 📺 YouTube : [@Bstudio136](https://www.youtube.com/@Bstudio136)

## 📄 License

This project is under the MIT License. You are free to use and modify it for your own needs.

<a href="https://hiddenswap.com/pay/AgRPwfFe" target="_blank" rel="noopener"><img src="https://hiddenswap.com/pay/AgRPwfFe/button.svg" alt="Donate with any coin" width="247" height="44"></a>

---

<div id="francais"></div>
🇫🇷<br>
# 🔐 One link One secret | Bstudio136

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-121013?style=for-the-badge&logo=github&logoColor=white)

Un outil minimaliste, zéro-knowledge et 100% côté client pour partager des secrets. Conçu avec un thème premium noir et or, des animations fluides et une architecture hautement sécurisée où le serveur ne voit jamais vos données.

## 🔗 Démo en direct
👉 **[Visiter l'application](https://bstudio136.github.io/OneLink-OneSecret/)**

## ✨ Fonctionnalités

- **100% Zéro-Knowledge** : Tout le chiffrement et le déchiffrement se font localement dans le navigateur via la Web Crypto API. Vos données ne touchent jamais un serveur.
- **Deux modes de partage** :
  - 🔑 *Protégé par mot de passe* : Dérivation de clé avec PBKDF2 (1 000 000 d'itérations) et chiffrement AES-GCM 256 bits.
  - 🔗 *Lien uniquement* : Génère une clé aléatoire de 256 bits stockée dans le fragment de l'URL (après le `#`). Toute personne possédant le lien peut le lire.
- **Aucun log serveur** : Comme la clé de déchiffrement est dans le fragment de l'URL, elle n'est jamais envoyée au serveur d'hébergement (comme GitHub Pages).
- **Design Premium** : Mode sombre avec un magnifique dégradé doré, arrière-plan lumineux animé et transitions UI fluides.
- **Modales Personnalisées** : De belles alertes intégrées au design au lieu des popups `alert()` natives du navigateur.
- **100% Responsive** : S'adapte parfaitement aux mobiles (évite le zoom auto sur iOS), tablettes et ordinateurs.

## 🛠️ Technologies Utilisées

- **HTML5** : Structure sémantique.
- **CSS3** : Variables CSS, Flexbox, Animations (`@keyframes`), Filtres d'arrière-plan, transitions de modales.
- **JavaScript (Vanilla)** : Web Crypto API (PBKDF2, AES-GCM), analyse du fragment d'URL, Clipboard API, gestion de l'état de l'UI.

## 🚀 Installation & Utilisation

Ce projet est un simple fichier HTML autonome. Pour le faire fonctionner localement :

1. Clonez le dépôt :
   `git clone https://github.com/Bstudio136/OneLink-OneSecret.git`
2. Ouvrez le fichier `index.html` dans votre navigateur.
3. C'est tout ! Aucune dépendance, aucun build et aucun backend requis.

## 🎨 Personnalisation

Pour adapter cet outil à votre propre image :

1. **Couleurs** : Modifiez les variables CSS dans `:root` (par exemple, `--gold: #d4af37`).
2. **Titres** : Modifiez les balises `<title>` et `<h1>`.
3. **Signature** : Mettez à jour la balise `<footer class="app-footer">` en bas du fichier HTML pour pointer vers votre propre site ou GitHub.
4. **Itérations** : Pour une sécurité accrue (mais des performances plus lentes), vous pouvez augmenter la constante `ITERATIONS` dans le JavaScript.

## 👨‍💻 Auteur

**Bstudio136**

- 🐙 GitHub : [@Bstudio136](https://github.com/Bstudio136)
- 🎵 TikTok : [@bstudio136](https://tiktok.com/@bstudio136)
- 🐦 Twitter / X : [@Bstudio136](https://x.com/Bstudio136)
- 📺 YouTube : [@Bstudio136](https://www.youtube.com/@Bstudio136)

## 📄 Licence

Ce projet est sous licence MIT. Vous êtes libre de l'utiliser et de le modifier pour vos propres besoins.

<a href="https://hiddenswap.com/pay/AgRPwfFe" target="_blank" rel="noopener"><img src="https://hiddenswap.com/pay/AgRPwfFe/button.svg" alt="Donate with any coin" width="247" height="44"></a>
