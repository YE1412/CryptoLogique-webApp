# <img alt="CryptoLogique Logo" src="/imgs/CL.png" height="40"/> CryptoLogique-webApp🔒

 This application is useful to **secure** your documents.

## Dependencies

- Electron : [![npm version](https://badge.fury.io/js/electron.svg)](https://badge.fury.io/js/electron)

- Electron forge CLI : [![npm version](https://badge.fury.io/js/@electron-forge%2Fcli.svg)](https://badge.fury.io/js/@electron-forge%2Fcli)

- React : [![npm version](https://badge.fury.io/js/react.svg)](https://badge.fury.io/js/react)

- WebAssembly : [Emscripten](https://emscripten.org/)

### Installation

 #### Windows

 `> make\squirrel.windows\x64\CryptoLogique-1.0.0 Setup.exe`

 #### Linux

  `> sudo dpkg -i make/deb/x64/CryptoLogique_1.0.0_amd64.deb`

 #### MacOS

  `> make/osx/CryptoLogique-1.0.0-x64.dmg`

## Usage

### Windows
 	
   Run the app.<br/>

   `> CryptoLogique.exe`<br/>

   1.	Generate the key
		- **inline**<br/><br/>
			<img alt="Generate Key Inline Image Win En" src="/imgs/en/generatekey_inline_validate_win_en.PNG" height="400" width="532"/><br/>
			Generate inline key allow you to copy the content of the key directly from the app.<br/><br/>    
			<img alt="Generate Key Inline Success Image Win En" src="/imgs/en/generatekey_inline_success_win_en.PNG" height="400" width="532"/><br/>
			You can then **drag & drop** the file content or copy and paste the content of the generated key.<br/><br/>
		- **file**<br/><br/>
			<img alt="Generate Key File Image Win En" src="/imgs/en/generatekey_file_validate_win_en.PNG" height="400" width="532"/><br/>
			Generate file key allow you to **drap & drop** the file from the app.<br/><br/>    
			<img alt="Generate Key File Success Image Win En" src="/imgs/en/generatekey_file_success_win_en.PNG" height="400" width="532"/><br/>
			The content of the generated key is not shown.<br/><br/>

   2.	Crypt some files
		- **inline**<br/><br/>
         <img alt="Crypt Files Inline Image Win En" src="/imgs/en/cryptfiles_inline_validate_win_en.PNG" height="400" width="532"/><br/>
         Crypt files through the *-inline mode-* allow keystream embedding to the outcome. No need of key to decrypt the output stream.<br/><br/>
         <img alt="Crypt Files Inline Image Win En" src="/imgs/en/cryptfiles_inline_success_win_en.PNG" height="400" width="532"/><br/>
         You can then **drag & drop** the crypted file(s) to copy the result to a new location.<br/><br/>
		- **file**<br/><br/>
         <img alt="Crypt Files File Image Win En" src="/imgs/en/cryptfiles_file_validate_win_en.PNG" height="400" width="532"/><br/>
         Crypt files through the *-file mode-* disable keystream embedding to the outcome. You will need the key to decrypt the output stream but the result is shorter.<br/><br/>
         <img alt="Crypt Files File Image Win En" src="/imgs/en/cryptfiles_file_success_win_en.PNG" height="400" width="532"/><br/>
         You can then **drag & drop** the crypted file(s) to copy the result to a new location.<br/><br/>
   3.	Decrypt files
		- **inline**<br/><br/>
         <img alt="Decrypt Files Inline Image Win En" src="/imgs/en/decryptfiles_inline_validate_win_en.PNG" height="400" width="532"/><br/>
         Decrypt files through the *-inline mode-* with embedded keystream content to the input.<br/><br/>
         <img alt="Decrypt Files Inline Image Win En" src="/imgs/en/decryptfiles_inline_success_win_en.PNG" height="400" width="532"/><br/>
         You can then **drag & drop** the decrypted file(s) to copy the result to a new location.<br/><br/>
		- **file**<br/><br/>
         <img alt="Decrypt Files File Image Win En" src="/imgs/en/decryptfiles_file_validate_win_en.PNG" height="400" width="532"/><br/>
         Decrypt files through the *-file mode-* with regular content to the input.<br/><br/>
         <img alt="Decrypt Files File Image Win En" src="/imgs/en/decryptfiles_file_success_win_en.PNG" height="400" width="532"/><br/>
         You can then **drag & drop** the decrypted file(s) to copy the result to a new location.<br/><br/>
   4.	Delete temps<br/><br/>
      <img alt="Delete Temporary Files Win En" src="/imgs/en/delete_temps_win_en.PNG" height="400" width="532"/><br/>
         Deleting the generated files from the **%AppUserData%/generated_files/** folder.<br/><br/>
   Enjoy !:+1:

### Linux

   Run the app.<br/>

   `> cryptologique`<br/>

   1. Generate a key
      - **inline**<br/><br/>
         <img alt="Generate Key Inline Image Linux En" src="/imgs/en/generatekey_inline_validate_linux_en.png" height="400" width="532"/><br/>
         Generate inline key allow you to copy the content of the key directly from the app.<br/><br/>    
         <img alt="Generate Key Inline Success Image Linux En" src="/imgs/en/generatekey_inline_success_linux_en.png" height="400" width="532"/><br/>
         You can then **drag & drop** the file content or copy and paste the content of the generated key.<br/><br/>
      - **file**<br/><br/>
         <img alt="Generate Key File Image Linux En" src="/imgs/en/generatekey_file_validate_linux_en.png" height="400" width="532"/><br/>
         Generate file key allow you to drap & drop the file from the app.<br/><br/>    
         <img alt="Generate Key File Success Image Linux En" src="/imgs/en/generatekey_file_success_linux_en.png" height="400" width="532"/><br/>
         The content of the generated key is not shown.<br/><br/>
   2. Crypt some files
      - **inline**<br/><br/>
         <img alt="Crypt Files Inline Image Linux En" src="/imgs/en/cryptfiles_inline_validate_linux_en.png" height="400" width="532"/><br/>
         Crypt files through the *-inline mode-* allow keystream embedding to the outcome. No need of key to decrypt the output stream.<br/><br/>
         <img alt="Crypt Files Inline Image Linux En" src="/imgs/en/cryptfiles_inline_success_linux_en.png" height="400" width="532"/><br/>
         You can then **drag & drop** the crypted file(s) to copy the result to a new location.<br/><br/>
      - **file**<br/><br/>
         <img alt="Crypt Files File Image Linux En" src="/imgs/en/cryptfiles_file_validate_linux_en.png" height="400" width="532"/><br/>
         Crypt files through the *-file mode-* disable keystream embedding to the outcome. You will need the key to decrypt the output stream but the result is shorter.<br/><br/>
         <img alt="Crypt Files File Image Linux En" src="/imgs/en/cryptfiles_file_success_linux_en.png" height="400" width="532"/><br/>
         You can then **drag & drop** the crypted file(s) to copy the result to a new location.<br/><br/>
   3. Decrypt some files
      - **inline**<br/><br/>
         <img alt="Decrypt Files Inline Image Linux En" src="/imgs/en/decryptfiles_inline_validate_linux_en.png" height="400" width="532"/><br/>
         Decrypt files through the *-inline mode-* with embedded keystream content to the input.<br/><br/>
         <img alt="Decrypt Files Inline Image Linux En" src="/imgs/en/decryptfiles_inline_success_linux_en.png" height="400" width="532"/><br/>
         You can then **drag & drop** the decrypted file(s) to copy the result to a new location.<br/><br/>
      - **file**<br/><br/>
         <img alt="Decrypt Files File Image Linux En" src="/imgs/en/decryptfiles_file_validate_linux_en.png" height="400" width="532"/><br/>
         Decrypt files through the *-file mode-* with regular content to the input.<br/><br/>
         <img alt="Decrypt Files File Image Linux En" src="/imgs/en/decryptfiles_file_success_linux_en.png" height="400" width="532"/><br/>
         You can then **drag & drop** the decrypted file(s) to copy the result to a new location.<br/><br/>
   4. Delete temps<br/><br/>
      <img alt="Delete Temporary Files Linux En" src="/imgs/en/delete_temps_linux_en.png" height="400" width="532"/><br/>
         Deleting the generated files from the **%AppUserData%/generated_files/** folder.<br/><br/>
   Enjoy !:+1:

### MacOS

   Run the app.<br/>

   `> /Applications/CryptoLogique.app/Contents/MacOS/CryptoLogique`<br/>

   1. Generate a key
      - **inline**<br/><br/>
         <img alt="Generate Key Inline Image Darwin En" src="/imgs/en/generatekey_inline_validate_darwin_en.png" height="400" width="532"/><br/>
         Generate inline key allow you to copy the content of the key directly from the app.<br/><br/>    
         <img alt="Generate Key Inline Success Image Darwin En" src="/imgs/en/generatekey_inline_success_darwin_en.png" height="400" width="532"/><br/>
         You can then **drag & drop** the file content or copy and paste the content of the generated key.<br/><br/>
      - **file**<br/><br/>
         <img alt="Generate Key File Image Darwin En" src="/imgs/en/generatekey_file_validate_darwin_en.png" height="400" width="532"/><br/>
         Generate file key allow you to drap & drop the file from the app.<br/><br/>    
         <img alt="Generate Key File Success Image Darwin En" src="/imgs/en/generatekey_file_success_darwin_en.png" height="400" width="532"/><br/>
         The content of the generated key is not shown.<br/><br/>

   2. Crypt some files
      - **inline**<br/><br/>
         <img alt="Crypt Files Inline Image Darwin En" src="/imgs/en/cryptfiles_inline_validate_darwin_en.png" height="400" width="532"/><br/>
         Crypt files through the *-inline mode-* allow keystream embedding to the outcome. No need of key to decrypt the output stream.<br/><br/>
         <img alt="Crypt Files Inline Image Darwin En" src="/imgs/en/cryptfiles_inline_success_darwin_en.png" height="400" width="532"/><br/>
         You can then **drag & drop** the crypted file(s) to copy the result to a new location.<br/><br/>
      - **file**<br/><br/>
         <img alt="Crypt Files File Image Darwin En" src="/imgs/en/cryptfiles_file_validate_darwin_en.png" height="400" width="532"/><br/>
         Crypt files through the *-file mode-* disable keystream embedding to the outcome. You will need the key to decrypt the output stream but the result is shorter.<br/><br/>
         <img alt="Crypt Files File Image Darwin En" src="/imgs/en/cryptfiles_file_success_darwin_en.png" height="400" width="532"/><br/>
         You can then **drag & drop** the crypted file(s) to copy the result to a new location.<br/><br/>
   3. Decrypt some files
      - **inline**<br/><br/>
         <img alt="Decrypt Files Inline Image Darwin En" src="/imgs/en/decryptfiles_inline_validate_darwin_en.png" height="400" width="532"/><br/>
         Decrypt files through the *-inline mode-* with embedded keystream content to the input.<br/><br/>
         <img alt="Decrypt Files Inline Image Darwin En" src="/imgs/en/decryptfiles_inline_success_darwin_en.png" height="400" width="532"/><br/>
         You can then **drag & drop** the decrypted file(s) to copy the result to a new location.<br/><br/>
      - **file**<br/><br/>
         <img alt="Decrypt Files File Image Darwin En" src="/imgs/en/decryptfiles_file_validate_darwin_en.png" height="400" width="532"/><br/>
         Decrypt files through the *-file mode-* with regular content to the input.<br/><br/>
         <img alt="Decrypt Files File Image Darwin En" src="/imgs/en/decryptfiles_file_success_darwin_en.png" height="400" width="532"/><br/>
         You can then **drag & drop** the decrypted file(s) to copy the result to a new location.<br/><br/>
   4. Delete temps<br/><br/>
      <img alt="Delete Temporary Files Darwin En" src="/imgs/en/delete_temps_darwin_en.png" height="400" width="532"/><br/>
         Deleting the generated files from the **%AppUserData%/generated_files/** folder.<br/><br/>
   Enjoy !:+1:

## Shortcuts

 ### Windows/Linux

   - **Alt-F**     : Toggle file toolbar's tab
   - **Ctrl-Q**    : Quit the app
   - **Alt-V**     : Toggle the view toolbar's tab
   - **Ctrl-R**    : Reload the app
   - **Ctrl-F**    : Toggle the full screen mode
   - **Ctrl-M**    : Minimize the app window
   - **Alt-H**     : Toggle the help toolbar's tab
   - **Alt-Ctrl-A**: Show the about page
   - **Alt-Ctrl-0**: Change language to French
   - **Alt-Ctrl-1**: Change language to English

### MacOS

   - **Cmd-Q**       : Quit the app
   - **Cmd-R**       : Reload the app
   - **Cmd-F**       : Toggle the full screen mode
   - **Cmd-M**       : Minimize the app window
   - **Option-Cmd-A**: Show the about page
   - **Option-Cmd-à**: Change language to French
   - **Option-Cmd-&**: Change language to English

## Allowed input files type

 - Reference Files<br>
   **image**: (.jpg|.jpeg|.png|.gif)  
   **document**: (.txt|.doc|.docx|.pdf|.xml)

 - Files to crypt/decrypt<br>
   **text**: (.txt)

 - Key files<br>
   **key file**: (.key)

## Generated files

### Windows

 - Keys<br>
   C:\\Users\\***{Username}***\\Library\\AppData\\Roaming\\CryptoLogique\\generated_files\\keys\\

 - Crypted<br>
   C:\\Users\\***{Username}***\\Library\\AppData\\Roaming\\CryptoLogique\\generated_files\\crypted\\

 - Decrypted<br>
   C:\\Users\\***{Username}***\\Library\\AppData\\Roaming\\CryptoLogique\\generated_files\\decrypted\\

### Linux

 - Keys<br>
   /home/***{Username}***/.config/CryptoLogique/generated_files/keys/

 - Crypted<br>
   /home/***{Username}***/.config/CryptoLogique/generated_files/crypted/

 - Decrypted<br>
   /home/***{Username}***/.config/CryptoLogique/generated_files/decrypted/

### MacOS

 - Keys<br>
   /Users/***{Username}***/Library/Application Support/CryptoLogique/generated_files/keys/

 - Crypted<br>
   /Users/***{Username}***/Library/Application Support/CryptoLogique/generated_files/crypted/

 - Decrypted<br>
   /Users/***{Username}***/Library/Application Support/CryptoLogique/generated_files/decrypted/
      