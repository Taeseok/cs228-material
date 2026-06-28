# Ch.02 Force Vectors (힘 벡터)

> **Hibbeler 14e — Chapter 2**

---

## 핵심 개념

- [[#2.1 스칼라와 벡터]]
- [[#2.2 벡터 연산]]
- [[#2.3 벡터 덧셈 — 평행사변형 법칙]]
- [[#2.4 2D 힘의 성분 분해]]
- [[#2.5 합력 (Resultant Force)]]
- [[#2.6 3D 힘 벡터 (직교 성분)]]
- [[#2.7 위치 벡터와 단위 벡터]]
- [[#2.8 두 점을 잇는 힘 벡터]]
- [[#2.9 내적 (Dot Product)]]

---

## 2.1 스칼라와 벡터

| 구분 | 정의 | 예시 |
|------|------|------|
| **스칼라** | 크기만 있는 양 | 질량, 온도, 시간 |
| **벡터** | 크기 + 방향이 있는 양 | 힘, 속도, 변위 |

벡터 표기: $\mathbf{F}$ (볼드), $\vec{F}$ (화살표)  
크기: $F = |\mathbf{F}|$

---

## 2.2 벡터 연산

### 벡터 덧셈
$$\mathbf{F}_R = \mathbf{F}_1 + \mathbf{F}_2$$

### 스칼라 곱
$$a\mathbf{F} = \mathbf{F} \cdot a$$

### 교환 법칙
$$\mathbf{F}_1 + \mathbf{F}_2 = \mathbf{F}_2 + \mathbf{F}_1$$

---

## 2.3 평행사변형 법칙

두 힘을 두 변으로 하는 **평행사변형**의 **대각선**이 합력이다.

**삼각형 법칙 (Triangle Rule)**:  
벡터를 머리에서 꼬리로 이어 삼각형을 만들면 합력은 첫 꼬리 → 마지막 머리.

**코사인 법칙**:
$$F_R = \sqrt{F_1^2 + F_2^2 - 2F_1 F_2 \cos\theta}$$

**사인 법칙**:
$$\frac{F_R}{\sin\theta} = \frac{F_1}{\sin\theta_1} = \frac{F_2}{\sin\theta_2}$$

---

## 2.4 2D 힘의 성분 분해

$$F_x = F\cos\theta, \quad F_y = F\sin\theta$$

### 합력의 크기와 방향
$$F_R = \sqrt{(\sum F_x)^2 + (\sum F_y)^2}$$

$$\theta = \tan^{-1}\left(\frac{\sum F_y}{\sum F_x}\right)$$

---

## 2.5 단위 벡터

$$\hat{\mathbf{u}} = \frac{\mathbf{F}}{|\mathbf{F}|}$$

크기가 1인 벡터. 방향만 나타낸다.

---

## 2.6 3D 힘 벡터

$$\mathbf{F} = F_x\hat{\mathbf{i}} + F_y\hat{\mathbf{j}} + F_z\hat{\mathbf{k}}$$

$$F = \sqrt{F_x^2 + F_y^2 + F_z^2}$$

### 방향 코사인
$$\cos\alpha = \frac{F_x}{F}, \quad \cos\beta = \frac{F_y}{F}, \quad \cos\gamma = \frac{F_z}{F}$$

$$\cos^2\alpha + \cos^2\beta + \cos^2\gamma = 1$$

---

## 2.7 위치 벡터

두 점 $A(x_A, y_A, z_A)$, $B(x_B, y_B, z_B)$ 사이의 위치 벡터:
$$\mathbf{r}_{AB} = (x_B - x_A)\hat{\mathbf{i}} + (y_B - y_A)\hat{\mathbf{j}} + (z_B - z_A)\hat{\mathbf{k}}$$

---

## 2.8 내적 (Dot Product)

$$\mathbf{A} \cdot \mathbf{B} = AB\cos\theta = A_xB_x + A_yB_y + A_zB_z$$

**활용**:
- 두 벡터 사이의 각도: $\theta = \cos^{-1}\left(\frac{\mathbf{A}\cdot\mathbf{B}}{AB}\right)$
- 벡터의 특정 축 투영 성분: $F_u = \mathbf{F} \cdot \hat{\mathbf{u}}$

---

## 연관 자료

- [애니메이션: 벡터 합성과 분해](../../animations/ch02/index.html)
- [강의 슬라이드](../../slides/ch02/index.html)
- [예제 문제](../../problems/ch02/)
