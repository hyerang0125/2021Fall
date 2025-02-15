> 🖇 2021 2학기 3주차 - 깊이 우선 탐색, 너비 우선 탐색

</br>

# 1️⃣ Depth-First Search?

## Depth-First Search 정의

- 루트 노드(혹은 다른 임의의 노드)에서 시작해서 다음 분기(branch)로 넘어가기 전에 해당 분기를 완벽하게 탐색하는 방법
- 넒게 탐색하기 전에 깊게 탐색하는 것이 특징이다.

</br>

## Depth-First Search 특징

1. 자기 자신을 호출하는 **순환 알고리즘의 형태**를 가지고 있다. 따라서 모든 노드를 방문하고자 하는 경우에 사용한다.
2. 전위 순회(Pre-Order Traversals)를 포함한 다른 형태의 트리 순회는 모두 DFS의 한 종류이다.
3. 어떤 노트를 방문 했었는지 여부를 반드시 검사해야 한다. (검사 x -> 무한루프 위험)

</br>

# 2️⃣ Breadth-First Search

## Breadth-First Search 정의

- 루트 노드(혹은 다른 임의의 노드)에서 시작해서 인접한 노드를 먼저 탐색하는 방법
- 시작 정점으로부터 가까운 정점을 먼저 방문하고 멀리 떨어져있는 정점을 나중에 방문하는 순회 방법이다.
- 즉, 깊게 탐색하기 전에 넓게 탐색한다.

## Breadth-First Search 특징

1. 두 노드 사이의 최단 경로 혹은 임의의 경로를 찾고 싶을 때 주로 사용한다.
2. DFS와 다르게 재귀적으로 동작하지 않고, 큐를 사용하여 반복적인 형태로 구현한다.
3. Prim, Dijkstra 알고리즘과 유사하다.

</br>
