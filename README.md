# NLW Agents

Projeto desenvolvido durante um evento da Rocketseat.

## Principais Tecnologias
- **React** 19 com **TypeScript**
- **Vite** para build e servidor de desenvolvimento
- **Tailwind CSS** para estilização
- **Radix UI** e componentes reutilizáveis
- **TanStack React Query** para dados assíncronos
- **React Hook Form** com **Zod** para formulários
- **React Router DOM** para navegação
- **Day.js** para datas
- **Biome** para lint e formatação

## Padrões de Projeto
- Componentização com React
- Hooks personalizados para acesso HTTP (`useCreateRoom`, `useCreateQuestion`, `useRooms`)
- Gerenciamento de estado de servidor com React Query
- Organização em módulos e utilidades (`src/lib`)

## Configuração
1. Instale as dependências:
   ```bash
   npm install
   ```
2. Inicie o projeto em modo desenvolvimento:
   ```bash
   npm run dev
   ```
3. Gere a versão de produção:
   ```bash
   npm run build
   ```
4. Visualize a build localmente:
   ```bash
   npm run preview
   ```
5. Opcionalmente rode o lint com:
   ```bash
   npx biome check .
   ```

Este projeto espera uma API rodando em `http://localhost:3333`.
