##  Contexto

A Id Websistemas vem trabalhando no projeto Biblioteca, destinado a uma pequena biblioteca pública da periferia da cidade. O sistema é simples e conta com um cadastro de livros e um cadastro de empréstimos, além de controle de log in. Para entrar em produção, o sistema precisa passar por um último processo de testes e por ajustes no versionamento da aplicação.
 
Serão utilizadas técnicas de caixa-preta e caixa-branca para os testes. Caso problemas sejam detectados, tarefas devem ser cadastradas no sistema de bug tracker do projeto. Além disso, um novo repositório precisará ser criado e as primeiras operações precisarão ocorrer.

## Atividade
Para realizar esta atividade, siga as instruções a seguir:

- Faça o download do projeto disponibilizado nos materiais complementares.

- Faça também o download do documento de requisitos do projeto disponibilizado nos materiais complementares.

- Instale o sistema de bug tracker Mantis.

- Realize o versionamento inicial do projeto com GIT, configurando arquivos a serem ignorados e realizando as primeiras operações de commit.
```bash
git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/xxxxxxxx/xxxxxx
git push -u origin main
```

- Teste o projeto utilizando técnicas de caixa-branca e caixa-preta. Baseie-se nos requisitos documentados para identificar erros e falhas.
Cadastre cada problema encontrado no sistema Mantis, indicando a descrição do problema e os passos para reproduzi-lo, além da gravidade e da urgência do problema.

## Avaliação
Nesta atividade, você será avaliado no indicador:
 - Registra os resultados e as alterações dos processos de teste e manutenção, de acordo com as melhorias implantadas na aplicação.

 ## Ícones

- :package: nova funcionalidade
- :up: atualização
- :beetle: correção de bug
- :checkered_flag: release
