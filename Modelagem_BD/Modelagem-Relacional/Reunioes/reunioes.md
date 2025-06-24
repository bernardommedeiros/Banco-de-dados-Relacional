# Gerenciamento de salas de aula

Deseja-se projetar um banco de dados que dará suporte a um sistema para gerenciar o uso de salas de reunião em uma empresa de consultoria. O objetivo do sistema é controlar as reservas realizadas pelos colaboradores e fornecer informações para otimizar a ocupação das salas. A modelagem deve ser feita por meio de um diagrama entidade-relacionamento no nível conceitual, e o banco de dados resultante não deve conter redundância de dados. O modelo deve incluir entidades, relacionamentos, atributos, especializações (quando aplicável), identificadores e restrições de cardinalidade. Não devem ser utilizado chaves estrangeiras.

A empresa possui várias salas de reunião, e cada sala deve ser identificada por um número único, além de possuir uma capacidade máxima de pessoas e uma descrição. As salas podem estar localizadas em diferentes andares ou prédios.

Cada colaborador da empresa pode reservar salas para reuniões. Para isso, o banco de dados deve armazenar o número de identificação do colaborador, seu nome completo e o departamento ao qual pertence. Um colaborador pode fazer diversas reservas.

Cada reserva de sala deve registrar qual colaborador fez a reserva, qual sala foi reservada, a data da reserva, o horário de início e de fim da reunião. Não é permitido que uma mesma sala seja reservada para dois eventos sobrepostos no tempo.

Além disso, o sistema deve permitir o registro de equipamentos adicionais solicitados para uma reunião, como projetores, notebooks ou quadros brancos. Cada equipamento deve ter um código, nome e quantidade disponível. Uma reserva pode solicitar mais de um tipo de equipamento, com quantidades específicas para cada um.