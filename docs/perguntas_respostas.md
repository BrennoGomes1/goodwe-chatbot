# Modelo de Teste — Chatbot GoodWe (Sprint 1)

## Teste 1
**Pergunta:** Como posso agendar a recarga do meu carro no condomínio?  
**Resposta esperada:**  
O chatbot deve orientar o morador a reservar um horário disponível no sistema, respeitar o limite máximo de tempo e liberar a vaga após o uso.

---

## Teste 2
**Pergunta:** Quanto vou pagar se consumir 30 kWh e a tarifa for R$ 1,20?  
**Resposta esperada:**  
O chatbot deve calcular:  
30 kWh × R$ 1,20 = R$ 36,00.

---

## Teste 3
**Pergunta:** O carregador não está iniciando a recarga. O que eu faço?  
**Resposta esperada:**  
O chatbot deve orientar um checklist:
1. Conferir se o cabo está conectado corretamente.
2. Verificar se o veículo está configurado para recarga.
3. Checar disjuntor ou energia do eletroposto.
4. Reiniciar o carregador (se possível).
5. Se persistir, abrir chamado com suporte técnico.

---

## Teste 4
**Pergunta:** Quem usou o carregador hoje?  
**Resposta esperada:**  
O chatbot deve informar que isso depende do log do sistema e, se disponível, listar usuário, horário e consumo. Caso não tenha acesso, orientar como gerar relatório.

---

## Teste 5
**Pergunta:** Como funciona o balanceamento de potência quando dois carros carregam ao mesmo tempo?  
**Resposta esperada:**  
O chatbot deve explicar que existe um limite de potência total disponível e o sistema divide ou limita a potência entre as recargas para evitar sobrecarga elétrica.