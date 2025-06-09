
# # Azure AI - Laboratório de Fala e Linguagem Natural

Este repositório contém anotações e insights obtidos durante o laboratório prático utilizando o **Azure Speech Studio** e o **Azure Language Studio**, conforme desafio proposto pela [DIO - Digital Innovation One](https://www.dio.me/).

## 🔍 Objetivo

Explorar as ferramentas da Azure para:
- Análise de fala (Speech Studio)
- Processamento de linguagem natural (Language Studio)
- Compreensão de linguagem coloquial
- Análise de sentimentos
- Geração de respostas automáticas com IA

## 🗣️ Speech Studio

### O que foi feito:
- Criação de um projeto de **Conversão de Texto em Fala (Text-to-Speech)**
- Testes com diferentes vozes e idiomas
- Exportação de áudio em MP3
- Exploração da funcionalidade de **Reconhecimento de Fala (Speech-to-Text)**

## 🧠 Language Studio

### O que foi feito:
- Análise de sentimentos em textos em português
- Identificação de entidades nomeadas (pessoas, lugares, organizações)
- Criação de projetos de **Classificação de Texto Personalizada**
- Testes com **Resposta a Perguntas (QnA)** e linguagem informal.

## ✨ Aprendizados

- A integração das ferramentas Azure facilita muito a prototipação de soluções com IA.
- A interface gráfica do Language Studio permite testar modelos NLP sem necessidade de código.
- O Speech Studio é extremamente poderoso para aplicações de acessibilidade, atendimento automatizado e assistentes virtuais.

## 📁 Recursos

- [Azure Speech Studio](https://speech.microsoft.com/)
- [Azure Language Studio](https://language.cognitive.azure.com/)
- [Laboratório Oficial - Microsoft Learn](https://learn.microsoft.com/)


## 🚀 Como Reproduzir

1. Acesse os links do Speech e Language Studio.
2. Crie seus próprios projetos com base nas instruções das aulas.
3. Documente tudo no seu GitHub, com prints e anotações.

# Anotações Técnicas 

# Speech Studio - Notas Técnicas

## Text-to-Speech
- Idioma testado: pt-BR
- Vozes testadas: Francisca, Antônio
- Configurações: Velocidade ajustada para 1.2x
- Exportação: formato MP3

## Speech-to-Text
- Upload de áudio via microfone e arquivo
- Resultado com alta precisão para fala clara
- Reconhecimento limitado para ruídos de fundo

# Language Studio - Notas Técnicas

## Análise de Sentimentos
- Textos analisados: feedback de usuários e reviews
- Sentimentos identificados: positivo (78%), negativo (15%), neutro (7%)

## Entidades Reconhecidas
- Pessoa: "Carlos Silva"
- Local: "São Paulo"
- Produto: "Azure AI"

## Perguntas e Respostas
- Texto base: documentação de um serviço
- Pergunta: "Como configurar o Speech Studio?"
- Resposta automática gerada: "Você pode configurar acessando a aba 'Projetos' e clicando em 'Novo Projeto'."

## Classificação Personalizada
- Criado projeto para classificar suporte técnico em "urgente", "médio", "baixo"
- Treinamento com 10 exemplos por categoria

## 📌 Conclusão

Esse projeto foi essencial para consolidar os conhecimentos em IA na nuvem com ferramentas acessíveis e poderosas. Documentar a experiência no GitHub ajuda a fixar o aprendizado e também funciona como portfólio para oportunidades futuras.

