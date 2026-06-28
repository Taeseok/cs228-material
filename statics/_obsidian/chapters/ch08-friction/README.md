# Ch.08 Friction (마찰)

> **Hibbeler 14e — Chapter 8**

---

## 핵심 개념

- [[#8.1 쿨롱 마찰 법칙]]
- [[#8.2 마찰 문제 유형]]
- [[#8.3 쐐기 (Wedge)]]
- [[#8.4 나사 (Screw)]]
- [[#8.5 벨트 마찰]]

---

## 8.1 쿨롱 마찰 법칙

$$F_s \leq \mu_s N \quad \text{(정지 마찰)}$$
$$F_k = \mu_k N \quad \text{(운동 마찰)}$$

| 기호 | 의미 |
|------|------|
| $\mu_s$ | 정지 마찰 계수 (static) |
| $\mu_k$ | 운동 마찰 계수 (kinetic) |
| N | 수직 항력 |

항상 $\mu_s > \mu_k$

**마찰각**:
$$\phi_s = \tan^{-1}(\mu_s)$$

---

## 8.2 마찰 문제 유형

| 상황 | 풀이 방법 |
|------|-----------|
| 정지 여부 확인 | F 계산 후 $F \leq \mu_s N$ 확인 |
| 미끄러짐 직전 | $F = \mu_s N$ 사용 |
| 운동 중 | $F = \mu_k N$ 사용 |

---

## 8.3 쐐기 (Wedge)

- 작은 힘으로 큰 힘 발생 (기계적 이득)
- 각 접촉면마다 마찰력 적용
- 각 부재별 FBD 작성

**자가 잠금 조건**:
$$\alpha \leq \phi_s$$
($\alpha$: 쐐기 각도, $\phi_s$: 마찰각)

---

## 8.4 나사 (Square-threaded Screw)

**조이는 방향**:
$$M = Wr\tan(\alpha + \phi_s)$$

**푸는 방향**:
$$M = Wr\tan(\phi_s - \alpha) \quad (\phi_s > \alpha)$$

자가 잠금: $\phi_s > \alpha$ → 외력 없이 풀리지 않음

---

## 8.5 벨트 마찰 (Belt Friction)

$$\frac{T_2}{T_1} = e^{\mu\beta}$$

| 기호 | 의미 |
|------|------|
| $T_2$ | 큰 장력 (당기는 쪽) |
| $T_1$ | 작은 장력 |
| $\mu$ | 마찰 계수 |
| $\beta$ | 감긴 각도 (rad) |

---

## 연관 자료

- [애니메이션: 마찰력](../../animations/ch08/index.html)
- [강의 슬라이드](../../slides/ch08/index.html)
- [예제 문제](../../problems/ch08/)
