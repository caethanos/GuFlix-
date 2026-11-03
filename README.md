# Estudo+ — plataforma de estudos

Plataforma estática de página única com trilhas de Inglês A1 e Espanhol. A interface e as orientações estão em português; as perguntas mantêm o idioma que o aluno está estudando.

## O que está incluído

- Catálogo em tema escuro inspirado em plataformas de streaming, com prateleiras horizontais por idioma, cartões navegáveis e menu compacto fixo. A interface, as explicações e as instruções estão em português; inglês e espanhol aparecem nos exercícios como idiomas de estudo.
- Quatro unidades de Inglês A1, com 30 perguntas de quiz cada (120 perguntas).
- Unidades 05 — Saúde e bem-estar e 06 — Finanças, com 11 perguntas de Espanhol.
- Modo intensivo: explicação e exemplo antes da pergunta; ao errar, o aluno revisa o conteúdo e tenta novamente antes de avançar.
- Flashcards, exercícios escritos, desafios, revisão de erros, XP, sequência diária e registro local de progresso.
- O progresso fica no `localStorage` do navegador. O app não exige servidor nem processo de build.

A correção escrita atual usa respostas e regras incluídas no app. IA generativa e Supabase ainda precisam de configuração separada.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie `index.html` para a raiz.
2. Abra **Settings → Pages**.
3. Escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`, depois clique em **Save**.
4. Quando a publicação terminar, abra o endereço mostrado na seção Pages.

## Publicar no Netlify

1. Conecte o Netlify à sua conta do GitHub.
2. Escolha **Add new site → Import an existing project** e selecione o repositório.
3. Deixe **Build command** vazio e informe `.` como **Publish directory**.
4. Clique em **Deploy site**. O Netlify publicará novamente após novos envios para a branch conectada.

Também é possível publicar arrastando a pasta que contém `index.html` para o deploy manual do Netlify.
