# Backlog
Projecto: Sistema de Gestão do Centro de Explicação XYZ

---

## US01 – Registar Alunos

User Story  
Como funcionário administrativo, quero registar novos alunos no sistema, para organizar e manter os dados dos alunos do centro de explicação.

Critérios de Aceitação
- O sistema deve permitir inserir nome do aluno, idade, classe e contacto do encarregado de educação.
- O sistema deve guardar os dados do aluno na base de dados.
- O sistema deve confirmar quando o registo for feito com sucesso.

Prioridade: Must  
Estimativa: M

---

## US02 – Criar e Gerir Turmas

User Story  
Como administrador, quero criar e gerir turmas, para organizar os alunos de acordo com a classe ou disciplina.

Critérios de Aceitação
- O sistema deve permitir criar uma turma com nome ou classe.
- O sistema deve permitir associar alunos a uma turma.
- O sistema deve permitir consultar a lista de turmas existentes.

Prioridade: Must  
Estimativa: M

---

## US03 – Registar Presenças

User Story  
Como explicador, quero registar a presença dos alunos nas aulas, para acompanhar a assiduidade dos alunos.

Critérios de Aceitação
- O sistema deve mostrar a lista de alunos da turma.
- O explicador deve poder marcar presença.
- O sistema deve guardar as presenças registadas.
- O sistema deve permitir consultar presenças anteriores.

Prioridade: Should  
Estimativa: M

---

## US04 – Registar Avaliações

User Story  
Como explicador, quero registar as notas ou avaliações dos alunos, para acompanhar o seu desempenho académico.

Critérios de Aceitação
- O sistema deve permitir inserir notas para cada aluno.
- O sistema deve permitir consultar as notas dos alunos.
- O sistema não deve permitir notas fora do intervalo permitido.

Prioridade: Should  
Estimativa: M

---

## US05 – Consultar Desempenho

User Story  
Como administrador, quero consultar o desempenho dos alunos, para acompanhar o progresso académico no centro de explicação.

Critérios de Aceitação
- O sistema deve permitir pesquisar um aluno pelo nome ou código.
- O sistema deve mostrar as notas e presenças do aluno.
- O sistema deve permitir visualizar os dados por turma ou disciplina.

Prioridade: Must  
Estimativa: M

---

## US06 – Registar Explicadores

User Story  
Como funcionário administrativo, quero registar explicadores, para associá-los às turmas.

Critérios de Aceitação
- O sistema deve permitir registar dados do explicador e disciplina.
- O sistema deve impedir cadastro com dados incompletos.
- O explicador deve ficar disponível para associação às turmas.

Prioridade: Must  
Estimativa: M

---

## US07 – Registar Pagamentos

User Story  
Como administrador, quero registar pagamentos ou mensalidades, para controlar as finanças do centro de explicação.

Critérios de Aceitação
- O sistema deve permitir registar valor e data do pagamento.
- O sistema deve associar o pagamento ao aluno.
- O sistema deve mostrar histórico de pagamentos.

Prioridade: Must  
Estimativa: C

---

## US08 – Agendar Aulas

User Story  
Como explicador, quero agendar aulas para a turma, para organizar o calendário de actividades.

Critérios de Aceitação
- O sistema deve permitir definir data e hora da aula.
- Apenas explicadores podem agendar aulas.
- A aula deve ficar associada à turma correspondente.

Prioridade: Should  
Estimativa: M

---

## US09 – Editar Dados de Aluno

User Story  
Como funcionário administrativo, quero editar os dados de um aluno, para corrigir ou actualizar informações.

Critérios de Aceitação
- O sistema deve permitir alterar dados existentes.
- Apenas utilizadores autorizados podem editar.

Prioridade: Must  
Estimativa: S

---

## US10 – Criar Turmas

User Story  
Como administrador, quero criar turmas, para organizar os alunos por classe ou disciplina.

Critérios de Aceitação
- O sistema deve permitir definir nome da turma.
- Deve permitir associar um explicador à turma.
- Deve definir limite de alunos por turma.

Prioridade: Must  
Estimativa: M

---

## US11 – Associar Alunos a Turmas

User Story  
Como funcionário administrativo, quero associar alunos numa turma, para organizar a sua participação nas aulas.

Critérios de Aceitação
- O sistema deve permitir seleccionar aluno e turma.
- O sistema não deve permitir associação se a turma estiver cheia.
- O sistema não deve permitir associar um aluno inexistente.

Prioridade: Must  
Estimativa: M

---

## US12 – Registar Notas dos Alunos

User Story  
Como explicador, quero registar notas dos alunos, para avaliar o seu desempenho académico.

Critérios de Aceitação
- Apenas explicadores podem inserir notas.
- As notas devem estar no intervalo de 0 a 20.
- O sistema deve guardar as notas associadas ao aluno.

Prioridade: Must  
Estimativa: M

---

## US13 – Eliminar Alunos

User Story  
Como administrador, quero eliminar alunos do sistema, para remover registos que já não são necessários.

Critérios de Aceitação
- O sistema deve permitir eliminar alunos existentes.
- Apenas administradores podem eliminar alunos.
- O sistema deve pedir confirmação antes da eliminação.

Prioridade: Should  
Estimativa: S

---

## US14 – Gerar Relatórios

User Story  
Como administrador, quero gerar relatórios de alunos e turmas, para analisar informações do centro de explicações.

Critérios de Aceitação
- O sistema deve gerar relatórios de alunos matriculados.
- O sistema deve gerar relatórios de turmas.
- O sistema deve permitir visualizar ou exportar o relatório.

Prioridade: Could  
Estimativa: M

---

## US15 – Controlar Acesso

User Story  
Como administrador, quero controlar o acesso dos utilizadores ao sistema, para garantir segurança nas informações.

Critérios de Aceitação
- O sistema deve permitir login usando credenciais.
- O sistema deve definir diferentes níveis de acesso (administrador, explicador, funcionário).
- O sistema deve bloquear acesso a funcionalidades não autorizadas.

Prioridade: Must  
Estimativa: C
