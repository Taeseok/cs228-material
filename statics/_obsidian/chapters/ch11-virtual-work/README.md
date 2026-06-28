# Ch.11 Virtual Work (가상일)

> **Hibbeler 14e — Chapter 11**

---

## 핵심 개념

- [[#11.1 가상일의 원리]]
- [[#11.2 자유도]]
- [[#11.3 퍼텐셜 에너지와 평형]]
- [[#11.4 평형의 안정성]]

---

## 11.1 가상일 (Virtual Work)

**가상 변위**: 실제 시간 변화 없이 가상으로 가하는 미소 변위 $\delta r$  
**가상일**: $\delta U = \mathbf{F} \cdot \delta \mathbf{r} = F \cos\theta \cdot \delta r$

### 가상일의 원리

평형 상태의 이상적 구속 시스템에서:
$$\delta U = 0$$

즉, 모든 능동력(active forces)이 하는 가상일의 합 = 0

---

## 11.2 자유도 (Degree of Freedom)

- 시스템의 위치를 완전히 기술하는 데 필요한 독립 좌표의 수
- 1 DOF → 1개의 좌표로 기술 가능
- 가상일 원리는 각 독립 가상 변위에 대해 적용

---

## 11.3 퍼텐셜 에너지와 평형

**중력 퍼텐셜 에너지**:
$$V_g = Wy$$

**탄성 퍼텐셜 에너지**:
$$V_e = \frac{1}{2}ks^2$$

**평형 조건**:
$$\frac{dV}{dq} = 0$$

($q$: 일반화 좌표, $V = V_g + V_e$)

---

## 11.4 평형의 안정성

$$\frac{d^2V}{dq^2} > 0 \quad \text{→ 안정 평형 (stable)}$$
$$\frac{d^2V}{dq^2} < 0 \quad \text{→ 불안정 평형 (unstable)}$$
$$\frac{d^2V}{dq^2} = 0 \quad \text{→ 중립 평형 (neutral)}$$

---

## 가상일 vs 평형 방정식

| 방법 | 장점 |
|------|------|
| 평형 방정식 | 모든 미지 반력 계산 가능 |
| 가상일 원리 | 구속력(반력) 제거, 원하는 힘만 계산 |

---

## 연관 자료

- [애니메이션: 가상일 & 안정성](../../animations/ch11/index.html)
- [강의 슬라이드](../../slides/ch11/index.html)
- [예제 문제](../../problems/ch11/)
