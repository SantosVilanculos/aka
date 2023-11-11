# Aka

## Introdução
O projeto visa desenvolver um abrangente Sistema de Gestão de Doação de Sangue que facilita eficientemente a correspondência de tipos sanguíneos, mantém registros de saúde de doadores e assegura uma interação segura e amigável entre doadores e administradores.

---
## Contextualização

### Porquê
#### Salvar Vidas:
- O propósito primário de um banco de sangue é salvar vidas, fornecendo um suprimento crucial de sangue e seus componentes a pacientes em hospitais e clínicas.

#### Garantir a Segurança Sanguínea:
- Protocolos rigorosos de teste e triagem para todas as doações de sangue são implementados para garantir a segurança dos destinatários, prevenindo a transmissão de doenças transmitidas pelo sangue, como o HIV, hepatite e sífilis.

#### Gerenciamento do Inventário de Sangue:
- O gerenciamento eficiente de diversos tipos sanguíneos é vital, garantindo um inventário ótimo alinhado com a demanda dinâmica, atendendo, em última instância, às diversas necessidades dos pacientes.

#### Facilitar a Doação:
- Simplificar o processo de doação de sangue para os doadores é alcançado tornando-o conveniente e informativo, incentivando contribuições regulares para o banco de sangue.

#### Rastreamento e Registro de Dados:
- O registro sistemático e o rastreamento de informações abrangentes sobre doadores, doações e inventário de sangue servem para relatórios, análises e conformidade com padrões regulatórios.

### Desafios
	
#### Inventários Flutuantes:
- O desafio reside em manter inventários de sangue consistentes devido à natureza imprevisível da demanda e à vida útil limitada dos produtos sanguíneos.

#### Triagem e Testes Precisos:
- A precisão nos testes de triagem de sangue é fundamental para prevenir a transmissão de doenças, enfatizando a importância da precisão nos procedimentos de teste.

#### Conscientização sobre Doação:
- Abordar o desafio contínuo de conscientizar sobre a doação de sangue e motivar indivíduos a contribuir regularmente para o banco de sangue.

#### Integridade e Privacidade de Dados:
- Garantir a integridade dos dados e proteger a privacidade das informações do doador são aspectos críticos, especialmente diante de preocupações com cibersegurança. Isso envolve adotar medidas robustas para proteger contra possíveis violações e acesso não autorizado.

---

## Requisitos Funcionais

### Correspondência de Tipos Sanguíneos:
- O sistema deve facilitar a correspondência eficiente de tipos sanguíneos entre doadores e destinatários para transfusões de sangue.

### Gerenciamento do Histórico de Saúde:
- Manter um histórico de saúde abrangente para cada doador para avaliar a elegibilidade para doação de sangue e garantir a segurança do destinatário.

### Sistema de Notificação:
- Implementar um sistema de notificação para alertar doadores sobre próximos agendamentos de doação, campanhas e atualizações críticas.

### Gerenciamento de Campanhas:
- Permitir que os administradores criem, gerenciem e rastreiem campanhas de doação de sangue.
- Os recursos incluem definir metas de campanha, monitorar o progresso e analisar a eficácia da campanha.

### Mecanismo de Feedback:
- Oferecer uma maneira para os doadores fornecerem feedback sobre o processo de doação, usabilidade do sistema e experiência geral do usuário.

---

## Requisitos Não Funcionais
### Segurança:
- Garantir a confidencialidade de registros sensíveis.

### Desempenho:
- Otimizar o desempenho do sistema para processamento eficiente de dados.

### Disponibilidade:
- Garantir que o sistema esteja sempre disponível para os usuários.

### Escalabilidade:
- Projetar o sistema para escalar e acomodar volumes crescentes de dados e usuários.

### Integração:
- Permitir integração sem problemas com outros sistemas relevantes.

### Usabilidade:
- Priorizar uma interface amigável para usuários, tanto doadores quanto administradores.

### Backup e Recuperação:
- Implementar mecanismos robustos de backup e recuperação para evitar a perda de dados.

### Agendamento de Doação:
- Facilitar o agendamento eficiente de doações de sangue.

---

## Regras de Negócios

### Confidencialidade:
- Garantir a confidencialidade de registros sensíveis em todo o sistema.

### Autorização:
- Permitir que apenas administradores autorizados registrem ou excluam usuários (funcionários ou doadores).

### Funções do Usuário:
- Atribuir a cada usuário uma função específica e um identificador único.

### Elegibilidade do Doador:
- Apenas doadores elegíveis devem ser registrados ou permitidos para doação de sangue se já estiverem registrados.

### Aplicativo Móvel do Doador:
- Permitir que os doadores acessem informações sobre campanhas, gerenciem informações pessoais não sensíveis e visualizem histórico ou status de doação de sangue por meio de um aplicativo móvel.
