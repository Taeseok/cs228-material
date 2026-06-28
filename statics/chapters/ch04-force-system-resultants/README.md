# Ch.04 Force System Resultants (힘 계의 합력)

> **Hibbeler 14e — Chapter 4**

---

## 핵심 개념

- [[#4.1 힘의 모멘트 (2D)]]
- [[#4.2 외적 (Cross Product)]]
- [[#4.3 힘의 모멘트 (3D)]]
- [[#4.4 우력 (Couple)]]
- [[#4.5 등가 힘-우력계]]
- [[#4.6 분포 하중의 합력]]

---

## 4.1 힘의 모멘트 (2D)

점 O에 대한 힘 F의 모멘트(회전 효과):

$$M_O = Fd$$

- $d$ = 모멘트 팔 (moment arm) — 점 O에서 힘의 작용선까지의 수직 거리
- 방향: **반시계 방향 (+)**, 시계 방향 (−)

### Varignon의 정리

합력의 모멘트 = 각 성분 힘의 모멘트의 합

$$M_O = \sum (F_x \cdot y - F_y \cdot x)$$

---

## 4.2 외적 (Cross Product)

$$\mathbf{M}_O = \mathbf{r} \times \mathbf{F}$$

$$\mathbf{r} \times \mathbf{F} = \begin{vmatrix} \hat{\mathbf{i}} & \hat{\mathbf{j}} & \hat{\mathbf{k}} \\ r_x & r_y & r_z \\ F_x & F_y & F_z \end{vmatrix}$$

크기: $|\mathbf{r} \times \mathbf{F}| = rF\sin\theta$

---

## 4.3 축에 대한 모멘트

$$M_a = \hat{\mathbf{u}}_a \cdot (\mathbf{r} \times \mathbf{F})$$

스칼라 삼중곱:

$$M_a = \begin{vmatrix} u_x & u_y & u_z \\ r_x & r_y & r_z \\ F_x & F_y & F_z \end{vmatrix}$$

---

## 4.4 우력 (Couple)

크기는 같고 방향이 반대인 두 힘의 쌍 → **순수 회전 효과만** 발생

$$M = Fd$$

- 우력은 자유 벡터: 어느 점에서 계산해도 동일한 값
- 우력은 **이동 가능** (같은 평면 내)

---

## 4.5 등가 힘-우력계

임의의 힘 계를 한 점 O에 대한 **합력 $\mathbf{F}_R$과 합 우력 $\mathbf{M}_{R_O}$** 으로 변환:

$$\mathbf{F}_R = \sum \mathbf{F}$$

$$\mathbf{M}_{R_O} = \sum \mathbf{M}_O + \sum \mathbf{M}$$

---

## 4.6 분포 하중

단순 분포 하중의 합력 = 분포 하중 선도의 **넓이**  
합력의 작용점 = 분포 하중 선도의 **도심**

| 형태 | 합력 크기 | 작용 위치 |
|------|-----------|-----------|
| 균일 (직사각형) | $F_R = w \cdot L$ | 중간점 (L/2) |
| 삼각형 | $F_R = \frac{1}{2}wL$ | 큰 쪽에서 L/3 |

---

## 연관 자료

- [애니메이션: 모멘트와 우력](../../animations/ch04/index.html)
- [강의 슬라이드](../../slides/ch04/index.html)
- [예제 문제](../../problems/ch04/)
