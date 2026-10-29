# 🎬 Cinelista

> Aplicação desenvolvida durante o Módulo 23 do curso Full Stack da EBAC, utilizando Next.js e a API do The Movie Database (TMDB).

O Cinelista é um projeto de estudo voltado à listagem e à consulta de informações sobre filmes. Ao longo do curso, a aplicação evoluiu e recebeu melhorias relacionadas a testes automatizados, qualidade de código e automação de processos.

## 🔗 Links do projeto

- **Aplicação publicada:** [Cinelista na Vercel](https://cinelista-psi.vercel.app/)
- **Versão mais recente do código:** [Cinelista — Módulo 27](https://github.com/gabriellysaless/6-testes-qualidade-codigo/tree/main/m27-testes-integracao-react-next/cinelista)
- **Repositório desta versão:** [Cinelista — Módulo 23](https://github.com/gabriellysaless/cinelista)

## 📌 Sobre a evolução do projeto

Esta versão corresponde à etapa inicial do desenvolvimento, realizada durante o Módulo 23 da EBAC. Para preservar o histórico de aprendizado, o código original permanece neste repositório.

Nos módulos seguintes, o projeto recebeu novas implementações e passou por melhorias técnicas, incluindo:

- Testes automatizados com Jest e React Testing Library.
- Verificação de qualidade de código com ESLint.
- Padronização de formatação com Prettier.
- Pipeline de CI/CD com GitHub Actions.
- Automação do build, das verificações e do deploy na Vercel.

Essas melhorias estão disponíveis na versão mais recente, localizada no repositório do Módulo 27.

## 🚀 Tecnologias

- Next.js
- React
- TypeScript
- CSS Modules
- Axios
- The Movie Database (TMDB) API

## ✨ Funcionalidades

- Listagem de filmes.
- Página de detalhes dos filmes.
- Consumo de API externa.
- Rotas dinâmicas.
- Utilização de Server Components.
- Layout responsivo.

## 📂 Estrutura do projeto

```text
src/
├── app/
├── components/
├── lib/
├── types/
└── styles/
```

## ⚙️ Como executar

### Pré-requisitos

- Node.js e npm instalados.
- Uma chave de API do [The Movie Database (TMDB)](https://www.themoviedb.org/).

### 1. Clone o repositório

```bash
git clone https://github.com/gabriellysaless/cinelista.git
```

### 2. Entre na pasta do projeto

```bash
cd cinelista
```

### 3. Instale as dependências

```bash
npm install
```

### 4. Configure as variáveis de ambiente

Crie um arquivo `.env.local` na raiz do projeto, utilizando o `.env.example` como referência.

```env
TMDB_API_URL=https://api.themoviedb.org/3
TMDB_API_KEY=SUA_TMDB_API_KEY
NEXT_PUBLIC_TMDB_API_IMG_URL=https://image.tmdb.org/t/p/w500
```

Substitua `SUA_TMDB_API_KEY` pela sua chave de API. Não compartilhe sua chave privada nem a envie ao repositório.

### 5. Inicie o servidor de desenvolvimento

```bash
npm run dev
```

Acesse [http://localhost:3000](http://localhost:3000) no navegador.

## 📚 Aprendizados

Durante o desenvolvimento inicial, foram praticados conceitos como:

- App Router e rotas dinâmicas.
- Server Components.
- Data Fetching.
- Consumo de APIs externas.
- Organização de componentes e arquivos.
- TypeScript.
- Estilização com CSS Modules.

A evolução do projeto também proporcionou contato com testes automatizados, ferramentas de qualidade de código e práticas de CI/CD. Para consultar essas implementações, acesse a [versão mais recente no GitHub](https://github.com/gabriellysaless/6-testes-qualidade-codigo/tree/main/m27-testes-integracao-react-next/cinelista).

## 👩‍💻 Desenvolvido por

**Gabrielly Sales**

Projeto desenvolvido para fins de estudo e aperfeiçoamento em desenvolvimento Front-end.