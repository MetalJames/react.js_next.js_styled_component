Have to use node 16 version as there is some incompatability with node 18

https://collabnix.com/how-to-install-and-configure-nvm-on-mac-os/

1. Install Homebrew - /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

2. Install nvm - brew install nvm

3. Add nvm to your shell profile - source $(brew --prefix nvm)/nvm.sh

4. Install Node.js - nvm install node(only if you dont have it)

5. List available Node.js versions - nvm ls-remote

6. Install the desired version - nvm install 16

7. Use the installed version - nvm use 16