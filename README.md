# 🪙 Caderno Temático: Criptomoedas para Iniciantes — Do Blockchain à Segurança Digital
 
> Projeto desenvolvido como parte do Desafio de Projeto da [DIO](https://www.dio.me/) — explorando o NotebookLM como ferramenta de aprendizagem ativa com Inteligência Artificial.
 
---
 
## Sumário
 
- [Contexto e Objetivos](#contexto-e-objetivos)
- [Curadoria de Fontes](#curadoria-de-fontes)
- [Engenharia de Prompts e Cicatrizes](#engenharia-de-prompts-e-cicatrizes)
- [Miniguia de Estudo](#miniguia-de-estudo-entrega-final)
  - [Resumos Estruturados](#resumos-estruturados)
  - [Glossário](#glossario-de-conceitos)
  - [Prompts Reutilizáveis](#prompts-reutilizaveis)
---
 
## 🎯 Contexto e Objetivos
 
### Por que Criptomoedas para Iniciantes?
 
As criptomoedas deixaram de ser assunto exclusivo de programadores e especuladores. Com mais de **10 milhões de brasileiros** declarando posse de ativos digitais à Receita Federal em 2023 e o Brasil figurando entre os países com maior adoção de cripto no mundo, entender esse universo virou uma competência relevante — tanto financeira quanto tecnológica.
 
Mais do que um investimento, criptomoedas são a camada financeira de uma tecnologia revolucionária: o **blockchain**. Compreender como ela funciona envolve conceitos de **criptografia, segurança digital, descentralização e privacidade** — pilares fundamentais para qualquer profissional de tecnologia.
 
Este caderno temático une os mundos das **finanças introdutórias** e da **cibersegurança**, estudando como as criptomoedas funcionam, quais são seus riscos reais, como proteger ativos digitais e como a regulação brasileira está evoluindo sobre o tema.
 
### Objetivos de Estudo
 
| # | Objetivo | Indicador de Sucesso |
|---|----------|----------------------|
| 1 | Compreender o funcionamento técnico do blockchain e das criptomoedas | Conseguir explicar o que é um bloco, uma chave privada e uma transação para um leigo |
| 2 | Entender os principais tipos de criptomoedas e suas diferenças | Distinguir Bitcoin, Ethereum, stablecoins e tokens com exemplos práticos |
| 3 | Identificar os principais riscos financeiros e de segurança digital | Listar ao menos 5 vetores de ataque/golpe comuns no universo cripto |
| 4 | Conhecer as boas práticas de custódia e proteção de ativos digitais | Descrever a diferença entre carteira quente, fria e custodial |
| 5 | Entender o marco regulatório brasileiro de criptomoedas | Resumir o que a legislação brasileira exige de exchanges e investidores |
 
---
 
## 📚 Curadoria de Fontes
 
As fontes abaixo foram selecionadas por serem **abertas, técnicas e confiáveis**, cobrindo os aspectos financeiros, tecnológicos, de segurança e regulatórios das criptomoedas. Todas foram inseridas no NotebookLM para compor o caderno temático.
 
### Fonte 1 — Banco Central do Brasil: Moedas Virtuais e Riscos
- **Título:** Moedas Virtuais — Riscos e Implicações
- **Instituição:** Banco Central do Brasil (BCB)
- **Formato:** PDF / Nota Informativa
- **Link:** [https://www.bcb.gov.br/content/financasinternacionais/moeda_virtual/moedavirtual.pdf](https://www.bcb.gov.br/content/financasinternacionais/moeda_virtual/moedavirtual.pdf)
- **Por que escolhi:** Documento oficial do regulador financeiro brasileiro explicando o que são moedas virtuais, seus riscos financeiros e como o BCB posiciona o tema. Essencial para entender o olhar regulatório.
### Fonte 2 — Receita Federal: Tributação de Criptoativos
- **Título:** Perguntas e Respostas sobre Criptoativos — Receita Federal
- **Instituição:** Receita Federal do Brasil
- **Formato:** PDF / Página Web
- **Link:** [https://www.gov.br/receitafederal/pt-br/assuntos/orientacao-tributaria/declaracoes-e-demonstrativos/dirpf/criptoativos](https://www.gov.br/receitafederal/pt-br/assuntos/orientacao-tributaria/declaracoes-e-demonstrativos/dirpf/criptoativos)
- **Por que escolhi:** Fonte primária sobre como declarar, tributar e reportar operações com criptoativos no Brasil. Muitos investidores ignoram as obrigações fiscais — essa fonte cobre essa lacuna crítica.
### Fonte 3 — CVM: Alerta sobre Criptoativos e Pirâmides Financeiras
- **Título:** Alertas ao Investidor — Criptoativos e Esquemas Fraudulentos
- **Instituição:** Comissão de Valores Mobiliários (CVM)
- **Formato:** PDF / Página Web
- **Link:** [https://www.gov.br/cvm/pt-br/assuntos/noticias/2022/alertas-sobre-criptoativos](https://www.gov.br/cvm/pt-br/assuntos/noticias/2022/alertas-sobre-criptoativos)
- **Por que escolhi:** A CVM documenta casos reais de fraudes, pirâmides e esquemas Ponzi envolvendo criptomoedas no Brasil. Material essencial para o módulo de segurança e proteção contra golpes.
### Fonte 4 — NIST: Introdução à Criptografia e Segurança de Ativos Digitais
- **Título:** Introduction to Cryptography and Digital Security (NIST SP 800-175B)
- **Instituição:** National Institute of Standards and Technology (NIST — EUA)
- **Formato:** PDF
- **Link:** [https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-175Br1.pdf](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-175Br1.pdf)
- **Por que escolhi:** O NIST é referência mundial em cibersegurança. Este documento explica os fundamentos criptográficos que sustentam o blockchain — hashing, chaves públicas/privadas e assinaturas digitais — com rigor técnico e linguagem acessível.
### Fonte 5 — Lei nº 14.478/2022: Marco Legal dos Criptoativos no Brasil
- **Título:** Lei nº 14.478, de 21 de dezembro de 2022 — Marco Legal dos Criptoativos
- **Instituição:** Presidência da República / Congresso Nacional
- **Formato:** Texto Legal
- **Link:** [https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2022/lei/l14478.htm](https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2022/lei/l14478.htm)
- **Por que escolhi:** É a lei que regulamenta o mercado de criptoativos no Brasil, definindo o papel do Banco Central, as obrigações das exchanges e os direitos dos usuários. Conhecer a lei é parte essencial da educação financeira no setor.
---
 
## 🧪 Engenharia de Prompts e Cicatrizes
 
Esta seção documenta o processo de formulação de perguntas no NotebookLM, incluindo as variações testadas, os resultados obtidos e as dificuldades encontradas — mostrando o raciocínio por trás das respostas.
 
---
 
### 🔬 Experimento 1 — Fundamentos do Blockchain
 
#### Prompt inicial (vago)
> *"O que é blockchain?"*
 
**Resultado:** Definição correta mas genérica, sem referência às fontes inseridas e sem profundidade técnica sobre criptografia.
 
**❌ Problema identificado:** Prompt de uma linha gera resposta de enciclopédia — sem conexão com o material de estudo.
 
---
 
#### Prompt refinado
> *"Com base nos documentos do NIST e do Banco Central inseridos, explique como o blockchain garante a imutabilidade e a segurança das transações, abordando os conceitos de hash, chave pública e chave privada."*
 
**Resultado:** Resposta técnica e bem fundamentada:
- **Hash:** função matemática que transforma qualquer dado em uma sequência fixa de caracteres; alterar um bloco invalida toda a cadeia
- **Chave privada:** segredo do usuário usado para assinar transações (quem perde, perde acesso permanente)
- **Chave pública:** endereço visível na rede, derivado da chave privada via criptografia assimétrica
- Referenciou o NIST SP 800-175B (seções 3 e 5) e o documento do BCB
**✅ Aprendizado:** Citar documentos específicos + pedir conceitos técnicos nomeados gera respostas muito mais ricas e rastreáveis.
 
---
 
#### Prompt avançado (com analogia)
> *"Explique como funciona uma transação em Bitcoin — do início ao fim — usando uma analogia com o envio de uma carta registrada, com base nos materiais inseridos."*
 
**Resultado:** Analogia clara e didática: a chave privada é a caneta que assina a carta; a chave pública é o endereço do destinatário; os mineradores são os carteiros que validam a entrega; o blockchain é o livro de registro dos Correios que nunca pode ser apagado.
 
**✅ Aprendizado:** Pedir analogias com objetos do cotidiano é uma das melhores estratégias para fixar conceitos técnicos complexos.
 
---
 
### 🔬 Experimento 2 — Golpes e Segurança Digital
 
#### Prompt testado
> *"Com base nos alertas da CVM e do Banco Central inseridos, quais são os principais tipos de golpe envolvendo criptomoedas no Brasil? Para cada um, descreva o mecanismo de funcionamento e como se proteger."*
 
**Resultado:** Resposta estruturada cobrindo:
1. **Esquemas Ponzi/Pirâmide** — prometem rentabilidade fixa e alta (ex: casos documentados pela CVM)
2. **Phishing de carteiras** — sites falsos de exchanges que capturam credenciais
3. **Rug pull** — criadores de tokens abandonam o projeto após captar recursos
4. **Golpe do falso suporte** — contato fingindo ser suporte técnico de exchanges
5. **Pump and dump** — coordenação para inflar artificialmente o preço de um ativo
Referenciou casos reais documentados pela CVM em 2021-2022.
 
**✅ Aprendizado:** Pedir "mecanismo + proteção" para cada item força uma resposta acionável, não só descritiva.
 
---
 
#### Prompt de aprofundamento
> *"A Lei 14.478/2022 (Marco Legal dos Criptoativos) prevê algum mecanismo de proteção ao consumidor em caso de fraude ou falência de exchanges? Cite os artigos relevantes."*
 
**⚠️ Dificuldade encontrada:** O NotebookLM citou artigos corretamente, mas misturou a lei com regulamentações posteriores do Banco Central que não estavam no documento inserido. Foi necessário refinar.
 
**Prompt de correção:**
> *"Refaça a resposta citando apenas o que está no texto da Lei 14.478/2022 inserido. Indique o número do artigo para cada afirmação. Se a informação não estiver na lei, diga 'não previsto no documento inserido'."*
 
**✅ Resultado ajustado:** Resposta precisa com citação de artigos reais. Boa prática essencial para uso acadêmico e profissional.
 
---
 
### 🔬 Experimento 3 — Tributação e Obrigações Fiscais
 
#### Prompt testado
> *"De acordo com o material da Receita Federal inserido, quais são as obrigações do investidor brasileiro ao operar com criptoativos? Organize em: o que declarar, quando declarar e qual alíquota de imposto aplicar."*
 
**Resultado:** Tabela clara e organizada:
 
| Situação | Obrigação | Alíquota |
|----------|-----------|----------|
| Posse de cripto > R$ 5.000 | Declarar no IRPF como bem | Isento (só posse) |
| Venda < R$ 35.000/mês | Declarar, mas isento de IR | 0% |
| Venda > R$ 35.000/mês | Recolher DARF até último dia útil do mês seguinte | 15% a 22,5% |
| Operação em exchange estrangeira | Declarar como ativo no exterior | Regras específicas |
 
**✅ Aprendizado:** Pedir organização em categorias (o quê / quando / quanto) é excelente para temas com múltiplas regras interdependentes.
 
---
 
### 🔬 Experimento 4 — Tipos de Carteiras e Custódia
 
#### Prompt testado
> *"Explique as diferenças entre carteira quente (hot wallet), carteira fria (cold wallet) e carteira custodial, com foco nos riscos de segurança de cada uma. Use os documentos do NIST e do BCB como base."*
 
**⚠️ Dificuldade encontrada:** As fontes inseridas não cobriam carteiras de forma detalhada. O NIST abordou criptografia de chaves, mas não os tipos de carteira especificamente. O NotebookLM completou com conhecimento externo sem sinalizar.
 
**Lição documentada:** Identifiquei uma lacuna nas fontes para esse tema específico. Em uma segunda versão do notebook, adicionaria um whitepaper técnico sobre custódia de ativos digitais (ex: documentação da Ledger ou guia da Coinbase Institute) para cobrir esse gap.
 
**Prompt de contorno aplicado:**
> *"Com base apenas nos princípios de segurança de chaves criptográficas descritos no NIST SP 800-175B inserido, quais seriam os riscos de armazenar uma chave privada em um dispositivo conectado à internet versus offline?"*
 
**✅ Resultado:** Resposta ancorada na fonte disponível, com raciocínio correto sobre os riscos — mesmo sem citar "hot/cold wallet" diretamente.
 
---
 
### 💡 Lições Gerais de Troubleshooting
 
| Problema | Causa Raiz | Solução Aplicada |
|----------|------------|-----------------|
| Resposta genérica sem citar fontes | Prompt vago | Nomear documentos específicos + pedir conceitos técnicos |
| Mistura de informações externas | Instrução ambígua | Pedir citação de artigo/seção para cada afirmação |
| Lacuna temática nas fontes | Fontes não cobrem o subtema | Identificar o gap e planejar fontes complementares |
| Analogias confusas | Analogia mal especificada | Definir o objeto da analogia no próprio prompt |
| Dados legais imprecisos | Regulações são dinâmicas | Sempre cruzar com o texto legal original inserido |
 
---
 
## 📖 Miniguia de Estudo (Entrega Final)
 
### Resumos Estruturados
 
#### 🔗 Módulo 1: Como o Blockchain Funciona
 
O blockchain é um **banco de dados distribuído e imutável** — um livro-razão compartilhado por milhares de computadores ao redor do mundo, sem nenhuma autoridade central controlando.
 
**Componentes essenciais:**
 
- **Bloco:** pacote de dados contendo um conjunto de transações, um timestamp e o hash do bloco anterior
- **Hash:** impressão digital matemática única de um bloco; qualquer alteração muda completamente o hash e invalida a cadeia
- **Nó:** computador participante da rede que mantém uma cópia completa do blockchain
- **Consenso:** mecanismo pelo qual os nós concordam sobre qual versão da cadeia é válida (Proof of Work, Proof of Stake etc.)
**Por que é seguro?**
Para alterar uma transação passada, seria necessário recalcular o hash de todos os blocos seguintes **e** controlar mais de 50% dos nós da rede simultaneamente — o chamado **ataque de 51%**, computacionalmente inviável nas grandes redes.
 
---
 
#### 🔐 Módulo 2: Criptografia — A Base de Tudo
 
As criptomoedas só existem por causa da criptografia moderna. Dois conceitos são fundamentais:
 
**Criptografia de chave assimétrica:**
- Cada usuário possui um par de chaves: **pública** (compartilhável, é o seu endereço) e **privada** (secreta, nunca deve ser compartilhada)
- Uma transação é "assinada" com a chave privada e verificada com a chave pública
- Perder a chave privada = perder acesso permanente aos fundos
**Função Hash (SHA-256 no Bitcoin):**
- Transforma qualquer entrada em uma saída de tamanho fixo
- É irreversível: não é possível descobrir a entrada a partir da saída
- Qualquer alteração mínima na entrada gera uma saída completamente diferente
> ⚠️ **Regra de ouro:** *"Not your keys, not your coins"* — se você não controla sua chave privada, não controla suas criptomoedas de verdade.
 
---
 
#### 🪙 Módulo 3: Tipos de Criptoativos
 
| Tipo | Exemplo | Característica Principal | Risco |
|------|---------|--------------------------|-------|
| Criptomoeda nativa | Bitcoin (BTC) | Reserva de valor descentralizada | Alta volatilidade |
| Smart contract platform | Ethereum (ETH) | Executa contratos programáveis | Complexidade técnica |
| Stablecoin | USDT, USDC | Atrelada ao dólar — baixa volatilidade | Risco de lastro/regulação |
| Token de utilidade | Tokens de DeFi | Acesso a serviços em ecossistemas específicos | Alta volatilidade, risco de rug pull |
| Token de segurança | Security tokens | Representam ativos reais (imóveis, ações) | Regulação variável por país |
| CBDC | DREX (Brasil) | Moeda digital emitida pelo Banco Central | Centralização, privacidade |
 
---
 
#### 🔒 Módulo 4: Segurança Digital e Proteção de Ativos
 
**Tipos de carteira:**
 
| Carteira | Conexão | Segurança | Indicada para |
|----------|---------|-----------|---------------|
| **Custodial** (exchange) | Online | Baixa — terceiro guarda sua chave | Pequenos valores e iniciantes |
| **Hot Wallet** (software) | Online | Média — você controla a chave, mas online | Uso frequente |
| **Cold Wallet** (hardware) | Offline | Alta — chave nunca toca a internet | Armazenamento de longo prazo |
| **Paper Wallet** | Offline | Alta (se seguro) — chave impressa em papel | Armazenamento extremo |
 
**Principais vetores de ataque:**
 
1. **Phishing** — e-mails e sites falsos imitando exchanges reais
2. **SIM Swap** — clonagem de chip para burlar autenticação por SMS
3. **Malware de clipboard** — vírus que substitui endereços de carteira copiados
4. **Engenharia social** — falso suporte técnico pedindo seed phrase
5. **Rug pull** — criadores de projetos DeFi somem com os fundos captados
6. **Esquemas Ponzi** — prometem retornos fixos e altos, pagam com dinheiro de novos entrantes
**Checklist de segurança para iniciantes:**
- [ ] Nunca compartilhe sua seed phrase (12 ou 24 palavras) com ninguém
- [ ] Ative autenticação de dois fatores (2FA) por aplicativo, não por SMS
- [ ] Use exchanges regulamentadas e registradas no Brasil
- [ ] Verifique sempre o URL antes de inserir credenciais
- [ ] Mantenha o software da carteira sempre atualizado
- [ ] Guarde o backup da seed phrase offline, em local físico seguro
---
 
#### ⚖️ Módulo 5: Regulação Brasileira de Criptoativos
 
**Marco Legal (Lei 14.478/2022):**
- Define criptoativo como "representação digital de valor que pode ser negociada ou transferida por meios eletrônicos"
- Autoriza o Banco Central a regular e supervisionar exchanges (Prestadoras de Serviços de Ativos Virtuais — PSAVs)
- Estabelece obrigações de prevenção à lavagem de dinheiro (KYC/AML)
- Prevê punições para fraudes envolvendo criptoativos
**Obrigações do investidor pessoa física:**
 
| Situação | O que fazer |
|----------|-------------|
| Possui cripto > R$ 5.000 | Declarar no IRPF como "outros bens" |
| Vendeu < R$ 35.000 no mês | Declarar, mas isento de IR |
| Vendeu > R$ 35.000 no mês | Recolher DARF (15% a 22,5%) até o último dia útil do mês seguinte |
| Usa exchange estrangeira | Reportar mensalmente via e-Financeira se > R$ 30.000 |
 
---
 
### 📖 Glossário de Conceitos
 
| Termo | Definição |
|-------|-----------|
| **Blockchain** | Banco de dados distribuído e imutável, organizado em blocos encadeados cronologicamente. |
| **Bitcoin (BTC)** | Primeira criptomoeda descentralizada, criada em 2009 por Satoshi Nakamoto; funciona como reserva de valor digital. |
| **Ethereum (ETH)** | Plataforma blockchain que permite a execução de contratos inteligentes e aplicações descentralizadas (dApps). |
| **Hash** | Função matemática que transforma dados em uma sequência única de caracteres de tamanho fixo; base da imutabilidade do blockchain. |
| **Chave Privada** | Código secreto que prova a propriedade de um endereço blockchain e autoriza transações. Nunca deve ser compartilhada. |
| **Chave Pública** | Endereço derivado da chave privada, usado para receber transações. Pode ser compartilhado livremente. |
| **Seed Phrase** | Sequência de 12 a 24 palavras que serve como backup completo de uma carteira. Quem tem a seed, controla os fundos. |
| **Carteira Digital (Wallet)** | Software ou hardware que armazena chaves criptográficas e permite enviar/receber criptoativos. |
| **Hot Wallet** | Carteira conectada à internet — mais prática, mas mais vulnerável a ataques. |
| **Cold Wallet** | Carteira offline (hardware ou papel) — mais segura para armazenamento de longo prazo. |
| **Exchange** | Plataforma de compra, venda e troca de criptoativos (ex: Binance, Mercado Bitcoin, Coinbase). |
| **PSAV** | Prestadora de Serviços de Ativos Virtuais — nome legal das exchanges no Brasil após a Lei 14.478/2022. |
| **DeFi** | Finanças Descentralizadas — serviços financeiros (empréstimos, juros, câmbio) rodando em blockchain sem intermediários. |
| **Smart Contract** | Contrato autoexecutável programado em blockchain — executa automaticamente quando as condições são cumpridas. |
| **Stablecoin** | Criptomoeda com valor atrelado a um ativo estável, geralmente o dólar americano (ex: USDT, USDC). |
| **NFT** | Token Não Fungível — registro único em blockchain que comprova propriedade de um ativo digital. |
| **DREX** | Moeda digital do Banco Central do Brasil (CBDC) — versão digital do real em desenvolvimento. |
| **Proof of Work (PoW)** | Mecanismo de consenso que exige poder computacional para validar blocos (usado pelo Bitcoin). |
| **Proof of Stake (PoS)** | Mecanismo de consenso que usa depósito de criptomoedas como garantia para validar blocos (usado pelo Ethereum). |
| **Rug Pull** | Golpe em que os criadores de um projeto de criptomoeda somem com os fundos captados dos investidores. |
| **Phishing** | Ataque de engenharia social que usa sites/e-mails falsos para roubar credenciais de acesso. |
| **SIM Swap** | Golpe em que criminosos clonam o chip de celular da vítima para burlar autenticação por SMS. |
| **KYC** | Know Your Customer — processo de verificação de identidade obrigatório em exchanges regulamentadas. |
| **AML** | Anti-Money Laundering — conjunto de práticas para prevenção à lavagem de dinheiro. |
| **Ataque de 51%** | Cenário hipotético em que um agente controla mais da metade dos nós de uma rede, permitindo manipular transações. |
| **DARF** | Documento de Arrecadação de Receitas Federais — guia usado para recolher o IR sobre ganhos com cripto. |
 
---
 
### 🔁 Prompts Reutilizáveis
 
#### 🗂️ Para Revisão de Conteúdo
```
"Com base nos documentos inseridos, crie um quiz com 5 perguntas de múltipla 
escolha sobre [TEMA — ex: funcionamento do blockchain, tributação de cripto], 
com gabarito comentado e referência ao documento de origem de cada resposta."
```
 
```
"Resuma em até 6 tópicos os pontos mais importantes sobre [TEMA] presentes 
nos materiais inseridos, indicando a fonte de cada tópico."
```
 
```
"Quais são as 3 principais dúvidas que um iniciante em criptomoedas teria 
sobre [TEMA]? Responda cada uma com base nos documentos inseridos."
```
 
#### 🔍 Para Aprofundamento Técnico
```
"Explique o conceito de [CONCEITO — ex: função hash, proof of stake, 
chave assimétrica] como se eu fosse um estudante de tecnologia no 
primeiro semestre, usando uma analogia com algo do mundo físico."
```
 
```
"Compare [TECNOLOGIA A] e [TECNOLOGIA B — ex: Proof of Work vs Proof of Stake] 
em uma tabela com os critérios: segurança, consumo de energia, velocidade 
de transação, descentralização e exemplos de uso."
```
 
```
"Com base na Lei 14.478/2022 inserida, quais são as obrigações legais de 
uma exchange operando no Brasil? Cite o número do artigo para cada obrigação."
```
 
#### 🛡️ Para Segurança Digital
```
"Liste os 5 erros de segurança mais comuns que iniciantes cometem ao 
comprar criptomoedas pela primeira vez, com base nos alertas da CVM 
e do Banco Central inseridos."
```
 
```
"Crie um checklist de segurança para alguém que vai comprar sua primeira 
criptomoeda, abordando: escolha da exchange, proteção da conta, 
armazenamento e impostos."
```
 
```
"Descreva passo a passo como funciona o golpe de [TIPO — ex: phishing 
de carteira, rug pull, SIM swap] e quais sinais de alerta o investidor 
deve observar, com base nos documentos inseridos."
```
 
#### ⚠️ Para Checagem e Pensamento Crítico
```
"Refaça a resposta anterior usando apenas as informações contidas nos 
documentos carregados. Para cada afirmação, cite o documento e o artigo 
ou seção de onde a informação foi extraída."
```
 
```
"Há alguma contradição ou ponto de tensão entre os documentos inseridos 
sobre [TEMA — ex: regulação de cripto, riscos de stablecoins]? 
Identifique e explique cada um."
```
 
```
"Quais aspectos de [TEMA] não estão cobertos pelos documentos inseridos? 
Que fontes complementares eu deveria buscar para preencher essas lacunas?"
```
 
---
 
## 🛠️ Tecnologias e Ferramentas Utilizadas
 
- [NotebookLM](https://notebooklm.google.com/) — Google (IA para estudo com base em fontes)
- [GitHub](https://github.com/) — Repositório e documentação do projeto
- Fontes abertas do **Banco Central do Brasil**, **Receita Federal**, **CVM**, **NIST** e **Lei Federal 14.478/2022**
---
 
## 🚀 Como Replicar Este Projeto
 
1. Acesse o [NotebookLM](https://notebooklm.google.com/) com sua conta Google
2. Crie um novo notebook chamado **"Criptomoedas para Iniciantes"**
3. Faça o upload dos PDFs das 5 fontes listadas acima (ou insira os links)
4. Comece com o prompt exploratório: *"Quais são os principais conceitos técnicos presentes nos documentos inseridos?"*
5. Avance para os prompts de segurança e regulação
6. Documente suas descobertas, dificuldades e aprendizados no seu README
---
 
## 👨‍💻 Autor
 
Desenvolvido como entrega do Desafio de Projeto da **DIO — Digital Innovation One**
 
> *"O blockchain não é sobre Bitcoin. É sobre a possibilidade de remover intermediários de confiança de qualquer sistema — e isso muda tudo."*
 
---
 
## 📄 Licença
 
Este projeto está sob a licença MIT. Sinta-se livre para usar, adaptar e compartilhar com os devidos créditos.
