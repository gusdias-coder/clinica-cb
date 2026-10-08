# Clínica Cb — proposta demonstrativa

Site estático em português brasileiro para apresentar a Clínica Cb, na Cidade Baixa, Porto Alegre. Design original em verde profundo, creme e terracota, inspirado nos conceitos de apresentação de clínicas veterinárias, sem reutilizar código, textos ou identidade da referência Zoomed.

**Destino de publicação:** `https://gusdias-coder.github.io/clinica-cb/`

## Como visualizar

Abra `index.html` no navegador ou sirva a pasta por HTTP:

```bash
python -m http.server 8000
```

Depois, abra `http://localhost:8000`. Não há instalação de dependências nem compilação.

## Publicar no GitHub Pages

1. Crie o repositório público **clinica-cb** na conta **gusdias-coder**.
2. Envie o conteúdo desta pasta à raiz do repositório, incluindo `index.html`, `assets/` e `.nojekyll`. Não envie a pasta como uma subpasta adicional.
3. Em **Settings → Pages**, selecione **Deploy from a branch**, branch **main**, pasta **/(root)** e salve.
4. Aguarde a publicação. O site ficará no endereço indicado acima. Só considere publicado após verificar o endereço público.

Documentação: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Como editar

- **Textos, serviços, horários, endereço e nota:** `index.html`.
- **Cores, tipografia, layout e tamanhos de tela:** `styles.css`, com as cores em `:root`.
- **WhatsApp:** número e mensagens em `script.js`. Atualize também os links de fallback e de telefone em `index.html`.
- **Fotos:** `assets/images/`. Preserve os nomes ou atualize os caminhos, dimensões e textos alternativos no HTML.
- **Imagem de compartilhamento:** `assets/images/social-card.jpg`, tamanho 1200 × 630.
- **Ícone:** `assets/favicon.svg`.
- Se mudar o usuário ou nome do repositório, atualize as URLs de `canonical`, `og:url` e `og:image` no HTML.

Os caminhos dos recursos são relativos, compatíveis com GitHub Pages em `/clinica-cb/`. As fontes são locais, sem consultas ao Google Fonts na navegação. As licenças das fontes estão em `assets/fonts/`.

## Conteúdo e limites da demonstração

- O rodapé identifica o site como **proposta demonstrativa**, não como site oficial.
- Serviços, horários, telefone e endereço foram fornecidos pelo solicitante. Não houve validação operacional pela clínica.
- A nota **4,8** e o total de **198 avaliações** são os dados fornecidos para esta proposta; não existe atualização automática ou integração com Google Reviews.
- Não foram inventados depoimentos, nomes de clientes, integrantes da equipe, registros profissionais, anos de experiência ou estatísticas.
- As fotos foram obtidas dos oito links Google fornecidos pelo solicitante, em resolução maior, otimizadas em WebP. Não foram copiadas fotos da Zoomed. O projeto inclui apenas as fotos usadas no site; para uma futura publicação oficial, a clínica deve confirmar os direitos de uso dos registros.
- A identidade tipográfica e o ícone são conceitos de apresentação, sem alegação de marca oficial.
- O contato por WhatsApp abre uma mensagem; não envia automaticamente nem confirma consulta. Os botões de telefone usam `tel:`.
- Não há backend, pagamentos, conta de paciente, cookies de rastreamento, coleta de formulários ou armazenamento de dados pessoais. Mapas e Instagram são links externos; não existem embeds.
- Urgências dependem de confirmação de disponibilidade. Não é anunciado atendimento 24 horas.
- Informações de programas municipais remetem ao canal **156**. Não há inscrição, promessa de benefício nem confirmação de credenciamento atual.

## Fontes de referência

- Referência de conceito: https://www.clinicazoomed.com.br/
- Instagram informado: https://www.instagram.com/clinicacidbaixa/
- Publicação da Prefeitura sobre programas de castração: https://prefeitura.poa.br/gca/noticias/prefeitura-abre-inscricoes-para-castracao-de-caes-e-gatos
- Fontes: Manrope e Cormorant Garamond, distribuídas sob SIL Open Font License.

## Interações e acessibilidade

Menu móvel com `aria-expanded` e fechamento por Escape; galeria com diálogo nativo, Escape, botão de fechar e retorno do foco; perguntas frequentes em `details/summary`; link para pular ao conteúdo; foco visível, textos alternativos e suporte a `prefers-reduced-motion`.

O conteúdo e os links de contato continuam disponíveis sem JavaScript. Menu móvel e ampliação de fotos usam JavaScript. Consulte `VALIDACAO.md` para os resultados da conferência.
