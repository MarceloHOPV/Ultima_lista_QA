# Ultima_lista_QA
Lista de exercícios do lab de QA do inatel

1. Como executar os testes:
- Importe o arquivo de coleção do Postman `Lista API.postman_collection(.json)`.
- Configure o ambiente no Postman.
- Execute os testes e analise os resultados.

2. Exportação no Postman:
- Exporte a coleção e o ambiente usados.

3. Relatório de Testes:
- Utilize a aba "Test Results" do Postman e salve um print ou exporte os resultados.

## Exercício 2: Respostas e Justificativas

1. **Os testes desenvolvidos são manuais ou automatizados?**  
   Os testes são **automatizados**, pois foram configurados no Postman para serem executados de forma programática, incluindo validações de status code e resposta por meio de scripts automatizados. O Postman permite executar todos os cenários sem interação manual após a configuração inicial.

2. **Alguns dos testes desenvolvidos são testes Fim-a-Fim (End-To-End)?**  
   Não, os testes desenvolvidos não são Fim-a-Fim (End-To-End). Esses testes verificam funcionalidades específicas de uma API, sem simular o fluxo completo de um sistema, como a interação entre cliente e servidor com autenticação e navegação.

3. **O que se deve fazer para que os testes desenvolvidos funcionem em modo regressão?**  
   Para que os testes funcionem em modo regressão, é necessário:  
   - **Automatizar a execução em pipelines CI/CD**, utilizando ferramentas como Newman (CLI do Postman) para rodar os testes em servidores.  
   - **Exportar e versionar os cenários no GitHub**, garantindo que todos tenham acesso à última versão.  
   - **Manter os testes atualizados** sempre que houver mudanças na API, ajustando as validações para refletir as novas funcionalidades ou requisitos.  
