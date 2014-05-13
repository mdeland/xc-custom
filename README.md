xc-custom
=========

Your custom roles &amp; Configuration

git clone https://github.com/osxc/xc-boot.git ~/src/github.com/osxc/xc-boot
cd ~/src/github.com/osxc/xc-boot
sh boot.sh github.com/mdeland/xc-custom
cd ~/src/github.com/mdeland/xc-custom
PYTHONIOENCODING='utf-8' HOMEBREW_CASK_OPTS="--appdir=/Applications" ansible-playbook all.yml --extra-vars "user=mdeland" --ask-sudo-pass
