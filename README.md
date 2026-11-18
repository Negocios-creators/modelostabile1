# Stabille Advogados — site (modelo 1)

Site de página única, cinematográfico, feito com o método da Aula 14 do Vibehub ("Como Criar Sites Premium",
skills `criar-site-motion` + `briefing-de-site` + `site-motion-starter`). HTML, CSS e JS puros, sem build.

## Rodar local

```bash
python -m http.server 8080
```

Abrir `http://localhost:8080` (nunca com dois cliques / `file://`, o hero fica preto).

## Arquivos

| Caminho | O que é |
|---|---|
| `index.html` | todas as seções, na ordem do funil |
| `css/style.css` | design system no `:root` (paleta tirada do escritório real) |
| `js/main.js` | motor: Lenis + GSAP, hero em sequência de frames, galeria horizontal, contadores |
| `assets/frames/` | 120 frames do hero (câmera se aproximando da estátua da Justiça) |
| `assets/video/hero.mp4` | versão do hero para celular · `accent.mp4` fundo dos depoimentos |
| `assets/img/logo-*.svg` | **logo provisória** (arco + S itálico, Cormorant Garamond) |
| `assets/img/escritorio-*.jpg` | fotos reais do escritório (Google Meu Negócio), com a logo nova aplicada nas TVs |
| `assets/img/henrique-stabile.jpg` | foto do Dr. Henrique, do site antigo |

## Origem do conteúdo

- Site antigo sepadv.com.br (home e Quem somos) e perfil do Google do escritório (nota 4,8, 29 avaliações, horário, endereço, fotos).
- Tudo que envolvia o Dr. Fernando Pessoa foi retirado: foto do hero antigo, card de sócio, OABs dele e o depoimento "Dr. Fernando".
- Depoimentos copiados palavra por palavra. Ficaram de fora avaliações de pessoas da equipe.
- Vídeos do hero e dos depoimentos: Pexels (licença livre), ids 8061667 e 8061655, com tratamento de cor.

## Pendências com o cliente

- [ ] Logo definitiva (a atual é provisória)
- [ ] Grafia da marca: o site usa **Stabille Advogados** (pedido), mas o sobrenome registrado na OAB é **Stabile**
- [ ] Confirmar o WhatsApp do escritório novo (hoje: (62) 9 8165-8049, o mesmo do S&P) e o fixo (62) 3010-0113
- [ ] CNPJ e registro da sociedade na OAB da nova banca (o 1.290 e o CNPJ 18.665.561/0001-75 são da Stabile e Pessoa e ficaram de fora)
- [ ] Foto do Dr. Henrique em alta resolução (a atual tem 377 px)
- [ ] Confirmar se os números "14 anos" e "+20 mil clientes" continuam válidos para a banca nova
- [ ] Texto de honorários no FAQ
- [ ] Renomear o perfil do Google Meu Negócio quando a marca nova sair (o link de avaliações aponta pra ele)
- [ ] Domínio próprio
