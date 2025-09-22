# Projeto-Final-POO-Banco-de-dados
Trabalho em conjunto entre as matérias de POO e banco de dados.

🐾 Pet+ – Sistema de Gestão para Clínica Veterinária
📌 Contexto

O tema Clínica Veterinária foi escolhido como ideal para um projeto de laboratório de Banco de Dados devido ao equilíbrio entre simplicidade e complexidade.
Esse cenário é familiar para a maioria das pessoas, o que facilita a compreensão dos requisitos e do fluxo de trabalho.

Em uma clínica veterinária, informações como clientes (tutores), pacientes (animais), serviços (consultas, cirurgias), agendamentos e finanças estão todas interconectadas.
Essa estrutura clara e definida torna o tema um excelente ponto de partida para aplicar conceitos de modelagem de dados e programação orientada a objetos (POO).

No projeto, imaginamos a seguinte situação:
A Pet+, clínica veterinária fictícia, oferece uma ampla gama de serviços — desde consultas de rotina até procedimentos cirúrgicos complexos. O objetivo é modernizar suas operações para otimizar a gestão de clientes, pacientes e finanças, garantindo qualidade no atendimento e crescimento sustentável.

🎯 Justificativa

A escolha do tema se justifica pela possibilidade de praticar modelagem de entidades e seus relacionamentos, com exemplos claros de aplicação:

Tutor pode ter vários Animais.

Animal pode ter vários Agendamentos.

Um Agendamento está vinculado a um Veterinário e a um Serviço.

Com esse modelo relacional, é possível aplicar conceitos fundamentais de Banco de Dados, como:

Chaves Primárias e Estrangeiras

Normalização

Integridade Referencial

Além disso, o sistema representa um cenário realista, onde a abstração orientada a objetos pode ser integrada com persistência em banco de dados.

📂 Escopo do Sistema
1. Gerenciamento de Tutores e Pacientes

Tutor: informações como nome, endereço, telefone e e-mail.

Animal: nome, espécie, raça, data de nascimento e peso, sempre vinculado a um tutor.

2. Agendamento e Serviços

Agendamento: consultas, cirurgias e outros procedimentos, vinculados a um Animal, um Veterinário e um Serviço.

Serviços: cadastro de serviços oferecidos (ex: Consulta de Rotina, Vacina Antirrábica, Cirurgia de Castração), com preço base e complexidade associados.

3. Histórico Clínico e Financeiro

Histórico Clínico: registro de diagnósticos, procedimentos e tratamentos para cada animal.

Cobrança de Serviços: geração de contas vinculadas a atendimentos, considerando preço base e complexidade (por exemplo, cirurgias de diferentes níveis).

Pagamentos: controle de status das contas, de pendente para pago, garantindo transparência e precisão.

🛠️ Tecnologias Utilizadas

Linguagem: Java

Banco de Dados: MySQL

Modelagem: MER, DER, normalização e scripts SQL.

Paradigma: Programação Orientada a Objetos (POO).

🚀 Funcionalidades Principais

✔️ Cadastro e gerenciamento de tutores e animais.
✔️ Registro de serviços, preços e complexidade.
✔️ Controle de agendamentos e disponibilidade de veterinários.
✔️ Histórico clínico detalhado para cada animal.
✔️ Emissão e controle de contas, com status de pagamento.
