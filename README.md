# Teste Prático - Dev Frontend Pleno

Bem-vindo ao teste prático! 🚀

O objetivo deste teste é avaliar seu conhecimento em **React/Next.js**, **Typescript**, uso do **Tailwind CSS**, consumo de APIs e boas práticas de organização e código limpo.

---

## 📝 Desafio

Implemente uma mini aplicação em **Next.js** que consume, obrigatoriamente, a API pública [JSONPlaceholder](https://jsonplaceholder.typicode.com).

### Requisitos obrigatórios

- **Lista de posts** em `/posts`

  - Usar `GET /posts`
  - Exibir título e resumo do conteúdo
  - Cada item deve ter link para os detalhes

- **Detalhe de um post** em `/posts/[id]`

  - Usar `GET /posts/{id}`
  - Exibir título, conteúdo e comentários (`GET /posts/{id}/comments`)

- **Criação de post** em `/posts/new`
  - Formulário com título e conteúdo
  - Validação (não permitir campos vazios)
  - Enviar `POST /posts`
  - Após criar, exibir feedback e atualizar a lista local

### Diferenciais (opcionais, pontos extras)

- Editar (`PUT /posts/{id}`) ou excluir (`DELETE /posts/{id}`) um post
- Paginação ou busca simples na listagem
- Componentes reutilizáveis (ex: `Card`, `FormInput`, `Layout`)

---

## 🛠️ Requisitos técnicos

- **Next.js**
- **Typescript**
- **Tailwind CSS** (já configurado no projeto base)
- Organização clara de pastas e arquivos
- Código limpo, legível e bem estruturado

📌 Você pode:

- Consultar **qualquer documentação oficial** (React, Next.js, Tailwind e qualquer outra que julgar necessário).
- Instalar **quaisquer bibliotecas adicionais** que julgar necessárias.

---

## ⏱️ Prazo e Supervisão

### Duração do Teste

Após o período de planejamento informado pelo recrutador, você terá **até 2 horas e 30 minutos** para concluir o teste.

### Supervisão

Conforme informado pelo recrutador, este teste será supervisionado e gravado utilizando a ferramenta **Google Meet** para posterior avaliação da nossa equipe.

---

## 🚀 Como entregar

1. Clone este repositório
2. Crie uma branch com seu nome:
   ```bash
   git checkout -b joao-silva
   ```

---

## 🍀 Boa sorte!

Esperamos que você tenha uma excelente experiência durante este teste. Demonstre suas habilidades e conhecimento técnico - estamos ansiosos para ver seu trabalho! 🚀
