# Site de exemplo · Promoção da Qualidade e Equidade na Educação Infantil

Protótipo do site do projeto **Promoção da Qualidade e Equidade na Educação Infantil: consulta nacional e monitoramento do uso de indicadores de qualidade à luz dos PNQEEI (2024)**. Realização: MEC/Governo Federal. Apoio: UFC.

É um rascunho para mostrar a proposta. Nenhuma resposta, cadastro ou adesão é enviada ou guardada em servidor.

## Como abrir

Abra `index.html` no navegador, ou sirva a pasta:

```
python -m http.server 8765
```

e acesse http://localhost:8765.

## O que tem

Um arquivo, quatro telas (trocadas pelo `#` do endereço):

- `#inicio`: apresentação do projeto, as duas ações, chamada para a consulta e para a adesão, quem participa e como participar.
- `#cadastro`: cadastro completo, com validação de CPF, CEP e data.
- `#consulta`: questionário às redes estaduais e do DF sobre o uso do INDIQUE e o alinhamento aos PNQEEI. **Versão preliminar, em elaboração.** Tem lógica de salto, limites de escolha, matriz, checagem dos campos numéricos e rascunho salvo só no navegador (sem nome, e-mail e telefone).
- `#adesao`: termo de adesão (minuta) para secretárias e secretários de educação. Gera o selo, o certificado A4 (PDF e PNG), um post 1080 × 1080 e um story 1080 × 1920, todos no próprio navegador.

Todo o visual é desenhado em código (CSS, SVG e canvas), sem imagens. As cores e os componentes seguem o design system v3 no Figma.

## Pendências

- Questionário em elaboração: numeração do Bloco 2, enunciados e tipos de resposta a revisar; tempo estimado a definir.
- Texto do termo de adesão sujeito a revisão jurídica e validação pelo MEC.
- Assinatura real (gov.br), registro em servidor e página pública de verificação do código.
- Logos oficiais (hoje são caixas tracejadas).
