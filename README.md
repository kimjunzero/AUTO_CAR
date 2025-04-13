대한상공회의소 AI 시스템 반도체 SW 개발자 과정 - MINI Project

Atmega128A를 활용한 자율 주행 자동차

재작기간 : 2025-03-21 ~ 2025-03-24

---

1. FSM
2. 회로도
3. 기능
4. 설계

---

# 1. FSM

![image.png](attachment:5e509381-d48b-4392-921f-52f36d99c550:image.png)

---

# 2. 회로도

![image.png](attachment:d3a91de6-1dda-4248-be01-c4624d8c1401:image.png)

![image.png](attachment:2c9d0b0d-abad-43e3-8829-dc8f00ef3c49:image.png)

---

# 3. 기능

초음파(거리 측정), I2C(CLCD)- 통신타이밍 개념 , 주파수 호핑 방식,  PWM(모터), Specker(pizeo)

주파수  호핑 방식 짧은 시간 1600번 1/1600→ 625us

동영상 자막 달기, 전원 공급기 활용(배터리 달앗을때 테스트로 하면 편함)

---

# 4. 설계

1. **타이머 0**
2. **타이머 1**
3. **타이머 2**
4. **타이머 3**
