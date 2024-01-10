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




