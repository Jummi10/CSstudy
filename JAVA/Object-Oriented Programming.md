# 객체 지향 프로그래밍

## 정의

**관련된 상태와 행위**를 하나의 객체로 만들고, 객체들간의 **유기적인 상호작용**을 통해 프로그램을 구성하는 것

## 장점

1. 코드 재사용이 용이해진다.
    - 다른 사람이 만든 클래스를 사용할 수 있고, 상속을 통해 확장할 수도 있다.
2. 소프트웨어 개발과 유지보수가 편리해진다.
    - 수정해야하는 부분이 클래스 내부에 필드나 메서드 속성으로 존재하기 때문에 해당 부분만 수정하면 된다.
3. 직관적인 코드 분석이 가능하다.
4. 대형 프로젝트에 적합하다.
    - 클래스 단위로 모듈화하여 개발할 수 있으므로 여러 명이 업무를 분담하기 쉽다.

## 단점

1. 설계에 많은 시간과 노력이 필요하다.
2. 객체가 많으면 용량이 커질 수도 있다.

# 개념

## 클래스 Class

- 속성(attribute)과 행위(behavior)를 변수와 메서드로 가지는 집합
- 객체를 만들기 위한 설계도

## 객체 Object

- 클래스에서 선언된 모양 그대로 생성된 실체
- 프로그램에서 구현할 대상
- 클래스의 인스턴스
- 모든 인스턴스를 대표하는 포괄적인 의미
- 클래스 타입으로 선언되었을 때 ‘객체’라고 부른다.

## 인스턴스 Instance

- 객체가 **메모리에 할당**되어 프로그램에서 사용되는 데이터
- 객체를 소프트웨어 실체화한 것
- 추상적인 개념과 구체적인 객체사이의 관계에 초점을 맞출 경우 사용한다.
    - 원본 → 생성된 복제본
    - 객체는 클래스의 인스턴스이다.
    - 객체 간의 링크는 클래스 간 연관 관계의 인스턴스이다.
    - 실행 프로세스는 프로그램의 인스턴스이다.

### 클래스 vs 객체

- 클래스: 설계도
- 객체: 설계도로 구현한 모든 대상

### 객체 vs 인스턴스

- 객체: 클래스 타입으로 선언되었을 때
- 인스턴스: 객체가 메모리에 할당되어 실제 사용될 때