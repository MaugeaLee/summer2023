# summer2023 
## 그래프 matplotlib으로 구현하기

~~~python

import matplotlib.pyplot as plt

second = [x**2 for x in range(-10, 11)]
index = [x for x in range(-10, 11)]

fig, ax = plt.subplots()

ax.spines['left'].set_position('center')
ax.spines['top'].set_visible(False)
ax.spines['right'].set_visible(False)

ax.set_ylim(ymin=0, ymax=100)
ax.plot(index, second)

~~~

![2차함수 그리기](https://github.com/MaugeaLee/summer2023/assets/92789013/77d95c5a-b583-475b-ad57-e9c6c41f0318)
