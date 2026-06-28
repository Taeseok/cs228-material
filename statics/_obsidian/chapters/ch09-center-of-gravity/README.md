# Ch.09 Center of Gravity and Centroid (무게중심과 도심)

> **Hibbeler 14e — Chapter 9**

---

## 핵심 개념

- [[#9.1 무게중심과 도심]]
- [[#9.2 복합 도형의 도심]]
- [[#9.3 파푸스-귤디누스 정리]]
- [[#9.4 분포 하중의 합력]]

---

## 9.1 무게중심 vs 도심

| 개념 | 기반 | 수식 |
|------|------|------|
| 무게중심 (Center of Gravity) | 무게 W | $\bar{x} = \frac{\sum \tilde{x}W}{\sum W}$ |
| 질량 중심 (Center of Mass) | 질량 m | $\bar{x} = \frac{\sum \tilde{x}m}{\sum m}$ |
| 도심 (Centroid of Area) | 면적 A | $\bar{x} = \frac{\sum \tilde{x}A}{\sum A}$ |
| 도심 (Centroid of Line) | 길이 L | $\bar{x} = \frac{\sum \tilde{x}L}{\sum L}$ |

균질 재료의 경우 무게중심 = 질량 중심 = 기하학적 도심

---

## 9.2 기본 도형의 도심

| 도형 | $\bar{x}$ | $\bar{y}$ |
|------|-----------|-----------|
| 직사각형 (b×h) | b/2 | h/2 |
| 삼각형 | b/3 (밑변에서) | h/3 |
| 반원 (반지름 r) | 0 | 4r/3π |
| 1/4 원 | 4r/3π | 4r/3π |

---

## 9.3 복합 도형 도심 계산 (구멍 포함)

$$\bar{x} = \frac{\sum \tilde{x}_i A_i}{\sum A_i}$$

구멍이 있는 경우: 구멍 면적에 **음수(−)** 부호 적용

---

## 9.4 파푸스-귤디누스 정리

**회전 표면적**:
$$A = 2\pi \bar{y} L$$

**회전 부피**:
$$V = 2\pi \bar{y} A$$

- $\bar{y}$: 생성 선/면의 도심에서 회전축까지 거리

---

## 연관 자료

- [애니메이션: 도심 계산](../../animations/ch09/index.html)
- [강의 슬라이드](../../slides/ch09/index.html)
- [예제 문제](../../problems/ch09/)
