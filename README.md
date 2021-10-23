# robotica
Repositório das minhas atividades realizadas no curso Robótica do Zero

Atividade 1: 1_DronePlanar.ipynb
  Determine a posição ($x(t)$, $y(t)$) e a orientação ($\phi(t)$) e crie uma animação de um drone planar, dadas as seguintes velocidades:

  \begin{align}
  v_x(t)&=-2\pi \sin(2\pi t) \, , \\
  v_y(t)&=2\pi \cos(2\pi t) \, ,\\
  \omega(t)&= 0.01 \, ,\\
  \end{align}
  onde $v_x(t)$ e $v_y(t)$ correspondem à velocidade linear do drone nos eixos x e y, respectivamente, e $\omega(t)$ representa sua velocidade angular. Tal que,

  $$
  x(t)= \int_0^t v_x(\tau) d\tau\, , \quad x(0)=1\, \text{m}, \\
  y(t)= \int_0^t v_y(\tau) d\tau\, , \quad y(0)=0\, \text{m}, \\
  \phi(t)= \int_0^t \omega(\tau) d\tau\, , \quad \phi(0)=0\, \text{rad} .
  $$
