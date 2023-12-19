# Commands

Generic
    mkdir
    cd
    explorer.exe .
    ls

git --version
git clone https://github.com/Paiktis/demo-repo.git
git status
git add .
git add README.md
git commit -m "Title meesage" -m "Description message"


        (git config --global user.email "arapakisgeorgios@gmail.com")
        (git config --global user.name "gg")


git push origin



ssh-keygen -t ed25519 -C "arapakisgeorgios@gmail.com"
cat ~/.ssh/id_ed25519.pub
chmod 600 ~/.ssh/id_ed25519
sudo apt-get install keychain
eval $(keychain --eval --agents ssh id_ed25519)   ~ add this line on the ~/.bashrc file ~