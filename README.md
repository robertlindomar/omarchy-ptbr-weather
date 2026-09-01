# Omarchy PT-BR — Clima

Tradução para português brasileiro do plugin `omarchy.weather` do Omarchy.

**ID do clone:** `robertlindomar.omarchy-ptbr.weather`

## O que é traduzido

- Textos e tooltips da interface em pt-BR
- Descrições do manifest quando aplicável
- Weather pill with detail popup

Tipos: bar-widget. Entry points: BarWidget.qml.

## Instalação

### Pelo Omarchy (recomendado)

1. Clone este repositório em `~/.config/omarchy/plugins/robertlindomar.omarchy-ptbr.weather/`
2. Valide: `omarchy plugin validate ~/.config/omarchy/plugins/robertlindomar.omarchy-ptbr.weather`
3. Habilite: `omarchy plugin enable robertlindomar.omarchy-ptbr.weather`
4. Reinicie o shell: `omarchy-restart-shell`

Ou use o instalador do monorepo principal (inclui todos os plugins):

```bash
git clone https://github.com/robertlindomar/omarchy-ptbr-github.git
cd omarchy-ptbr-github
./install.sh
```

### Manual

```bash
git clone https://github.com/robertlindomar/omarchy-ptbr-weather.git ~/.config/omarchy/plugins/robertlindomar.omarchy-ptbr.weather
omarchy plugin validate ~/.config/omarchy/plugins/robertlindomar.omarchy-ptbr.weather
omarchy plugin enable robertlindomar.omarchy-ptbr.weather
omarchy-restart-shell
```

## Remoção

```bash
omarchy plugin disable robertlindomar.omarchy-ptbr.weather
rm -rf ~/.config/omarchy/plugins/robertlindomar.omarchy-ptbr.weather
omarchy-restart-shell
```

Para remover todos os plugins pt-BR de uma vez, use o desinstalador do monorepo:

```bash
cd omarchy-ptbr-github
./uninstall.sh
```

## Licença e dependências

- **Licença:** MIT (ver `LICENSE`). Obra derivada do plugin upstream `omarchy.weather`.
- **Requisitos:** Omarchy instalado, Hyprland em execução, Quickshell (incluído no Omarchy).
- **Dependências externas:** nenhuma além do stack Omarchy/Quickshell.

## Origem

Plugin baseado em: `omarchy.weather`

Projeto principal: https://github.com/robertlindomar/omarchy-ptbr-github

## Aviso

Projeto comunitário e **não oficial**. Não modifique `/usr/share/omarchy`.

## Problemas / traduções faltando

Abra uma issue em https://github.com/robertlindomar/omarchy-ptbr-github/issues ou neste repositório.
