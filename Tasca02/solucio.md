# T02: Selecció d’un SAI per una empresa client

## Informe tècnic: Estudi i selecció de SAI per a TecnoGestió S.L.

**Autor:** Jan Fernández Pauinelli  
**Curs:** 2025/2026  
**Mòdul:** Seguretat informàtica  
**Enllaç:** [https://goo.su/fqBdNdR](https://goo.su/fqBdNdR)

---

## Índex
1. [Inventari d’equips](#1-inventari-dequips)  
2. [Càlcul de potència total](#2-càlcul-de-potència-total)  
3. [Determinació de l’autonomia](#3-determinació-de-lautonomia)  
4. [Models de SAI analitzats](#4-models-de-sai-analitzats)  
5. [Selecció final i justificació](#5-selecció-final-i-justificació)

---

## 1. Inventari d’equips

| Dispositiu | Consum [W] | Connectat al SAI |
|-------------|-------------|------------------|
| PC de sobretaula (x4) | 200 W c/u (800 W total) | Sí |
| Monitor LED 24" (x4) | 35 W c/u (140 W total) | Sí |
| Router | 12 W | Sí |
| Impressora multifunció | 30 W en standby / fins a 480 W en ús | No |

S'ha exclòs la impressora multifunció, ja que el seu consum en impressió és elevat i no és un equip crític que hagi de romandre actiu en cas de tall elèctric.

---

## 2. Càlcul de potència total

- Ordinadors: 800 W  
- Monitors: 140 W  
- Router: 12 W  
**Total:** 952 W  

Amb un marge de seguretat del 20%:  
**952 W × 1,2 = 1150 W ≈ 1900 VA (factor de potència 0,6)**

---

## 3. Determinació de l’autonomia

S’estableix un temps mínim de 10 minuts per permetre als usuaris guardar els seus treballs i apagar els ordinadors de forma segura.

---

## 4. Models de SAI analitzats

| Model | Potència (VA/W) | Autonomia | Preu (€) |
|--------|------------------|------------|-----------|
| APC Back-UPS Pro BR1500G | 1500 VA / 865 W | 5–7 min a 500 W | 280–300 € |
| APC Smart-UPS SMT1500 | 1500 VA / 1000 W | 6–7 min a 1000 W | 500–550 € |
| Eaton 5P 1550VA | 1550 VA / 1100 W | 10 min a 600 W / 3–5 min plena càrrega | 450–500 € |

---

## 5. Selecció final i justificació

El model més adequat per a TecnoGestió S.L. és el **Eaton 5P 1550VA**, ja que ofereix:

- Potència suficient (1100 W útils)  
- Temps d’autonomia adequat  
- Bona relació qualitat-preu  
- Fiabilitat i característiques modernes per a equips crítics  

És un SAI de gamma professional, ideal per protegir els ordinadors i la xarxa de l’empresa.

---

[torna a l'enunciat](README.md)

