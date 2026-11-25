# Como publicar um artigo no site

Os artigos ficam na pasta `_posts` do repositório **site-ssaadvocacia** no GitHub.
Cada artigo é um arquivo de texto. Ao salvar, o site é atualizado sozinho em 1 a 3 minutos.

## Passo a passo

1. Abra https://github.com/SSAAdvocacia/site-ssaadvocacia e entre na pasta **_posts**.
2. Clique em **Add file → Create new file**.
3. No nome do arquivo, use **data + título curto, sem acentos e com hífens**, terminando em `.md`:

   `2026-11-25-banco-de-horas-o-que-a-empresa-precisa-saber.md`

   A data do nome é a data que aparece no artigo. Datas futuras só aparecem no site quando chegar o dia.
4. Copie o conteúdo do arquivo `modelo-de-artigo.md` e cole no editor.
5. Preencha o cabeçalho (entre as linhas `---`):

   | Campo | O que escrever |
   |---|---|
   | `title` | Título do artigo |
   | `autor` | `joao`, `marcela` ou `gedson` (exatamente assim, em minúsculas) |
   | `resumo` | Uma ou duas frases sobre o artigo |

6. Escreva o texto abaixo do cabeçalho. Formatação:
   - `## Subtítulo` para subtítulos
   - `**negrito**` e `*itálico*`
   - `- item` para listas
   - `> texto` para citações
   - `[texto](https://endereco)` para links
7. Clique em **Commit changes** (botão verde) e confirme.

O artigo aparece em:
- a página do autor (por exemplo, ssaadvocacia.com/socios/joao-mario-sonsim/)
- a página geral ssaadvocacia.com/artigos/

## Editar ou apagar um artigo

- **Editar:** abra o arquivo em `_posts`, clique no lápis (Edit), altere e clique em **Commit changes**.
- **Apagar:** abra o arquivo, clique nos três pontos (…) → **Delete file** → **Commit changes**.

## Se o site não atualizar

Abra a aba **Actions**. Se a publicação estiver com **X vermelho** ou parada há mais de 10 minutos
na fila, cancele e salve o arquivo de novo. Se o erro continuar, confira o cabeçalho do artigo:
as três linhas `---`, os campos `title`, `autor` e `resumo` e o valor do autor.

## Regras da OAB

Os artigos devem ter caráter informativo (Provimento 205/2021): sem promessa de resultado,
sem autoengrandecimento, sem menção a clientes ou casos e sem valores de honorários.
Cada artigo já é publicado com um aviso de que não constitui consulta jurídica.
