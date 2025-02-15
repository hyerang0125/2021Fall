> 🖇 2021 2학기 2주차 - 브루트포스, 백트래킹

</br>

# 1️⃣ Brute Force?

## Brute Force 특징

- 완전탐색 알고리즘으로 가능한 모든 경우의 수를 모두 탐색하면서 요구조건에 충족되는 결과만을 가져온다.
- 이 알고리즘은 예외 없이 100%의 확률로 정답만을 출력하는 것이 특징이다.

</br>

## 종류

- **순차탐색**: 선형 구조를 전체적으로 탐색
- **너비 우선 탐색(BFS, Breadth First Search)**: 비선형 구조에서 사용
- **깊이 우선 탐색(DFS, Depth First Search)**: 너비 우선 탐색과 마찬가지로 비선형 구조에서 사용되지만 뒤에서 다룰 백트래킹에서 더 많이 사용된다.

</br>

## 문제해결 방법 - 순차탐색

1. 주어진 문제를 선형 구조로 구조화 한다.
2. 구조화된 문제 공간을 적절한 방법으로 해를 구성할 때까지 탐색한다.
3. 구성된 해를 정리한다.

</br>

## 문제해결 방법 - 너비 우선 탐색(BFS)

- 큐를 사용하여 탐색 시작부터 목표를 만날 때까지 연결된 모든 정점(값)들을 우선 방문한다.
- 출발부터 목표까지의 최단 길이 경로를 보장하는 장점이 있다.
- 그러나 경로가 매우 길 경우에는 탐색 가지가 급격히 증가하여 많은 공간을 필요로 하고, 무한 그래프(infinite graph)의 경우에는 답도 못찾고 끝내지도 못하게 된다.

</br>

# 2️⃣ Backtracking

## Backtracking 특징

- 일반적으로 최적화 문제를 해결할 때 사용하는 방법이다.
- 문제를 비선형으로 구조화한 다음, 가능한 모든 상태를 깊이 우선으로 탐색해가며 해를 구성해 나간다.
- 이 과정에서 더 이상 탐색을 진행할 수 없으면 백트래킹하여 다시 다른 상태를 조사한다.

## 깊이 우선 탐색(DFS)

- 목표 값이 깊은 단계에 있을 경우 해를 빨리 구할 수 있다.
- 그러나 해가 없는 경로에 깊이 빠져 시간이 오래 소요될 수 있으므로 미리 지정한 임의의 깊이까지만 탐색하고 값을 발견하지 못하면 다음의 경로를 탐색하는 방법을 사용할 수 있다.
- 그러나 얻어진 해가 최단 경로가 된다는 보장이 없다. (최적의 해가 아닐 수 있음)

</br>
