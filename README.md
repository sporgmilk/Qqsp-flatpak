# Qqsp-flatpak
A flatpak build for Qt Quest Soft Player

### Prerequisite 
  git

  flatpak 

  flathub

  internet connection

### Build instructions:

    git clone https://github.com/sporgmilk/Qqsp-flatpak.git

    cd Qqsp-flatpak
    
    flatpak install org.flatpak.Builder

    flatpak run org.flatpak.Builder --force-clean --user --install-deps-from=flathub \
    --repo=repo --install builddir  io.Sonnix.Qqsp.yml
