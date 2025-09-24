# UCAN
Tema : Processo de acesso a prova para todos os estudantes

Contexto : 
   Havendo a necessidade de controlar os alunos que estão com as suas matricular legalizadas para terem acesso as provas, a intenção é criar um sistema que através do face id do aluno verificar se ele esta apto para fazer uma determinada prova 

### 🎯 Objetivo Geral

Desenvolver um sistema automatizado de identificação por reconhecimento facial para validar o acesso dos alunos às provas, com base na sua matrícula regularizada e situação financeira junto à instituição.

### ✅ Objetivos Específicos

- Integrar a base de dados acadêmica com o sistema de reconhecimento facial para verificar a matrícula do aluno em determinada disciplina.
- Implementar uma verificação automática da inexistência de pendências financeiras do aluno antes de liberar o acesso à prova.
- Garantir segurança e precisão na autenticação da identidade do aluno no momento da avaliação.
- Facilitar o controle administrativo dos alunos aptos a realizar provas, reduzindo processos manuais.

### ✅ Linguagem e Ambiente de Desenvolvimento

- **Backend:** Java com Spring Boot — estrutura robusta, orientada a serviços RESTful, facilitando integração.
- **Frontend:** React Native — compatível com dispositivos móveis Android/iOS, ideal para captura facial em tempo real.
- **Banco de Dados:** PostgreSQL — sistema relacional com forte suporte a operações complexas e segurança de dados.
- **Reconhecimento Facial:** OpenCV integrado a biblioteca `dlib` com modelagem de landmarks para detecção em tempo real.

### ✅ Modelagem da Solução

- Cadastro prévio de alunos com foto facial vinculada ao seu perfil acadêmico.
- Interface de verificação facial durante o acesso à sala de provas.
- Consulta automática à base de dados da instituição verificando:
    - matrícula ativa na disciplina da prova
    - inexistência de pendências financeiras
- Autorização imediata ou bloqueio de acesso, com justificativa em tela.
