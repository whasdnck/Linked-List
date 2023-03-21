# Linked-List 란?

### 오늘은 Linked-List 라는 선형구조를 코딩했다.
### 연결 리스트는 자료들을 반드시 연속적으로 배열시키지는 않음.
### 자료 항목의 순서에 따라 노드의 포인터를 이용하여 다음 자료를 연결시킴.
### 동적 메모리에 할당된 링크에 의해 연결된 유한 개수의 데이터 원소들 이 있음.
### 링크 값을 변화시키는 것 만으로 노드의 삽입 삭제가 용이하다.
### 기억공간이 연속적으로 놓여 있지 않아도 저장이 가능하다.
# Linked-List 코드
## 첫번쨰 노드를 가리키는 필드
![dasdad](https://user-images.githubusercontent.com/127116197/226498024-901263c3-aa60-41ec-b5ab-1c42d3b7015f.png)

## 다음 노드를 가리키는 필드
![123456789](https://user-images.githubusercontent.com/127116197/226498176-fa01ddb7-bcf0-42ea-9fbb-1044e2f837fa.png)

## 노드의 내용을 쉽게 출력해서 확인해볼 수 있는 기능
![456666666666666666666](https://user-images.githubusercontent.com/127116197/226498288-28ac122a-1cec-43d9-a92b-7497374afad2.png)

## 헤드로 새로운 노드를 지정합니다.
![화면 캡처 2023-03-21 102140](https://user-images.githubusercontent.com/127116197/226498365-060c49fb-6f96-4af2-a6b2-1875aebc7c99.png)

# Full Code
![화면 캡처 2023-03-21 102422](https://user-images.githubusercontent.com/127116197/226498651-b1a2e663-3503-4bb9-a51d-5c6d6e1e5eb4.png)


# Stack이란?
### 스택의 개념은 한 쪽 끝에서만 자료를 넣고 뺄 수 있는 LIFO(Last In First Out) 형식의 자료 구조 이다.
### 스택(Stack)는 LIFO(Last In First Out) 를 따른다. 즉, 가장 최근에 스택에 추가한 항목이 가장 먼저 제거될 항목이다.

### pop(): 스택에서 가장 위에 있는 항목을 제거한다.
### push(item): item 하나를 스택의 가장 윗 부분에 추가한다.
### peek(): 스택의 가장 위에 있는 항목을 반환한다.
### isEmpty(): 스택이 비어 있을 때에 true를 반환한다.
### push와 pop은 스택을 다루는 자료구조를 이루는 두 개의 관리 함수이다.
### 어셈블리 언어에서는 함수의 파라미터를 메모리에 저장해 두거나 연산 후에 반환할 값을 메모리에서 빼내는 작업을 push와 pop이라고 한다.
# Stack Full Code
![화면 캡처 2023-03-21 114735](https://user-images.githubusercontent.com/127116197/226507044-2c274b0f-ea54-43d7-8602-81f68d128479.png)
