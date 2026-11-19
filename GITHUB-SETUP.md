# Como publicar este portfólio no GitHub

## 1. Criar o repositório

No GitHub, crie um repositório com estas configurações:

- **Nome:** `Conduz-Solar-Website`
- **Descrição:** `Estudo de caso de website institucional desenvolvido com WordPress e Elementor para a Conduz Solar.`
- **Visibilidade:** Public (somente após confirmar autorização para divulgar o projeto e a marca)
- **Add a README:** desativado, porque este pacote já contém `README.md`
- **.gitignore e licença:** não adicionar nesta etapa; o pacote já inclui `.gitignore` e um aviso de direitos, sem conceder licença aberta.

## 2. Enviar os arquivos

1. Baixe e extraia `Conduz-Solar-Website-Portfolio.zip`.
2. Abra a pasta `conduz-solar-website`.
3. Selecione o conteúdo de dentro da pasta (incluindo arquivos ocultos, como `.gitignore`, se o sistema os exibir).
4. No repositório vazio, escolha **Add file → Upload files**.
5. Arraste os arquivos e pastas para a área de upload.
6. Confira se `README.md`, `.gitignore`, `documentation/`, `screenshots/` e `custom-code/` aparecem na raiz.
7. Escreva a mensagem de commit `Add Conduz Solar website portfolio documentation`.
8. Clique em **Commit changes**.

## 3. Antes de divulgar

- Confirme autorização da empresa para publicar o estudo de caso.
- Adicione capturas de tela autorizadas na pasta `screenshots/`.
- Personalize a seção **Minha participação** no `README.md`, marcando somente atividades que você realizou.
- Adicione arquivos de código apenas se forem seus e houver autorização para publicá-los.
- Não envie arquivos de instalação WordPress, banco de dados, backups ou credenciais.

## 4. O que colocar no portfólio

Compartilhe o link do repositório GitHub e o link do site oficial. Não configure GitHub Pages para este repositório: o WordPress depende de PHP e banco de dados, enquanto o GitHub Pages publica sites estáticos.

## 5. Capturas de tela e apresentação

Depois de enviar o pacote inicial, abra o website público e faça capturas de tela da página inicial e de algumas áreas relevantes. Salve-as na pasta `screenshots/` conforme as orientações do arquivo `screenshots/README.md`. Faça um novo commit com essas imagens autorizadas.

O banner `assets/banner.svg` já está referenciado no README e é uma arte de apresentação original criada para este estudo de caso.
