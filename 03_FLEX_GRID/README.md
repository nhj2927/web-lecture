# Class 3

CSS Flex Box, Grid

## Flex Box

Flexible Box라고 함. flex라는 방향을 가진 1차원 선을 이용해서 요소를 배치하는 방법.

요소를 위치시키는 비교적 쉬운 방법.

Flex Box만 알아도 거의 대부분을 구현할 수 있다.

```

display: flex

```

### Flex

흐름. 기본값은 row방향. 왼쪽에서 오른쪽 방향.

Flex의 방향과 Flex의 수직 방향의 설정을 통해 요소를 위치시키는 방법

* flex-direction: Flex의 방향

```

flex-direction: row || column || row-reverse || column-reverse

```

* flex-wrap: 넘치는 요소를 어떻게 할 것인가?
```

flex-wrap: wrap || nowrap || wrap-reverse

```

* flex-flow: flex-direction과 flex-wrap을 합쳐 놓은 것


### Flex 내부 아이템

위의 설정들이 Flex의 설정이었다면, Flex 내부에 있는 아이템(자식)들의 설정

* justify-content: Flex 방향의 설정

* align-items: Flex 수직 방향의 설정

```

justify-content: flex-start || flex-end || space-around || space-between || space-evenly || center
align-items: flex-start || flex-end || space-around || space-between || space-evenly || center

```

* align-content 등

* flex: 내부 아이템의 너비

  div A 가 flex: 1, div B가 flex: 2 일 경우 너비는 A : B = 1 : 2

> 앞에보여주는 flex box 만들어보기


## Grid

2차원 적으로 요소를 배치하는 방법(바둑판). 비교적 최신 기능.

Flex Box 보다 편한 부분이 있지만, 더 구현하기 어려운 부분도 존재.

그러므로 Flex Box와 Grid를 적절히 섞어서 사용하면 좋다.

```

display: grid

```

### Grid

그리드는 Container와 Item으로 구성

* grid-template-row: 좌우방향의 그리드 설정

* grid-template-column: 상하방향의 그리드 설정

* grid-template: grid-template-row / grid-template-column

* fr: 부분의 단위


* row-gap: 좌우방향 아이템 사이의 여백

* column-gap: 상하방향 아이템 사이의 여백

* gap: row-gap column-gap


* grid-column-start, grid-column-end => grid-column

* grid-row-start, grid-row-end => grid-row

* grid-area: grid-row-start / grid-column-start / grid-row-end / grid-column-end

> 앞에 보여주는 Grid 만들어보기


## 연습게임

[Flexbox 연습게임](https://flexboxfroggy.com/#ko)

[Grid 연습게임](https://cssgridgarden.com/#ko)