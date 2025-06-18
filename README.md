**Installing and Using CS50 Library**
1. Close VS Code.
2. Go to [https://github.com/cs50/libcs50](https://github.com/cs50/libcs50) and download the zip file.
3. Extract to Desktop.
4. Go to “/Users/USERNAME/Desktop/libcs50-main/src” and copy all 2 files. (cs50.c and cs50.h)
5. Open VS Code, create a C file (example, hello.c) and write #include <stdio.h> and right click <stdio.h>.
6. Click “Go to definition” and right click the file.
7. Click “Show in finder” and paste 2 files that we copied.
8. When you write a code, remember to write #include <cs50.h> or “cs50.h”, <cs50.c>, “cs50.c”
9. For creating a binary file from a C file, write “cc (c file name).c -o (binary file name) cs50.c” like “cc hello.c -o hello cs50.c”.
10. Then for run the file, write ./(binary file name) to the terminal.

11. Open MacOS terminal and paste "/Users/USERNAME/Desktop/libcs50-main".
12. Paste "sudo make install".
**Installing cs50.dev Extensions**
13. Download “vscode-extensions-export.zip”
14. Extract to Desktop.
15. If you want to install only special CS50 extensions, just delete others from the txt file and continue with the next step.
16. Open MacOS terminal and write “cd” and paste the directory of the “install-extensions.sh” file. Like “cd /Users/USERNAME/Desktop/vscode-extensions-export”
17. Paste “chmod +x install-extensions.sh” and hit enter.
18. Paste “./install-extensions.sh” and hit enter.

**Installing Special cs50.dev Extensions**

You can install “cs50.ddb50”(CS50 Duck Debugger) on the VS Code Marketplace.

You can install “cs50.extension-uninstaller”(Extension Uninstaller) on the VS Code Marketplace.

Paste “npm install -g @vscode/vsce” to the MacOS terminal.

**For install cs50.cs50**
  
Paste these codes to the MacOS terminal.

cd

git clone https://github.com/cs50/cs50.vsix.git

cd cs50.vsix

npm install

./node_modules/@vscode/vsce/vsce package

code --install-extension cs50-0.0.1.vsix

**For install cs50.design50**

Paste these codes to the MacOS terminal.

cd

git clone https://github.com/cs50/design50.vsix.git

cd design50.vsix

npm install

npx vsce package

code --install-extension design50-1.0.0.vsix

- You can change 1.0.0 version.

**For install cs50.explain50**

Paste these codes to the MacOS terminal.

cd

git clone https://github.com/cs50/explain50.vsix.git

cd explain50.vsix

npm install

npx vsce package

code --install-extension explain50-1.0.0.vsix

- You can change 1.0.0 version.

**For install cs50.phpliteadmin**

Paste these codes to the MacOS terminal.

cd

git clone https://github.com/cs50/phpliteadmin.vsix.git

cd phpliteadmin.vsix

npm install

npx vsce package

code --install-extension phpliteadmin-0.0.1.vsix

- You can change 0.0.1 version.

**For install cs50.style50**

Paste these codes to the MacOS terminal.

cd

git clone https://github.com/cs50/style50.vsix.git

cd style50.vsix

npm install

npx vsce package

code --install-extension style50-0.0.1.vsix

• ⁃ You can change 0.0.1 version.
