# livecoding

## Sistema de Reservas para Eventos

### Objetivo:
Projetar e implementar parte de uma API para um sistema de reservas para eventos, focando em um único endpoint que cria reservas, mas considerando aspectos de segurança, performance e escalabilidade.

Requisitos
1.	Modelagem de Dados: O sistema tem dois modelos principais, Evento e Reserva. O modelo Evento deve incluir atributos como nome, data, localização e capacidade_maxima. O modelo Reserva deve incluir evento_id e usuario_id.
2.	Endpoint da API: Implementar um POST /reservas que cria uma reserva para um usuário em um evento específico, considerando a capacidade_maxima do evento. Se o evento atingiu sua capacidade máxima, a reserva não deve ser criada, e a API deve retornar uma mensagem de erro apropriada.
