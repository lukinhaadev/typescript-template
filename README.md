# Projeto Padrão TypeScript 🚀

Este projeto é um template para um projeto TypeScript com uma configuração pré-definida para desenvolvimento.

## Ferramentas 🛠️

### TypeScript

TypeScript é uma linguagem de programação fortemente tipada que se baseia no JavaScript, proporcionando melhores ferramentas em qualquer escala. Ele ajuda a capturar erros cedo através de um sistema de tipos e torna o desenvolvimento em JavaScript mais eficiente.

### ESLint

ESLint é uma ferramenta de análise estática de código para identificar padrões problemáticos encontrados no código JavaScript. Ele ajuda a manter a qualidade e consistência do código, aplicando padrões de codificação e detectando possíveis erros.

### Prettier

Prettier é um formatador de código opinativo que aplica um estilo consistente ao analisar seu código e reimprimi-lo com suas próprias regras. Ele ajuda a manter seu código limpo e legível.

### dotenv

dotenv é um módulo sem dependências que carrega variáveis de ambiente de um arquivo `.env` para `process.env`. Ele ajuda a gerenciar configurações para diferentes ambientes (desenvolvimento, teste, produção) de maneira simples e segura.

## Começando 🚀

1. **Instale as dependências**:

   ```bash
   npm install
   ```

2. **Execute o servidor de desenvolvimento**:

   ```bash
   npm run dev
   ```

3. **Construa o projeto**:

   ```bash
   npm run build
   ```

4. **Inicie o projeto construído**:

   ```bash
   npm start
   ```

5. **Verifique o código com ESLint**:

   ```bash
   npm run lint
   ```

6. **Formate o código com Prettier**:

   ```bash
   npm run format
   ```

## Variáveis de Ambiente 🌍

Crie um arquivo `.env` na raiz do seu projeto e adicione suas variáveis de ambiente lá. Um exemplo de arquivo `.env` é fornecido como `.env.example`.

```properties
MY_SECRET=seu_valor_secreto
```
