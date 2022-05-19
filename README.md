# Microserviços: Administração de Catálogo de Vídeos com Typescript (Backend)

## Curso Full Cycle 3.0 - Criando projeto e entidade Categoria

### Desafio

Neste do desafio: <br><br>
[ X ] Monte o ambiente da aplicação TypeScript com Docker, Docker Compose, Jest e tudo que foi passado no curso.<br>

[ X ] Criar a entidade Categoria, bem como as abstrações de Entity e Object Value. Faça também os testes automatizados usando o Jest <br>

[ X ] Implemente mais 2 operações na na entidade Categoria

- update - deve receber name e description. Esta operação atualiza as duas propriedades, implemente os testes.
- activate e deactivate - estas duas operações ativam ou desativam a categoria respectivamente, ou seja, mudam a propriedade is_active para true ou false. Implemente os testes.

### Solução

- Prepare o ambiente docker e docker-compose
- Prepare o ambiente na IDE
- Implementar os metódos changeName e changeDescription no /src/domain/entities/category.ts
- Criar e efetuar os testes unitários
- Implementar os metódos activate e desactivate no /src/domain/entities/category.ts
- Criar e efetuar os testes unitários
- Efetuar todos os testes
