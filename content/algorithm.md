# 정렬 알고리즘
### 버블정렬
개념 : 인접한 두 요소를 비교하여, 필요한 경우 교환하며 배열을 정렬하는 알고리즘입니다. 가장 큰 요소가 매 반복마다 끝으로 이동하는 형태입니다.   
특징 : 단순하지만 비효율적, 소규모 배열에서만 유용하다.

### 선택 정렬
개념 : 배열에서 가장 작은 요소를 찾아 첫 번째 위치와 교환하고, 이를 반복하여 전체 배열을 정렬하는 알고리즘입니다.   
특징: 단순하지만 비효율적입니다. 특정 상황에서 다른 정렬 알고리즘보다 느립니다.

### 삽입 정렬
개념 : 배열의 각 요소를 차례대로 비교하여, 적절한 위치에 삽입하여 정렬하는 알고리즘입니다.   
특징 : 단순하고, 거의 정렬된 배열에서 활용하면 효율적이다.

### 병합 정렬
개념 : 배열을 재귀적으로 반으로 나누고, 각 부분을 정렬한 후 병합하여 전체 배열을 정렬하는 알고리즘입니다.    
특징 : 안정적인 정렬 알고리즘으로, 대규모 데이터 정렬에 적합하지만 추가 메모리 공간이 필요합니다.

### 퀵 정렬
개념 : 피벗 요소를 선택하고, 피벗을 기준으로 작은 요소는 왼쪽, 큰 요소는 오른쪽으로 분할하여 정렬하는 알고리즘입니다. 재귀적으로 이 과정을 반복합니다.   
특징 : 빠르고 효율적이지만, 피벗 선택에 따라 성능이 달라질 수 있습니다.

### 힙 정렬
개념 : 힙 데이터 구조를 이용하여 배열을 정렬하는 알고리즘입니다. 최대 힙이나 최소 힙을 구성하여 정렬합니다.   
특징 : 안정적이지 않지만, 추가 메모리 없이 효율적으로 정렬할 수 있습니다.