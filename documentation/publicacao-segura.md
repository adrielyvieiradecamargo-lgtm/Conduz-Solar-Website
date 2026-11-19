# Checklist de publicação segura

Antes de tornar este repositório público, confira:

- [ ] Existe autorização da Conduz Solar para apresentar o trabalho em portfólio público.
- [ ] As capturas de tela não exibem painel administrativo, usuários, comentários privados ou dados pessoais.
- [ ] Nenhuma senha, chave de API, token ou credencial foi incluída.
- [ ] `wp-config.php` não foi incluído.
- [ ] Nenhum dump de banco de dados ou backup foi incluído.
- [ ] Arquivos comerciais de temas e plugins não foram copiados.
- [ ] Imagens, logotipos e fontes têm autorização ou licença compatível com a publicação.
- [ ] Os textos de clientes e depoimentos estão autorizados para reutilização.
- [ ] A seção “Minha participação” do README descreve apenas atividades realmente realizadas.
- [ ] O repositório não contém dados de clientes, fornecedores ou funcionários.

## Arquivos que não devem ser enviados

- `wp-config.php`
- `.env` e arquivos de configuração com segredos
- backups `.zip`, `.sql`, `.tar`, `.gz`
- credenciais de FTP, SSH, banco de dados ou hospedagem
- pastas integrais de plugins/temas comerciais sem autorização
- exportações com dados pessoais ou registros de clientes

## Se algum segredo for publicado por engano

Apagar o arquivo em um commit posterior não apaga necessariamente o segredo do histórico. Revogue ou altere imediatamente a credencial exposta e siga o processo de remoção do histórico do GitHub, se necessário.
