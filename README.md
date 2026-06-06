# Painel de Transmissão BRADO TV

Sistema de placar esportivo para transmissões ao vivo utilizando OBS Studio.

## Recursos

- Placar em tempo real
- Cronômetro de jogo
- Nome da competição
- Escudos dos times
- Atualização automática via LocalStorage
- Compatível com OBS Browser Source
- Hospedagem gratuita no GitHub Pages

## Estrutura do Projeto

```text
brado-tv-scoreboard/
├── index.html
├── overlay.html
├── style.css
├── script.js
├── overlay.js
├── LICENSE
├── README.md
├── .gitignore
└── assets/
```

## Instalação

Clone o repositório:

```bash
git clone https://github.com/seuusuario/brado-tv-scoreboard.git
```

Entre na pasta:

```bash
cd brado-tv-scoreboard
```

Abra o arquivo:

```text
index.html
```

em seu navegador.

## Publicação no GitHub Pages

1. Faça upload dos arquivos para um repositório GitHub.
2. Acesse:

Settings → Pages

3. Selecione:

Deploy from a branch

4. Escolha:

Main Branch

5. Clique em Save.

A URL será semelhante a:

```text
https://seuusuario.github.io/brado-tv-scoreboard/
```

## Utilização no OBS

Adicionar Fonte → Navegador

URL:

```text
https://seuusuario.github.io/brado-tv-scoreboard/overlay.html
```

Configurações recomendadas:

```text
Largura: 1920
Altura: 1080
FPS: 60
```

## Tecnologias

- HTML5
- CSS3
- JavaScript
- OBS Studio
- GitHub Pages

## Autor

João Paulo Verli

BRADO TV – A Casa do Futebol Brasileiro

YouTube:
https://www.youtube.com/@bradotvcasadofutebolbrasileiro

## Licença

Este projeto está licenciado sob a licença MIT.
