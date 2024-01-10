# Home
 PROJETO ESCOLA IFPI-CAMPUS ANGICAL
|Nome | Responsabilidade | E-mail | Github
| :---         |     :---:      |          ---: |      ---:|
| Kemelly     | Documento de Visão (escorpo) editora    | caang.2022119isinf26@aluno.ifpi.edu.br | Kemellyamorim
| Evanildo     | Documento de Visão  | caang.2022119isinf09@aluno.ifpi.edu.br  | Evanildoplay      |

![Diagrama sem nome drawio](https://github.com/kemellyamorim/monitoria/assets/144905285/c4c1f08a-57b7-4de7-8e16-12d76c691c85)

# 1.introdução
Este documento possui como finalidade a elucidação das questões relacionadas à implementação arquitetural do projeto do instituto federal ifpi-campus angical, desenvolvido nas disciplinas de Métodos de Desenvolvimento de Software e Gestão de Portfólios e Projetos de Software, que possui como cliente principal a diretoria da escola CEM 01 do Gama.

#  1.1 Finalidade
Este documento possui como finalidade trazer questões relacionadas à implementação arquitetural do projeto controle de chaves, idealizado na disciplina Análise e Projeto de Sistemas, que possui como cliente principal a direção da escola IFPI - Campus Angical.

# 1.2 Escopo
Este artefato documenta assuntos relacionados a visões de casos de uso e de lógica do projeto.

# 2.Visão dos Casos de Uso
![274275041-c4c1f08a-57b7-4de7-8e16-12d76c691c85](https://github.com/kemellyamorim/monitoria/assets/144693858/21f3be01-a18d-45a9-b21e-e844088848f8)
# 2.1 Atores de Casos de Uso

|Ator|Descrição|
|---|---|
|Adm(Diretor)|O adm irá manter os dados do corpo docente, dos alunos e poderá consultar os dados dos alunos|
|Aluno|O aluno irá registrar sua entrada e saída e poderá consultar seus dados| 
|Responsável|O responsável pode consultar os dados do aluno e será notificado da sua entrada e saída|
|Professor|O professor pode consultar dados dos alunos e gerar notificação|
|Secretário|O secretário pode registrar nota e consultar dados dos aluno|

# 2.2 Descrições de Casos de Uso

|Caso de Uso|Descrição|
|---|---|
|UC01 - Manter alunos|Criar, alterar ou deletar um aluno.|
|UC02 - Registrar advertência|Registrar uma nova advertência para um aluno.|
|UC03 - Registrar suspensões|Registrar uma nova suspensão para um aluno.|
|UC04 - Registrar notificação|Registrar notificação para aluno.|
|UC05 - Manter Responsáveis|Criar, alterar ou deletar um responsável de um aluno|
|UC06 - Consultar aluno|Fazer a busca pelo o histórico de um aluno.|
|UC07 - Visualizar número de faltas|Acessar o número de faltas de um determinado aluno.|
|UC08 - Visualizar Boletim|Acessar o boletim de um determinado aluno.|
|UC09 - Visualizar advertências/suspensões|Acessar o número de advertências/suspensões de um determinado aluno.|
|UC10 - Dar nota|Adicionar notas dos alunos.|
|UC11 - Registrar entrada/saída|Registrar a hora de entrada ou saída do aluno.|
|UC12 - Notificar os Responsáveis|Mandar SMS para os responsáveis após entrada/saída do aluno.|
|UC13 - Manter corpo docente|Criar, alterar ou deletar um membro do corpo docente.|
|UC14 - Fazer login|Acessar funcionalidades do sistema.|

# 3.visão

# 3.1 Classe
![Cópia do Diagrama sem nome drawio](https://github.com/kemellyamorim/monitoria/assets/144693858/23c04ddd-b0ce-475a-b005-e04d3de93951)
# 3.2 Colaboração entre Classes

O objetivo deste tópico é apresentar as principais colaborações entre as classes para executar suas funções dentro do sistema.
# 3.1.2 Cartão CRC
![286593002-7b22b4ca-7a65-4f97-a48c-3f350cdaa593](https://github.com/kemellyamorim/monitoria/assets/144693858/2d4d9617-0195-4c72-a28e-b07528792c0f)
# 3.2.2 Lógica das Responsabilidades
Classe: Posse
Responsabilidade: cadastrar() - Cadastrar a posse de uma chave para um usuário.

* Criar um objeto usuário com os dados repassados.
* Criar um objeto chave com os dados repassados.
* Verificar se o usuário existe
* Verificar se a chave existe
* Verificar se a chave está disponível
* Verificar autorização do usuário para posse da chave
* Footer

* Responsabilidade**:emAberto()- Listar




 # HISTORIA DO USUARIO
| Identificador | Historia | Pontuação
| --- | --- | --- | 
| US01 | Eu como vigilante desejo me manter informado de quem esta com a chave? | 0
| US02 | Eu, como vigilante, desejo manter disciplinas para gerenciar a organização das chaves de cada bloco. | 0
| US03 | Eu como funcionário da escola desejo consultar alunos para visualizar o controle de chaves. | 0
| US04 | Eu como diretor desejo manter os professores informados para melhor administração das chaves. | 0
| US05 | Eu desejo como aluno um cargo de monitor para a posse das chaves. | 0
| US06 | Eu como servidor desejo saber a troca de usos da chaves. | 0
| US07 | Eu, como secretário, desejo poder visualizar a forma correta de quem esta responsavel pelo o controle das chaves. | 0
| US08 | Eu como vigilante desejo registrar de quem esta com a chave. | 0
| US09 | Eu como vigilante desejo registrar alguma ocorrencia caso aconteça algum imprevisto. | 0

# monitoria Visão
Introdução

# Propositos

Este documento tem como objetivo definir e organizar as características sobre o desenvolvimento da solução do IFPI- campus Angical.

# 1.2 Escorpo
Este projeto tem como finalidade suprir a necessidade de controle e gerenciamento da diretoria referente a vida acadêmica dos alunos do IFPI- campus Angical

busca uma solução em software para substituir um sistema previamente implementado, sendo que, deve possuir como característica fundamental a confiabilidade.

O software, a ser implementado, deve monitorar a presença e atividades escolares dos alunos mantendo os responsáveis informados.

# visões gerais

| Visões  |
| --------------|
| Caio pega chaves todos os dias |
| não tem autorização para pegar de outros laboratório |
| Necessidade de autorização para pegar a chave |
| So pode ficar em um laboratório |
| cada professor ter seu proprio monitor |
| Professores e alunos levando a chave para casa |
| responsabilização dos monitores |
| sistemas para auxiliar nas entregas de chaves para alunos com autorização do professor |

# 2.posição
# 2.1 Oportunidade de negocios
A forma como se dá o controle e gestão da vida acadêmica dos docentes, principalmente nas escolas públicas, não se adequa às necessidades das coordenações. Isso ocorre devido a um controle rudimentar e, em alguns casos, ineficiente em manter os dados relacionados e informar os responsáveis.

Nosso projeto visa solucionar este problema por meio da informatização do sistema de identificação dos alunos e notificação dos pais.
# 2.2 Instruções do problema

| Problemas | 
| --------- |
| Não tem sistemas para auxiliar nas entregas de chaves para alunos com autorização do professor |
| Professores e alunos levando a chave para casa |
| perda de chave |
| É obrigado arrebentar a porta para dar aula quando perde a chave |
| capaz de perder as 2 chaves a reserva e a principal |
| -Se acontecer do pessoal da limpeza entrar em uma sala e tiver alguma coisa faltando ou quebrado não vai saber quem foi, pois tem outros servidores que tem uma copía da chave |

# Descrições da parte interessada e do usuário
# 3.1 Resumo da parte Interessada 
| Nome | Descrição | Responsibilidade
| --- | --- | --- |
| Equipe de desenvolvimento| Estudantes da Universidade de Brasília da disciplina de MDS.| Desenvolver e Implementar o software.
| Equipe de Gestão de Projeto | Estudantes da Universidade de Brasília da disciplina de GPP. | Gerir o desenvolvimento do produto identificando o problema e apontando caminhos e soluções.
| Clientes | Centro de Ensino Médio 01 do Gama. | Disponibilizar informações sobre os alunos .

# 3.2 Principais necessidades da parte interessada
| Necessidades | Prioridade | Interesses | Solução atual | Solução proposta
| ------------- | ------------- | ------------- | ------------- | -------------
| Gerir a vida acadêmica dos alunos. | Alta  | Manter o controle diário de entrada/saída dos alunos e controlar as atividades acadêmicas. | Método manual e ineficiente, utilizando também o aplicativo Acadêmicos Total Pais e Filhos. | Exercer uma gerência mais eficiente da vida acadêmica dos alunos com o auxílio de um software com maior confiabilidade que o sistema anterior.
| Notificar os responsáveis.  | Alta  | nformar os responsáveis sobre entrada/saída e vida acadêmica dos alunos | Os responsáveis recebem um SMS sobre a entrada dos alunos, mas não possuem uma forma digital de acessar o histórico do alunos. | Os responsáveis receberão um SMS informando a entrada e saída do aluno, além de uma plataforma web para acessar o histórico escolar do estudante.
# 4 Visão geral do produto
# 4.1 Perspectiva do Produto
O sistema irá oferecer uma maneira informatizada e eficiente de controlar a entrada e saída dos alunos utilizando um leitor de códigos de barra, existente na instituição. O leitor vai fazer a identificação de cada aluno através da carteirinha, dessa forma os respectivos responsáveis receberão um SMS informando o horário de entrada ou saída do aluno. Cada responsável terá acesso ao histórico escolar do aluno, que fornecerá informações como: número de faltas, boletim escolar e advertências ou suspensões.
# EQUIPE
| nome | Responsabilibidade |     E- mail | 
| :---         |     :---:      |          ---: |
| Kemelly    | listar visões gerais (escopo)     | caang.2022119isinf26@aluno.ifpi.edu.br   | 
| Evanildo   | Listar problemas/ soluções  | caang.2022119isinf09@aluno.ifpi.edu.br     | 
