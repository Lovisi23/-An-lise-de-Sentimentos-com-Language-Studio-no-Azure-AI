# Analise-de-Sentimentos-com-Language-Studio-no-Azure-AI
Este repositório contém anotações práticas do laboratório de IA com foco em análise de fala e linguagem natural utilizando as ferramentas da Microsoft: **Speech Studio** e **Language Studio**.

---

## 🔹 Etapas Realizadas

### 1. Introdução (Aulas Teóricas)
As primeiras aulas foram teóricas, abordando os conceitos de IA aplicada à linguagem e fala. Nenhuma prática foi realizada até esse ponto.

### 2. Speech Studio - Transcrição de Fala

- Acesse o site: https://speech.microsoft.com/portal
- Va na aba de configurações, caso nao tenha nenhum recurso, crie um novo reurso, selecione sua assinatura, de um nome a ele e coloque a regiao e padrão caso nao estejam selecionadas já
- selecionar a conversão de fala em texto
- Fazer upload do arquivo
- Ocorre a transcrição automatica do audio
- O sistema abre uma aba "próximas etapas", dando exemplos de onde esse recurso pode ser utilizado

**Insight:** a ferramenta é eficiente para converter fala em texto e pode ser usada em aplicações como legendas, assistentes virtuais e acessibilidade.

### 3. Language Studio - Análise de Texto

- Acesse novamente: https://ai.azure.com
- Criação de um projeto no Language Studio.
- Testes com textos simulados para:
  - Extração de entidades
  - Frases-chave
  - Sumarização
  - Análise de sentimentos

### 🛠️ Como Criar um Projeto no Language Studio

#### 1. Criar o Recurso de Linguagem no Azure

- No portal do Azure, procure por "Serviço de Linguagem".
- Crie um recurso, defina a região e selecione o plano gratuito (F0) se disponível.

#### 2. Acessar o Language Studio

- Vá para: [https://language.cognitive.azure.com/](https://language.cognitive.azure.com/)
- Faça login com sua conta Azure e selecione o recurso que criou.

#### 3. Criar o Projeto

Escolha o tipo de projeto:
- **Custom NER:** extrair nomes, locais, etc.
- **Classificação de Texto:** categorizar textos (ex: spam, feedback).
- **CLU:** entender intenções em conversas.
- **Perguntas e Respostas:** responder a perguntas com base em documentos.

Configure o idioma e nome do projeto.

#### 4. Importar e Rotular os Dados

- Carregue textos e rotule manualmente os trechos relevantes (ex: "Rio" como Local).
- A rotulagem deve ser precisa e consistente para bons resultados.

#### 5. Treinar e Implantar

- Treine o modelo com os dados rotulados.
- Avalie o desempenho (precisão, recall etc.).
- Implemente e gere um **endpoint** com chave de acesso para uso externo.

---

---

## 📘 Conclusão

Mesmo com uma introdução teórica longa, as ferramentas se mostraram práticas e úteis na etapa de laboratório. O Speech Studio foi eficaz na transcrição de áudio, e o Language Studio forneceu bons resultados na análise textual.

---

## 🔗 Links úteis

- [Lab de Speech Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)  
- [Lab de Language Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)
