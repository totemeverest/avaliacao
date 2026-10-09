# Everest — Minhas avaliações

Página pública (GitHub Pages) onde cada aluno da Academia Everest acompanha as próprias avaliações corporais.

- Endereço: `https://everestacademias.com/avaliacao/#<código-do-aluno>` (GitHub Pages deste repositório, no domínio da academia)
- O código (22 caracteres aleatórios) é criado pelo app do totem e enviado ao aluno pelo WhatsApp.
- Fica depois do `#`: o navegador não manda essa parte para o servidor.
- A página lê **um único documento** no Firestore (`portal/<código>`) com o primeiro nome e as avaliações daquele aluno.
- As regras do Firestore só permitem ler pelo código exato; listar é proibido.
- Não há telefone, imagem nem dado de outros alunos.
- **Este repositório não guarda nenhum dado de aluno.** Só o `index.html` e as imagens da marca.
- A página é só para consulta e não mostra comparações (elas são feitas no app, na academia).

Trocar o link de um aluno: app do totem → Buscar aluno → **TROCAR LINK DO ALUNO**. O link antigo para de abrir.
