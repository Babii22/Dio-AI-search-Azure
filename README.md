# 🧾 Inteligência de Documentos no Azure

Este documento reúne os principais conceitos aprendidos sobre **Document Intelligence** no Microsoft Azure, destacando como extrair informações estruturadas de documentos por meio de IA.

---

## 📑 Análise de Documentos

A análise de documentos no Azure permite **extrair automaticamente texto, tabelas, valores-chave e estruturas** de arquivos como PDFs, imagens digitalizadas e formulários. É uma tecnologia poderosa para acelerar processos manuais e transformar documentos não estruturados em dados prontos para uso.

---

## 🧰 Modelos Pré-Construídos

O Azure oferece modelos prontos para cenários comuns como:
- **Faturas**
- **Recibos**
- **Carteiras de identidade**
- **Contratos**
- **Formulários fiscais**

Esses modelos **não exigem treinamento prévio** e são ideais para uso imediato, com alta precisão em documentos padronizados.

---

## 🛠️ Modelos Personalizados

Para cenários específicos ou documentos fora dos padrões, é possível **criar e treinar modelos personalizados**. Com isso, podemos ensinar o sistema a reconhecer campos e estruturas específicas dos nossos próprios documentos.

Ferramentas:
- Azure Document Intelligence (anteriormente Form Recognizer)
- Azure AI Studio

---

## 🧾 Analisando Formulários com o Serviço de Document Intelligence

Durante a prática, utilizamos o serviço para analisar formulários e obter:
- Campos de entrada e saída automaticamente identificados
- Tabelas extraídas com estrutura compreensível
- Identificação de relações entre campos

Essa abordagem é útil em casos como cadastros, pesquisas e documentos internos que seguem padrões internos.

---

## 🧪 Estúdio de Inteligência de Documentos

O **Document Intelligence Studio** é uma interface visual que facilita:
- A criação de projetos de extração
- O upload e anotação de documentos
- O treinamento e teste de modelos personalizados
- A visualização de resultados

Ele elimina a necessidade de código, tornando o processo acessível mesmo a usuários com pouca experiência técnica.

---

## 🧠 Análise Final

Durante as aulas, foram abordados três passos principais:

1. **Ingestão de conteúdo para IA**  
   - Importação de documentos para o Azure (PDFs, formulários, imagens).
2. **Criação de índices inteligentes**  
   - Organização dos dados extraídos com habilidades cognitivas e serviços como o Azure Cognitive Search.
3. **Exploração prática dos dados organizados**  
   - Análise de dados estruturados, extração de insights e compreensão de padrões informacionais.

O foco foi desenvolver uma **compreensão sólida sobre como essas ferramentas podem ser utilizadas para minerar e extrair conhecimento** de grandes volumes de informação.

---

## 🤖 Utilização do AI Search para Indexação e Consulta

O **Azure AI Search** permite transformar documentos em conteúdo pesquisável. Ele:
- Cria **índices customizados** com os campos extraídos
- Aplica **habilidades cognitivas** para enriquecer os dados (ex: linguagem natural)
- Permite realizar **consultas por texto livre** ou filtros estruturados
- Integra com aplicações e dashboards para visualização dos resultados

Essa funcionalidade é essencial para minerar grandes volumes de documentos com rapidez e precisão.

---

## 🎯 Conclusão

As ferramentas de Inteligência de Documentos do Azure, aliadas ao AI Search, formam uma solução robusta para:
- Automatizar a leitura e extração de documentos
- Estruturar grandes volumes de dados não estruturados
- Possibilitar análises, buscas e insights com base em IA
