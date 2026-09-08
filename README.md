# TechBoard React + Vite

Projeto de estudos da Alura usado como **reciclagem de conhecimento em React** para a atuação fullstack na modernização do portal de créditos **Intercred**, no **Banco Inter**, em alocação pela **Stefanini**.

Repositório: [marcelohs402015/techboard-react](https://github.com/marcelohs402015/techboard-react)

## Contexto profissional

Atuo como **desenvolvedor fullstack** alocado pela Stefanini no Banco Inter. Sou responsável pela **modernização do Intercred**, o portal de créditos que está saindo de uma base **Delphi** para uma arquitetura web com **React no frontend** e **Java no backend**.

Essa migração não é só troca de linguagem. É mudar o jeito de construir interface, estado, formulários, integração com API e entrega contínua — do desktop legado para um produto web moderno.

## Por que este projeto existe

O TechBoard (curso Alura: React 19, JSX, componentes, form action e useState) é o laboratório em que eu **reciclo e atualizo** o conhecimento de frontend que preciso aplicar no Intercred.

Objetivos desta jornada:

1. **Sair do Delphi e pensar em React** — componentes, JSX, composição de UI e fluxo de dados em vez de formulários e eventos do desktop legado.
2. **Dominar o stack de entrega atual** — Vite, React 19, JavaScript moderno e o ciclo `dev → build → preview` que o portal novo usa no dia a dia.
3. **Treinar o que o Intercred exige na prática** — formulários de negócio, estado com `useState`, ações de submit, listagem e organização por temas/categorias.
4. **Fechar o ciclo fullstack** — frontend React conversando com contratos de API; no Intercred isso se conecta ao **backend Java**.
5. **Manter qualidade e rastreabilidade** — Git, README, Figma como fonte de layout e evolução incremental, o mesmo tipo de disciplina da modernização em produção.

## Mapa da reciclagem → Intercred

| O que pratico no TechBoard | Como isso se aplica no Intercred |
| --- | --- |
| Componentes e JSX | Telas do portal de crédito quebradas em peças reutilizáveis, não em um único formulário Delphi |
| `useState` e formulários (`form action`) | Cadastro, simulação e fluxos de crédito com estado previsível na UI |
| Listagem e organização visual | Consultas, cards e painéis do portal após a migração |
| Vite + React 19 | Mesmo tipo de tooling do frontend moderno (HMR, build, lint) |
| Layout a partir do Figma | Implementar UI fiel ao design, como nas entregas de modernização |
| Integração mental frontend ↔ API | Preparação para consumir serviços **Java** no lugar da lógica embutida no Delphi |

## Jornada de estudo

1. **Base** — projeto Vite + React criado e versionado neste repositório.
2. **UI** — reproduzir o Figma do Tecboard (header, banner, formulário, listagem).
3. **Comportamento** — cadastrar eventos na memória da aplicação com `useState` e `form action`.
4. **Transferência para o Intercred** — levar os mesmos padrões (componentes, formulários, estado, consumo de API) para as telas da modernização Delphi → React + Java.
5. **Evolução fullstack** — quando fizer sentido, conectar este laboratório a um backend Java simples, espelhando a arquitetura do portal.

Este repositório **não contém código do Banco Inter**. É um espaço pessoal de estudo. O Intercred permanece no ambiente e nos repositórios oficiais do cliente.

## Figma

Layout do curso (Tecboard / Alura):

- [Arquivo na Community do Figma](https://www.figma.com/community/file/1490097519019624965)
- [Node, React e Vite \| Tecboard](https://www.figma.com/design/Ib7Hkdqfl4JTvEIdLwTJMF/Node--React-e-Vite-%7C-Tecboard--Community-)

## Stack deste laboratório

- React 19
- Vite
- JavaScript (JSX)
- Oxlint

No Intercred, o alvo da modernização é **React (frontend) + Java (backend)**, substituindo o **Delphi**.

## Como rodar

```bash
npm install
npm run dev
```

Abra o endereço que o Vite mostrar no terminal (geralmente `http://localhost:5173`).

## Scripts

| Comando | Descrição |
| --- | --- |
| `npm run dev` | Servidor de desenvolvimento |
| `npm run build` | Build de produção |
| `npm run preview` | Pré-visualiza o build |
| `npm run lint` | Lint com Oxlint |
