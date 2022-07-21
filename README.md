# js-validacao

Página formulário de cadastro com validações utilizando regex e api para auto-preenchimento, desenvolvida no curso JavaScript na Web: validação de Formulários e HTML5, com o instrutor Matheus Alberto

[checks]
  Na página é possível fazer as seguintes testagens/checagens:
    1. Verificar se campos "required" receberam inputs/dígitos;
    2. Verificar se campos como Email, Senha, CPF, CEP foram digitados seguindo um padrão válido;
    3. Verificar se a idade do usuário é maior que 18 anos.

Caso alguma dessas testagens não passe nos filtros do código desenvolvido, uma mensagem de erro amigável é exibida para o usuário, orientando sobre o motivo do erro e a possível solução

[functionalities]
  No campo CPF e no campo CEP foram desenvolvidas funcionalidades específicas para garantir uma boa experiência para o usuário e validação dos dados digitados.
    [CPF]
      No campo CPF, a validação do Dígito Verificador através da execução de rotina módulo 11 para obter os dois dígitos.
    [CEP]
      No campo CEP, além da validação, através da implementação da API ViaCEP, os campos de Logradouro, Cidade e Estado são automaticamente preenchidos, caso o CEP digitado seja válido e conste no banco de dados do IBGE.
