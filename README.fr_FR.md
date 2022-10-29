# <img alt="CryptoLogique Logo" src="/imgs/CL.png" height="40"/> CryptoLogique-webApp🔒

 Cette application est utile pour **securiser** vos documents.

## Dépendances

- Electron : [![npm version](https://badge.fury.io/js/electron.svg)](https://badge.fury.io/js/electron)

- Electron forge CLI : [![npm version](https://badge.fury.io/js/@electron-forge%2Fcli.svg)](https://badge.fury.io/js/@electron-forge%2Fcli)

- React : [![npm version](https://badge.fury.io/js/react.svg)](https://badge.fury.io/js/react)

- WebAssembly : [Emscripten](https://emscripten.org/)

### Installation

 #### Windows

 `> make/squirrel.windows/x64/CryptoLogique-1.0.0 Setup.exe`

 #### Linux

  `> sudo dpkg -i make/deb/x64/CryptoLogique_1.0.0_amd64.deb`

 #### MacOS

  `> make/osx/CryptoLogique-1.0.0-x64.dmg`

## Usage

### Windows
 	
   Lancer l'application.<br/>

   `> CryptoLogique.exe`<br/>

   1.	Générer la cléf
		- **direct**<br/><br/>
			<img alt="Generate Key Inline Image Win Fr" src="/imgs/fr/generatekey_inline_validate_win_fr.PNG" height="400" width="532"/><br/>
         La génération de cléf de façon directe permet de copier le contenu de la cléf directement depuis l'application.<br/><br/>
			<img alt="Generate Key Inline Success Image Win Fr" src="/imgs/fr/generatekey_inline_success_win_fr.PNG" height="400" width="532"/><br/>
			Vous pouvez ensuite **Glisser-Déposer** le contenu du fichier ou copier/coller le contenu de la cléf généré.<br/><br/>
		- **fichier**<br/><br/>
			<img alt="Generate Key File Image Win Fr" src="/imgs/fr/generatekey_file_validate_win_fr.PNG" height="400" width="532"/><br/>
         Générer la cléf de type fichier permet uniquement de **Glisser-Déposer** le fichier généré depuis l'application.<br/><br/>    
			<img alt="Generate Key File Success Image Win Fr" src="/imgs/fr/generatekey_file_success_win_fr.PNG" height="400" width="532"/><br/>
         Le contenu de la cléf généré n'est pas affiché.<br/><br/>

   2.	Crypter des fichiers
		- **direct**<br/><br/>
         <img alt="Crypt Files Inline Image Win Fr" src="/imgs/fr/cryptfiles_inline_validate_win_fr.PNG" height="400" width="532"/><br/>
         Crypter des fichiers à travers le mode *-direct-* permet d'embarquer les données de la cléf de cryptage dans le résultat. Cette cléf ne sera pas nécessaire lors du décryptage de la donnée.<br/><br/>
         <img alt="Crypt Files Inline Image Win Fr" src="/imgs/fr/cryptfiles_inline_success_win_fr.PNG" height="400" width="532"/><br/>
         Vous pouvez ensuite **Glisser-Déposer** le(s) fichier(s) crypté(s) pour copier le résultat dans un nouvel emplacement.<br/><br/>
		- **fichier**<br/><br/>
         <img alt="Crypt Files File Image Win Fr" src="/imgs/fr/cryptfiles_file_validate_win_fr.PNG" height="400" width="532"/><br/>
         Crypter des fichiers à travers le mode *-fichier-* désactive la cléf dans le résultat. Afin de décrypter les données il sera donc nécessaire de fournir la cléf de cryptage cependant le résultat est plus court.<br/><br/>
         <img alt="Crypt Files File Image Win Fr" src="/imgs/fr/cryptfiles_file_success_win_fr.PNG" height="400" width="532"/><br/>
         Vous pouvez ensuite **Glisser-Déposer** le(s) fichier(s) crypté(s) pour copier le résultat vers un nouvel emplacement.<br/><br/>
   3.	Decrypter les fichiers
		- **direct**<br/><br/>
         <img alt="Decrypt Files Inline Image Win Fr" src="/imgs/fr/decryptfiles_inline_validate_win_fr.PNG" height="400" width="532"/><br/>
         Décrypter des fichiers à travers le mode *-direct-* permet de omettre la cléf de décryptage.<br/><br/>
         <img alt="Decrypt Files Inline Image Win Fr" src="/imgs/fr/decryptfiles_inline_success_win_fr.PNG" height="400" width="532"/><br/>
         Vous pouvez ensuite **Glisser-Déposer** le(s) fichier(s) décrypté(s) vers un nouvel emplacement.<br/><br/>
		- **fichier**<br/><br/>
         <img alt="Decrypt Files File Image Win Fr" src="/imgs/fr/decryptfiles_file_validate_win_fr.PNG" height="400" width="532"/><br/>
         Décrypter les fichiers à travers le mode *-fichier-* dépend de la cléf de décryptage.<br/><br/>
         <img alt="Decrypt Files File Image Win Fr" src="/imgs/fr/decryptfiles_file_success_win_fr.PNG" height="400" width="532"/><br/>
         Vous pouvez ensuite **Glisser-Déposer** le(s) fichier(s) décrypté(s) pour copier le résultat vers un nouvel emplacement.<br/><br/>
   4.	Supprimer le(s) fichier(s) temporaire(s)<br/><br/>
      <img alt="Delete Temporary Files Win Fr" src="/imgs/fr/delete_temps_win_fr.PNG" height="400" width="532"/><br/>
         Supprimer le(s) fichier(s) généré(s) se trouvant dans le fichier **%AppUserData%/generated_files/**.<br/><br/>
   Voilà !:+1:

### Linux

   Lancer l'application.<br/>

   `> cryptologique`<br/>

   1. Générer la cléf
      - **direct**<br/><br/>
         <img alt="Generate Key Inline Image Linux Fr" src="/imgs/fr/generatekey_inline_validate_linux_fr.png" height="400" width="532"/><br/>
         La génération de cléf de façon directe permet de copier le contenu de la cléf directement depuis l'application.<br/><br/>
         <img alt="Generate Key Inline Success Image Linux Fr" src="/imgs/fr/generatekey_inline_success_linux_fr.png" height="400" width="532"/><br/>
         Vous pouvez ensuite **Glisser-Déposer** le contenu du fichier ou copier/coller le contenu de la cléf généré.<br/><br/>
      - **fichier**<br/><br/>
         <img alt="Generate Key File Image Linux Fr" src="/imgs/fr/generatekey_file_validate_linux_fr.png" height="400" width="532"/><br/>
         Générer la cléf de type fichier permet uniquement de **Glisser-Déposer** le fichier généré depuis l'application.<br/><br/>    
         <img alt="Generate Key File Success Image Linux Fr" src="/imgs/fr/generatekey_file_success_linux_fr.png" height="400" width="532"/><br/>
         Le contenu de la cléf généré n'est pas affiché.<br/><br/>
   2. Crypter des fichiers
      - **direct**<br/><br/>
         <img alt="Crypt Files Inline Image Linux Fr" src="/imgs/fr/cryptfiles_inline_validate_linux_fr.png" height="400" width="532"/><br/>
         Crypter des fichiers à travers le mode *-direct-* permet d'embarquer les données de la cléf de cryptage dans le résultat. Cette cléf ne sera pas nécessaire lors du décryptage de la donnée.<br/><br/>
         <img alt="Crypt Files Inline Image Linux Fr" src="/imgs/fr/cryptfiles_inline_success_linux_fr.png" height="400" width="532"/><br/>
         Vous pouvez ensuite **Glisser-Déposer** le(s) fichier(s) crypté(s) pour copier le résultat dans un nouvel emplacement.<br/><br/>
      - **fichier**<br/><br/>
         <img alt="Crypt Files File Image Linux Fr" src="/imgs/fr/cryptfiles_file_validate_linux_fr.png" height="400" width="532"/><br/>
         Crypter des fichiers à travers le mode *-fichier-* désactive la cléf dans le résultat. Afin de décrypter les données il sera donc nécessaire de fournir la cléf de cryptage cependant le résultat est plus court.<br/><br/>
         <img alt="Crypt Files File Image Linux Fr" src="/imgs/fr/cryptfiles_file_success_linux_fr.png" height="400" width="532"/><br/>
         Vous pouvez ensuite **Glisser-Déposer** le(s) fichier(s) crypté(s) pour copier le résultat vers un nouvel emplacement.<br/><br/>
   3. Decrypter les fichiers
      - **direct**<br/><br/>
         <img alt="Decrypt Files Inline Image Linux Fr" src="/imgs/fr/decryptfiles_inline_validate_linux_fr.png" height="400" width="532"/><br/>
         Décrypter des fichiers à travers le mode *-direct-* permet de omettre la cléf de décryptage.<br/><br/>
         <img alt="Decrypt Files Inline Image Linux Fr" src="/imgs/fr/decryptfiles_inline_success_linux_fr.png" height="400" width="532"/><br/>
         Vous pouvez ensuite **Glisser-Déposer** le(s) fichier(s) décrypté(s) vers un nouvel emplacement.<br/><br/>
      - **fichier**<br/><br/>
         <img alt="Decrypt Files File Image Linux Fr" src="/imgs/fr/decryptfiles_file_validate_linux_fr.png" height="400" width="532"/><br/>
         Décrypter les fichiers à travers le mode *-fichier-* dépend de la cléf de décryptage.<br/><br/>
         <img alt="Decrypt Files File Image Linux Fr" src="/imgs/fr/decryptfiles_file_success_linux_fr.png" height="400" width="532"/><br/>
         Vous pouvez ensuite **Glisser-Déposer** le(s) fichier(s) décrypté(s) pour copier le résultat vers un nouvel emplacement.<br/><br/>
   4. Supprimer le(s) fichier(s) temporaire(s)<br/><br/>
      <img alt="Delete Temporary Files Linux Fr" src="/imgs/fr/delete_temps_linux_fr.png" height="400" width="532"/><br/>
         Supprimer le(s) fichier(s) généré(s) se trouvant dans le fichier **%AppUserData%/generated_files/**.<br/><br/>
   Voilà !:+1:

### MacOS

   Lancer l'application.<br/>

   `> /Applications/CryptoLogique.app/Contents/MacOS/CryptoLogique`<br/>

   1. Générer la cléf
      - **direct**<br/><br/>
         <img alt="Generate Key Inline Image Darwin Fr" src="/imgs/fr/generatekey_inline_validate_darwin_fr.png" height="400" width="532"/><br/>
         La génération de cléf de façon directe permet de copier le contenu de la cléf directement depuis l'application.<br/><br/>
         <img alt="Generate Key Inline Success Image Darwin Fr" src="/imgs/fr/generatekey_inline_success_darwin_fr.png" height="400" width="532"/><br/>
         Vous pouvez ensuite **Glisser-Déposer** le contenu du fichier ou copier/coller le contenu de la cléf généré.<br/><br/>
      - **fichier**<br/><br/>
         <img alt="Generate Key File Image Darwin Fr" src="/imgs/fr/generatekey_file_validate_darwin_fr.png" height="400" width="532"/><br/>
         Générer la cléf de type fichier permet uniquement de **Glisser-Déposer** le fichier généré depuis l'application.<br/><br/>    
         <img alt="Generate Key File Success Image Darwin Fr" src="/imgs/fr/generatekey_file_success_darwin_fr.png" height="400" width="532"/><br/>
         Le contenu de la cléf généré n'est pas affiché.<br/><br/>

   2. Crypter des fichiers
      - **direct**<br/><br/>
         <img alt="Crypt Files Inline Image Darwin Fr" src="/imgs/fr/cryptfiles_inline_validate_darwin_fr.png" height="400" width="532"/><br/>
         Crypter des fichiers à travers le mode *-direct-* permet d'embarquer les données de la cléf de cryptage dans le résultat. Cette cléf ne sera pas nécessaire lors du décryptage de la donnée.<br/><br/>
         <img alt="Crypt Files Inline Image Darwin Fr" src="/imgs/fr/cryptfiles_inline_success_darwin_fr.png" height="400" width="532"/><br/>
         Vous pouvez ensuite **Glisser-Déposer** le(s) fichier(s) crypté(s) pour copier le résultat dans un nouvel emplacement.<br/><br/>
      - **fichier**<br/><br/>
         <img alt="Crypt Files File Image Darwin Fr" src="/imgs/fr/cryptfiles_file_validate_darwin_fr.png" height="400" width="532"/><br/>
         Crypter des fichiers à travers le mode *-fichier-* désactive la cléf dans le résultat. Afin de décrypter les données il sera donc nécessaire de fournir la cléf de cryptage cependant le résultat est plus court.<br/><br/>
         <img alt="Crypt Files File Image Darwin Fr" src="/imgs/fr/cryptfiles_file_success_darwin_fr.png" height="400" width="532"/><br/>
         Vous pouvez ensuite **Glisser-Déposer** le(s) fichier(s) crypté(s) pour copier le résultat vers un nouvel emplacement.<br/><br/>
   3. Decrypter les fichiers
      - **direct**<br/><br/>
         <img alt="Decrypt Files Inline Image Darwin Fr" src="/imgs/fr/decryptfiles_inline_validate_darwin_fr.png" height="400" width="532"/><br/>
         Décrypter des fichiers à travers le mode *-direct-* permet de omettre la cléf de décryptage.<br/><br/>
         <img alt="Decrypt Files Inline Image Darwin Fr" src="/imgs/fr/decryptfiles_inline_success_darwin_fr.png" height="400" width="532"/><br/>
         Vous pouvez ensuite **Glisser-Déposer** le(s) fichier(s) décrypté(s) vers un nouvel emplacement.<br/><br/>
      - **fichier**<br/><br/>
         <img alt="Decrypt Files File Image Darwin Fr" src="/imgs/fr/decryptfiles_file_validate_darwin_fr.png" height="400" width="532"/><br/>
         Décrypter les fichiers à travers le mode *-fichier-* dépend de la cléf de décryptage.<br/><br/>
         <img alt="Decrypt Files File Image Darwin Fr" src="/imgs/fr/decryptfiles_file_success_darwin_fr.png" height="400" width="532"/><br/>
         Vous pouvez ensuite **Glisser-Déposer** le(s) fichier(s) décrypté(s) pour copier le résultat vers un nouvel emplacement.<br/><br/>
   4. Supprimer le(s) fichier(s) temporaire(s)<br/><br/>
      <img alt="Delete Temporary Files Darwin Fr" src="/imgs/fr/delete_temps_darwin_fr.png" height="400" width="532"/><br/>
         Supprimer le(s) fichier(s) généré(s) se trouvant dans le fichier **%AppUserData%/generated_files/**.<br/><br/>
   Voilà !:+1:

## Raccourcis clavier

 ### Windows/Linux

   - **Alt-F**     : Basculer sur l'onglet 'Fichier' de la barre de tâches
   - **Ctrl-Q**    : Quitter l'application
   - **Alt-V**     : Basculer sur l'onglet 'Vue' de la barre de tâches
   - **Ctrl-R**    : Recharger l'application
   - **Ctrl-F**    : Basculer affichage plein écran
   - **Ctrl-M**    : Minimiser l'application
   - **Alt-H**     : Basculer sur l'onglet 'Aide'
   - **Alt-Ctrl-A**: Afficher la page 'A propos'
   - **Alt-Ctrl-0**: Changer langage en français
   - **Alt-Ctrl-1**: Changer langage en anglais

### MacOS

   - **Cmd-Q**       : Quitter l'application
   - **Cmd-R**       : Recharger l'application
   - **Cmd-F**       : Basculer affichage plein écran
   - **Cmd-M**       : Minimiser l'application
   - **Option-Cmd-A**: Afficher la page 'A propos'
   - **Option-Cmd-à**: Changer langage en français
   - **Option-Cmd-&**: Changer langage en anglais

## Types de fichiers acceptés

 - Fichier de référence<br>
   **image**: (.jpg|.jpeg|.png|.gif)  
   **document**: (.txt|.doc|.docx|.pdf|.xml)

 - Fichier à crypter/décrypter<br>
   **texte**: (.txt)

 - Fichier de cléf<br>
   **cléf**: (.key)

## Fichiers générés

### Windows

 - Cléfs<br>
   C:\\Users\\***{Username}***\\Library\\AppData\\Roaming\\CryptoLogique\\generated_files\\keys\\

 - Fichiers cryptés<br>
   C:\\Users\\***{Username}***\\Library\\AppData\\Roaming\\CryptoLogique\\generated_files\\crypted\\

 - Fichiers décryptés<br>
   C:\\Users\\***{Username}***\\Library\\AppData\\Roaming\\CryptoLogique\\generated_files\\decrypted\\

### Linux

 - Cléfs<br>
   /home/***{Username}***/.config/CryptoLogique/generated_files/keys/

 - Fichiers cryptés<br>
   /home/***{Username}***/.config/CryptoLogique/generated_files/crypted/

 - Fichiers décryptés<br>
   /home/***{Username}***/.config/CryptoLogique/generated_files/decrypted/

### MacOS

 - Cléfs<br>
   /Users/***{Username}***/Library/Application Support/CryptoLogique/generated_files/keys/

 - Fichiers cryptés<br>
   /Users/***{Username}***/Library/Application Support/CryptoLogique/generated_files/crypted/

 - Fichiers décryptés<br>
   /Users/***{Username}***/Library/Application Support/CryptoLogique/generated_files/decrypted/
      