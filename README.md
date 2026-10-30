# brewfile
Lista de pacotes recomendados a serem instalados via Homebrew no Linux e no macOS.

**Informações**:
- Se não utilizar alguma imagem do [Universal Blue](https://universal-blue.org/), instale antes o [Homebrew](https://brew.sh/).
- Os programas estão divididos em **programas de linha de comando** e **programas gráficos** e, dentro de cada parte, por categoria e em ordem alfabética, sem distinção entre `brew`, `cask` e `flatpak`.
- Cada linha traz, em comentário, o nome do programa e uma breve descrição.
- Nos Brewfiles do GNOME e do KDE Plasma, Claude, ChatGPT e Tessera vêm do [FlatPark](https://flatpark.org/), e não do Flathub. Como o `brew bundle` instala os Flatpaks no sistema (`--system`), adicione antes o repositório do FlatPark em modo systemwide:
  ```sh
  flatpak remote-add --if-not-exists flatpark https://dl.flatpark.org/flatpark.flatpakrepo
  ```
- Certifique-se de excluir ou comentar o que não for necessário.
- Uso: `brew bundle --file [caminho para o Brewfile]`
- Documentação: https://docs.brew.sh/Brew-Bundle-and-Brewfile

**Listas existentes**:
- `gnome.Brewfile`, com aplicativos recomendados para o Linux no ambiente desktop GNOME (Bazzite e Bluefin);
- `plasma.Brewfile`, com aplicativos recomendados para o Linux no ambiente desktop KDE Plasma (Bazzite e Aurora);
- `macos.Brewfile`, com aplicativos recomendados para o macOS; e
- `jogos.Brewfile`, com jogos e launchers recomendados para o Linux, todos em Flatpak.
