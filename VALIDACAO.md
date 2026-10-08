# Validação da proposta Clínica Cb

Verificação realizada em 8 de outubro de 2026.

- HTML: IDs únicos, âncoras existentes, imagens com texto alternativo e recursos locais presentes.
- Recursos locais: respostas HTTP 200 no caminho `/clinica-cb/`.
- JavaScript: verificação de sintaxe com Node.js.
- Navegador: testes em desktop (1440 px), tablet (768 px) e celular (390 px), sem rolagem horizontal nos tamanhos confirmados.
- Menu móvel: abre e fecha, atualiza `aria-expanded`, fecha ao navegar e por Escape; Escape devolve o foco ao botão.
- Galeria: abre foto, fecha pelo botão e por Escape, devolve o foco à foto de origem.
- FAQ: expansão e fechamento confirmados.
- WhatsApp: todos os links apontam ao número 5551994221484, com mensagens codificadas; não foram enviadas mensagens.
- Links de telefone, Instagram e Google Maps conferidos no HTML; não foram realizadas chamadas nem contatos externos.
- Console do navegador: sem registros de erro na conferência.
- Contraste: cores principais de texto atendem ao mínimo de 4,5:1 (resultados abaixo).
- Movimento reduzido: CSS desativa animações/transições e rolagem suave quando solicitado pelo sistema.

## Contraste calculado

- green/cream: 10.73:1
- clay/cream: 5.42:1
- muted/cream: 5.16:1
- cream/green: 10.73:1

## Publicação

Arquivos preparados para `gusdias-coder/clinica-cb`, branch `main`, raiz, GitHub Pages. A publicação e a verificação do endereço público dependem da autenticação na conta. Este relatório não declara que o site já foi publicado.

## Limites

Não houve auditoria completa com leitor de tela ou validação operacional pela clínica. O tamanho de 320 px não foi confirmado devido a divergência na dimensão reportada pelo navegador durante o teste; as conferências responsivas confirmadas foram 390, 768 e 1440 px. Serviços e horários são os dados fornecidos pelo solicitante.
