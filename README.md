# missing bars in matplotlib.pyplot.bar()

* 증상: matplotlib.pyplot.bar()로 막대 그래프를 그릴 때 막대가 사라지거나 막대 사이의 틈이 사라지는 현상이 있음 

* 원인: bar()는 막대의 위치를 1픽셀 단위로만 계산하는데, 막대 또는틈이 너무 얇으면 무시하고 그리지 않음

* 해결책: bar()의 파라미터 중 width를 조절하고, 필요에 따라 figsize, edgecolor를 설정하거나 Figure 창의 크기를 조절

* 자세한 설명은 제 [블로그](https://lazymatlab.tistory.com/144)에서 확인하실 수 있습니다.
