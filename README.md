# DJ Juninho-BSB — Site oficial

Site de apresentação artística do **DJ Juninho-BSB** (Marcos R. Junior), de Brasília/DF, com uma versão revisada e organizada de seu release original.

## Conteúdo
- Apresentação artística em destaque.
- História de sua trajetória e marcos aos 13 e 16 anos.
- Tipos de eventos citados no release original.
- Release oficial revisado, com botão **Copiar release**.
- Seção de contato / redes sociais.
- Interface responsiva, menu móvel acessível, animações respeitando preferências de movimento reduzido.

## Arquivos
- `index.html` — toda a página, os estilos e o JavaScript (sem etapa de build).
- `favicon.svg` — ícone original em SVG.

## Como abrir localmente
1. Baixe os arquivos do repositório.
2. Abra `index.html` no navegador.

Opcionalmente, com Python instalado:

```bash
python -m http.server 8000
```

Acesse `http://localhost:8000`.

## Publicar com GitHub Pages
No repositório do GitHub, abra **Settings → Pages**:
1. Em *Build and deployment*, escolha *Deploy from a branch*.
2. Selecione a branch `main` e a pasta `/ (root)`.
3. Salve. Aguarde a publicação informada pelo GitHub.

O site está pronto para ser hospedado como página estática, mas **o GitHub Pages não é ativado automaticamente por este repositório**.

## Informação pendente antes da divulgação
O material original indica o Instagram como **“Djjuninho-bsb”**, mas esse texto não é um nome de usuário válido do Instagram (o caractere hífen não é permitido em nomes de usuário). Para evitar direcionar visitantes para um perfil errado, o site atualmente aponta para uma **pesquisa pública**.

Assim que o endereço oficial for confirmado, substitua no `index.html` o link externo da seção **Contato** por `https://www.instagram.com/USUARIO_CORRETO/`. Também vale incluir futuramente:
- Fotos oficiais autorizadas do DJ.
- Contato profissional ou WhatsApp comercial, caso desejado.
- Agenda, portfólio de eventos e vídeos ou sets, quando disponíveis e autorizados.

## Manutenção
O site não depende de framework nem de serviços pagos. O botão de copiar a release usa a API Clipboard do navegador; esta funcionalidade funciona com mais consistência quando o site está publicado por HTTPS (como no GitHub Pages).

## Conteúdo e fontes
O conteúdo biográfico foi reescrito exclusivamente com base na release fornecida para este projeto. Não foram criados depoimentos, números de eventos, contratos ou conquistas não comprovadas.
