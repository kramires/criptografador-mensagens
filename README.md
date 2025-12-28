# 🔐 Criptografador de Mensagens

Criptografador de mensagens seguro em um único arquivo HTML com interface moderna e design militar/profissional.

## ✨ Características

- **Arquivo único HTML**: Funciona offline, sem necessidade de servidor
- **Criptografia AES-GCM 256 bits**: Algoritmo de criptografia de alto nível
- **Sistema de chaves compartilhadas**: Use uma Seed (senha mestre) compartilhada com seus contatos
- **Interface moderna**: Design militar/profissional com cores adequadas
- **Fácil de usar**: Interface intuitiva com seletor para criptografar/descriptografar
- **Botões de ação**: Copiar e limpar mensagens facilmente

## 🚀 Como usar

1. Abra o arquivo `criptografador.html` em qualquer navegador moderno
2. Configure a **Seed** (senha mestre) compartilhada com seus contatos
3. Selecione o modo: **Criptografar** ou **Descriptografar**
4. Digite ou cole a mensagem
5. Clique no botão de ação correspondente
6. Use o botão **Copiar** para copiar o resultado
7. Use o botão **Limpar** para limpar os campos

## 🔒 Segurança

- **AES-GCM**: Algoritmo de criptografia simétrica de 256 bits
- **PBKDF2**: Derivação de chave com 100.000 iterações
- **IV aleatório**: Cada mensagem usa um Initialization Vector único
- **Sem dependência de data**: Mensagens podem ser descriptografadas a qualquer momento

## 📋 Requisitos

- Navegador moderno com suporte a Web Crypto API (Chrome, Firefox, Safari, Edge)

## 📝 Notas

- A Seed deve ser compartilhada apenas com pessoas confiáveis
- Mantenha a Seed segura e não a compartilhe publicamente
- As mensagens criptografadas podem ser descriptografadas a qualquer momento, desde que você tenha a Seed correta

## 🎨 Design

Interface com tema militar/profissional:
- Cores escuras e sóbrias
- Verde militar para botões e destaques
- Dourado para títulos e elementos importantes
- Fonte monoespaçada para mensagens

## 📄 Licença

Este projeto é de código aberto e está disponível para uso livre.
