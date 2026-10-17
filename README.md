# Fedora Ricing — Sakura

Personalização do Fedora SwayFX e SDDM de GatesInDev. Lavanda e rosa, painéis
flat, transparência, blur e wallpapers complementares.

## Desktop — SwayFX

![Wallpaper do desktop](sakura-sway/wallpaper.png)

Waybar, Fuzzel, Foot, Mako, swaylock, atalhos e scripts de backup/restauração.
Janelas com bordas de 3 px e cantos de 18 px. Ilhas da Waybar sem contorno ou relevo.

```bash
cd sakura-sway
bash install.sh --no-packages
```

Use --no-packages se as dependências já estiverem instaladas. Para instalação
com DNF, consulte [as instruções completas](sakura-sway/LEIA-ME.md).
Execute como GatesInDev; o instalador usa sudo somente para pacotes.
Fedora tradicional com DNF; Fedora Atomic não é atendido.

## Login — SDDM

![Wallpaper do login](sakura-sddm/theme/background.png)

Tema Qt6 próprio: formulário à direita, relógio, seletor de sessão e painel
translúcido sem relevo. Teste a aparência antes de ativar:

```bash
cd sakura-sddm
bash preview.sh
sudo bash install.sh
sudo bash activate.sh
```

A prévia não autentica. A ativação cria backup e não reinicia o SDDM.
Consulte [dependências e restauração](sakura-sddm/LEIA-ME.md).

## Validação

Sintaxe Bash, configurações JSON/INI, SVG e rotinas de edição da configuração
SDDM verificadas durante a preparação. Desktop SwayFX e prévia SDDM confirmados
pelo usuário no Fedora. Autenticação real do tema SDDM ainda não confirmada.

Os wallpapers foram fornecidos pelo usuário; autoria e licença das imagens não
foram identificadas. Este repositório não atribui autoria dessas ilustrações
nem concede uma licença sobre elas.
