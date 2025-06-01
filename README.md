# 🍽️ Cookin' Up - Application Vue 3

Este é um projeto web desenvolvido com **Vue 3 + Vite + TypeScript** que simula um sistema de recomendação de receitas baseado em ingredientes selecionados. A aplicação permite que o usuário escolha ingredientes e visualize receitas que podem ser preparadas com eles.

## 🚀 Tecnologias Utilizadas

- [Vue.js 3](https://vuejs.org/)
- [Vite](https://vitejs.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- Ícones e imagens estáticas

## 📁 Estrutura do Projeto

```
cookin-up/
├── public/                         # Imagens públicas e ícones de categorias
│   ├── imagens/icones/
│   └── imagens/receitas/
├── src/
│   ├── assets/                     # Estilos, logos e imagens locais
│   ├── components/                # Componentes Vue reutilizáveis
│   │   ├── Banner.vue
│   │   ├── CardCategoria.vue
│   │   ├── IngredienteSelecionavel.vue
│   │   ├── SelecionarIngredientes.vue
│   │   ├── SuaLista.vue
│   │   └── Tag.vue
│   ├── http/                      # Configuração de chamadas HTTP
│   │   └── index.ts
│   ├── App.vue                    # Componente raiz
│   └── main.ts                    # Ponto de entrada da aplicação
├── index.html                     # HTML principal
├── vite.config.ts                 # Configuração do Vite
├── package.json                   # Dependências e scripts
└── tsconfig*.json                 # Configurações do TypeScript
```

## 🧪 Funcionalidades

- Seleção de ingredientes a partir de categorias.
- Filtragem de receitas com base nos ingredientes selecionados.
- Interface amigável e responsiva com imagens ilustrativas.
- Listagem de receitas com visual atrativo.

## ▶️ Como Executar o Projeto

### 1. Instalar dependências

```bash
npm install
```

### 2. Executar ambiente de desenvolvimento

```bash
npm run aplication-dev
```

## 👩‍💻 Desenvolvido por

Projeto exemplo ou protótipo visual com fins educacionais ou para portfólio.
Implementado para estudos da plataforma Alura.

## 📄 Licença

Este projeto é apenas para fins educacionais. Nenhuma licença específica definida.
