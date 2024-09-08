---
{"dg-publish":true,"permalink":"/adra/solayer-strategy/"}
---

## Базовое описание:

v1 LRT: 

1. User deposits SOL to Adra
2. Adra gives back adraSOL
3. Adra restakes with Solayer and gets sSOL
4. Adra delegates sSOL to predefined AVS

end deposit

---
withdrawal user

4. User clicks to withdraw sol back
5. Adrasol is being exchanged to native staking token
6. User checks when withdrawal is available on the adra protocol
7. User exchanges native staking token to Solana 

---
withdrawal protocol

4. User clicks to withdraw
5. Adra unstakes avs position
6. Adra initiates ssol to sol unstaking 
7. adra exchanges adrasol to native staking token
8. adra UI shows when it's possible to claim solana back with native staking token (epoch)

## Задача:

**Бизнес-логика**
Необходимо разработать Solana-программу и бэкенд (если требуется, NestJS, PostgreSQL) для реализации вышеописанной схемы.

Схема взаимодействия с Solayer и шаблоны у нас есть. В шаблоне содержится примерная структура программы и CPI-вызовы в программу Solayer

**Фронтент**
Надо разработать фронтент (React) по макету для реализации вышеописанного пользовательского опыта