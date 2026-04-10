# Workflow: Presentation Builder (Construtor de Apresentações)

Este workflow define o passo a passo rigoroso para a orquestração e criação de apresentações visuais de alta qualidade. As apresentações devem nascer como código, estruturadas e planejadas para garantir um design premium e exportação perfeita para múltiplos formatos.

## 📁 Diretrizes de Versionamento e Estrutura de Pastas

Antes de qualquer linha de código ou geração, crie o ambiente de trabalho do projeto de forma isolada e organizada.

O workflow DEVE seguir estritamente o modelo de caminhos abaixo:

`docs/Apresentacoes/[Nome-do-Projeto]/`
*   `src/`: Pasta obrigatória para guardar todo o código fonte (arquivos `.html`, `.css`, etc.), assets de imagem originais, referências e downloads. Tudo o que "constrói" a apresentação fica aqui.
*   `build/`: Pasta obrigatória dedicada **exclusivamente** ao resultado final formato que o usuário pediu.

**🚨 Regra de Imutabilidade e Versionamento Final:** 
O arquivo final gerado em `build/` deve sempre possuir a versão explícita no nome, ex: `[Nome-do-Projeto]_v1.pdf`. **NUNCA** sobrescreva um arquivo final. Se o usuário pedir um ajuste, você deverá gerar o projeto atualizado e salvar como `[Nome-do-Projeto]_v2.pdf`, e assim sucessivamente.

---

## 🕵️ Passo 1: Coleta de Informações, Estilo e Assets

Inicie um diálogo interativo para definir o escopo completo.

1.  **O Propósito Real:** Entenda o que o usuário quer. É um relatório de dados? Uma análise de perfil? Apresentação de serviço? Reunião gerencial? 
2.  **O Formato Final e Resolução:** Pergunte qual é a saída esperada (Web interativa, PDF estático, slides em PNG, PPTX exportado). Se for imagem/PDF, questione se ele exige alta resolução (ex: 4K, 300dpi). Sempre ofereça sugestões.
3.  **Tratamento de Assets (Logos e Imagens):** Solicite todos os arquivos visuais pertinentes de antemão.
    *   *Análise Crítica:* Analise as imagens para fundos inadequados. Sugira adaptações se a imagem for cortar o layout (ex: "Sua logo tem fundo branco, recomendo usarmos ela numa caixa neutra ou aplicar remoção de fundo").
    *   *Efeitos Visuais:* Sugira paletas e overlays de cor unificadores para que as fotos amadoras pareçam estar no mesmo *moodboard*.
4.  **Cores e Tipografias Inovadoras:** Colete a cor principal da marca do usuário, mas não o limite a fontes batidas. Use seus conhecimentos de design avançado para **sugerir combinações de fontes criativas** (ex: *Outfit* para tech moderna, *Playfair* para sofisticação, *Plus Jakarta Sans* para clareza corporativa).

## ✍️ Passo 2: O Processo de Copy, SEO e Humanização Extrema

Nesta etapa, você vai processar os dados cedidos pelo usuário e preparar todos os textos e componentes textuais.

1.  **Estruturação Semântica:** Organize as informações na cadência clássica de uma narrativa de apresentação (Abertura, Dores, Soluções, Dados, Encerramento).
2.  **Filtro de Humanização Rígido:** 
    *   A copy **não pode** parecer gerada por IA.
    *   **PROIBIDO** o uso de marcadores como travessão longo duplo ("—").
    *   **PROIBIDO** o uso de emojis na estrutura do design final.
3.  **Ícones no Lugar de Emojis:** Se o usuário solicitar símbolos para dar dinamismo (checkmarks, ícones de alerta), sugira bibliotecas de ícones de interface profissionais (Ex: Lucide Icons, Phosphor Icons ou FontAwesome) e peça para o usuário validar qual estilo ele prefere.
4.  **SEO e Best Practices:** Se a escolha da etapa 1 tiver sido o formato HTML/Web, inclua todos os fundamentos de SEO (`seo-fundamentals` e `copywriting` tags semânticas, meta descrições, acessibilidade de imagem).

## 🎨 Passo 3: O Processo de Criação (Código e Design)

Implemente visualmente o que foi acordado utilizando as diretrizes recolhidas.

1.  **Skills e Regras de Design:** Aplique agressivamente conhecimentos do `@ui-ux-pro-max` e `@frontend-design` para criar uma estrutura moderna de alto padrão. Preocupe-se com respiros (whitespace) e alinhamentos.
2.  **Atenção ao Formato de Exportação:**
    *   Se for destinado a **PPTX / PDF / PNG**: Use HTML/CSS padronizado mantendo proporção 16:9 (`aspect-ratio: 16/9;`) para telas ou A4. Cuide de `page-break` em CSS para guiar cortes de impressões/telas e desabilite scroll ou animações incompatíveis com arte estática.
    *   Se for unicamente destinado a **Página HTML ou Web App**: Aqui você deve priorizar interatividade. Neste cenário exclusivo, o uso de ferramentas de suporte web (`artifacts/web-artifacts-builder`) é plenamente autorizado para ganho de agilidade e apresentação.
3.  Todo o código criado e mantido deverá ser enclausurado na pasta `src/` criada no pré-workflow.

## 🔎 Passo 4: Confirmação e Pente-Fino de Integridade

O código e os arquivos não vão para renderização sem passar por auditoria rigorosa.

1.  **Double-Check do Pedido Original:** Leia atentamente toda a spec pedida na Etapa 1 e garanta que 100% dos tópicos foram supridos.
2.  **Caça aos Erros de Design (Bug Tracking Visual):**
    *   Verifique visualmente transbordamento de divs.
    *   Verifique contraste do texto com o fundo (WCAG guidelines).
    *   Audite novamente a copy de placeholder para confirmar ausência total de emojis e travessões de IA.
    *   Se imagens externas tiverem sido injetadas, valide se quebram com variações de tela.
3.  Comunique-se com o usuário e ofereça um review prévio.

## ⚙️ Passo 5: Geração de Alta Qualidade e Fechamento

Transforme o projeto base em seu estágio visual puro no formato final exigido pelo cliente.

1.  Execute, orquestre por scripts ou oriente o processo de conversão do HTML limpo presente no terminal para PDF, PNG 4K ou arquivo correspondente usando as ferramentas/bibliotecas localmente disponíveis (ex: dom-to-image, puppeteer css print, html2pdf, etc).
2.  Mova o arquivo convertido para a pasta `build/`.
3.  Gere o arquivo sob a estrutura de versão (ex: `docs/Apresentacoes/MeuProjeto/build/MeuProjeto_v1.pdf`).
4.  Se o usuário não estiver satisfeito e exigir reformulações profundas de texto e layout, aplique a refatoração no `src/`, gere novamente a conversão e salve a nova iteração terminantemente como `_v2`.
5.  Entregue o caminho absoluto do diretório para o usuário.
