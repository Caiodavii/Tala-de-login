Atividade V – Casos de teste
Cenário de Teste 01 – Cadastro com Sucesso
Objetivo: Verificar se o processo de cadastro de um novo usuário é concluído
com sucesso e o usuário é redirecionado corretamente para a área logada.
Pré-condições:
• O aplicativo está instalado e funcionando corretamente.
• O usuário está na tela principal do aplicativo.
• O usuário não está logado no aplicativo.
Passos para Execução:
1. Acessar o aplicativo:
o Abra o aplicativo no dispositivo.
o Verifique se a tela principal do aplicativo é exibida corretamente.
2. Navegar para a tela de cadastro:
o Na tela principal, localizar o botão "Cadastrar-se".
o Clicar no botão "Cadastrar-se".
o Verificar se a tela de cadastro é exibida corretamente.
3. Preencher o formulário de cadastro:
o Na tela de cadastro, localizar o campo "Nome".
o Preencher o campo "Nome" com o valor "Pedro Malta".
o Localizar o campo "E-mail".
o Preencher o campo "E-mail" com o valor "Pedro.malta@gamil.com".
o Localizar o campo "Senha".
o Preencher o campo "Senha" com o valor "S3nh@Sup3rF4rt3!!!!".
4. Submeter o formulário de cadastro:
o Verificar se todos os campos estão preenchidos conforme
especificado.
o Localizar o botão "Cadastrar".
o Clicar no botão "Cadastrar".
Resultado Esperado:
1. Exibição da mensagem de sucesso:
o O aplicativo deve exibir um popup com a mensagem "Usuário
cadastrado com sucesso" por 3 segundos.
o Verificar se a mensagem é exibida corretamente por 3 segundos.
2. Redirecionamento para a área logada:
o Após a exibição da mensagem de sucesso, o usuário deve ser
redirecionado automaticamente para a área logada do aplicativo.
o Verificar se a área logada é exibida corretamente e se todas as
funcionalidades da área logada estão disponíveis.
Pontos de Verificação:
• A tela principal do aplicativo é carregada corretamente.
• A navegação para a tela de cadastro ocorre sem problemas.
• Todos os campos do formulário de cadastro estão presentes e são
editáveis.
• A mensagem de sucesso é exibida corretamente quando o cadastro é
submetido com todos os campos preenchidos.
• O redirecionamento para a área logada após a exibição da mensagem de
sucesso funciona corretamente.
Observações:
• Verificar se o popup de sucesso não persiste na tela após o tempo
esperado de 3 segundos.
• Testar com variações de dados válidos para garantir que o processo de
cadastro está funcionando corretamente.
• Verificar se os dados do usuário estão corretamente salvos no banco de
dados após o cadastro.
• Verificar se, após o cadastro, o usuário permanece logado ao fechar e
reabrir o aplicativo se aplicável.
Cenário de Teste 02 – Cadastro com Falha: Sem Nome
Objetivo: Verificar se o aplicativo impede o cadastro de um usuário quando o campo
"Nome" está vazio e se a mensagem de erro apropriada é exibida.
Pré-condições:
• O aplicativo está instalado e funcionando corretamente.
• O usuário está na tela principal do aplicativo.
• O usuário não está logado no aplicativo.
Passos para Execução:
1. Acessar o aplicativo:
o Abra o aplicativo no dispositivo.
o Verifique se a tela principal do aplicativo é exibida corretamente.
2. Navegar para a tela de cadastro:
o Na tela principal, localizar o botão "Cadastrar-se".
o Clicar no botão "Cadastrar-se".
o Verificar se a tela de cadastro é exibida corretamente.
3. Preencher o formulário de cadastro:
o Na tela de cadastro, deixar o campo "Nome" vazio.
o Localizar o campo "E-mail".
o Preencher o campo "E-mail" com o valor "uninove@gmail.com".
o Localizar o campo "Senha".
o Preencher o campo "Senha" com o valor " uninove1717@.
4. Submeter o formulário de cadastro:
o Verificar se os campos "E-mail" e "Senha" estão preenchidos conforme
especificado.
o Localizar o botão "Cadastrar".
o Clicar no botão "Cadastrar".
Resultado Esperado:
1. Exibição da mensagem de erro:
o O aplicativo deve exibir um popup com a mensagem "O nome do usuário é
obrigatório".
o Verificar se a mensagem é exibida corretamente por um período de tempo
visível, geralmente de 3 a 5 segundos.
2. Redirecionamento para a tela de login:
o Após a exibição da mensagem de erro, o usuário deve ser redirecionado
automaticamente para a tela de login do aplicativo.
o Verificar se a tela de login é exibida corretamente e se todos os campos
necessários estão presentes.
Pontos de Verificação:
• A tela principal do aplicativo é carregada corretamente.
• A navegação para a tela de cadastro ocorre sem problemas.
• Todos os campos do formulário de cadastro estão presentes e são editáveis.
• A mensagem de erro é exibida corretamente quando o campo "Nome" está vazio.
• O redirecionamento para a tela de login após a exibição da mensagem de erro
funciona corretamente.
Observações:
• Testar variações onde outros campos estão preenchidos, mas o campo "Nome"
está vazio, para garantir que a validação de campo obrigatório está funcionando
corretamente.
• Verificar se o popup de erro não persiste na tela após o tempo esperado.
• Verificar se o usuário permanece na tela de cadastro caso o campo "Nome" seja
preenchido e submetido novamente sem fechar o aplicativo.
Cenário de Teste 03 – Cadastro com Falha: Senha Fraca
Objetivo: Verificar se o aplicativo impede o cadastro de um usuário quando a senha não
atende aos requisitos de segurança e se a mensagem de erro apropriada é exibida.
Pré-condições:
• O aplicativo está instalado e funcionando corretamente.
• O usuário está na tela principal do aplicativo.
• O usuário não está logado no aplicativo.
Passos para Execução:
1. Acessar o aplicativo:
o Abra o aplicativo no dispositivo.
o Verifique se a tela principal do aplicativo é exibida corretamente.
2. Navegar para a tela de cadastro:
o Na tela principal, localizar o botão "Cadastrar-se".
o Clicar no botão "Cadastrar-se".
o Verificar se a tela de cadastro é exibida corretamente.
3. Preencher o formulário de cadastro:
o Na tela de cadastro, localizar o campo "Nome".
o Preencher o campo "Nome" com o valor "Pedro Malta".
o Localizar o campo "E-mail".
o Preencher o campo "E-mail" com o valor "Pedro.malta@gamil.com".
o Localizar o campo "Senha".
o Preencher o campo "Senha" com o valor "010203".
4. Submeter o formulário de cadastro:
o Verificar se todos os campos estão preenchidos conforme especificado.
o Localizar o botão "Cadastrar".
o Clicar no botão "Cadastrar".
Resultado Esperado:
1. Exibição da mensagem de erro:
o O aplicativo deve exibir um popup com a mensagem "A senha precisa ter
10 caracteres e ao menos um número, uma letra maiúscula, uma letra
minúscula e caracteres especiais".
o Verificar se a mensagem é exibida corretamente por um período de tempo
visível, geralmente de 3 a 5 segundos.
o
2. Redirecionamento para a tela de login:
o Após a exibição da mensagem de erro, o usuário deve ser redirecionado
automaticamente para a tela de login do aplicativo.
o Verificar se a tela de login é exibida corretamente e se todos os campos
necessários estão presentes.
Pontos de Verificação:
• A tela principal do aplicativo é carregada corretamente.
• A navegação para a tela de cadastro ocorre sem problemas.
• Todos os campos do formulário de cadastro estão presentes e são editáveis.
• A mensagem de erro é exibida corretamente quando a senha não atende aos
requisitos.
• O redirecionamento para a tela de login após a exibição da mensagem de erro
funciona corretamente.
Observações:
• Testar com variações de senha que não atendam aos requisitos (por exemplo,
senhas sem caracteres especiais, sem letras maiúsculas, sem letras minúsculas,
etc.) para garantir que a validação de senha está funcionando corretamente.
• Verificar se o popup de erro não persiste na tela após o tempo esperado.
• Verificar se o usuário permanece na tela de cadastro caso a senha seja corrigida e
submetida novamente sem fechar o aplicativo.
