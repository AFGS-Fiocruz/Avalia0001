# Avaliação 1
## Para candidatos à vaga de Desenvolvedor PHP (Jr/Pleno/Sênior)
Olá dev, nosso objetivo é avaliar seu conhecimento independente de sua experiência profissional. 

# O que precisa saber
* HTML
* CSS
* Javascript 
* PHP
* MySQl
* Git

# O que precisa entregar
Uma micro aplicação para cadastro de usuário com parte do preenchimento do formulário automatizada e salvando em uma base de dados.

# O que avaliaremos
* Código limpo, organizado e comentado
* Modularizado
* Aplicação da regra do negócio
* Uso do API

# Instruções
## Implementar um cadastro de usuário

### Telas
#### Tela de cadastro de usuário e regra do negócio
1. Campo "Nome de usuário", obrigatório e mínimo de 3 e máximo de 20 caracteres
2. Campo "Senha", obrigatório, mínino de 8 caracteres e criptografado
3. Campo "CEP", obrigatório e, após preenchido, deve buscar alguns dados via API CEP de https://brasilapi.com.br/
4. Campos "Logradouro", "Cidade" e "UF" serão preenchidos automaticamente pela pesquisa realizada via API CEP de https://brasilapi.com.br/
5. Campo "Número", obrigatório e recebe apenas números
6. Campo "Complemento", não obrigatório

#### Tela de resultado do cadastro

### Banco de dados
#### Tabela "TB_Usuario"
1. Campo "Nome de usuário", obrigatório, texto com 20 caracteres
2. Campo "Senha", obrigatório, texto com 256 caracteres
3. Campo "CEP", obrigatório, texto com 8 caracteres
4. Campos "Logradouro", "Cidade" e "UF", obrigatório, texto com 256, 100 e 2 caracteres consecutivamente
5. Campo "Número", obrigatório, inteiro
6. Campo "Complemento", não obrigatório, texto com 100 caracteres

## Bônus
* Tela de autenticação de usuário
* Tela com os cadastros ativos e opção para excluir um usuário
* Implementação de logs

## Boa sorte!!!
