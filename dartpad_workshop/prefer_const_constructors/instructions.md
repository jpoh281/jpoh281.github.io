# 안녕하세요! DartPad Workshop 예시 입니다.
## 이번 워크샵을 통해 Const 생성자 유무의 차이에 대해서 한번 배워보도로 하겠습니다.

지금 현재는 const가 붙어있지 않은 자식 위젯을 가지고있는 페이지입니다.
setState를 호출해 const를 붙였을 때와 붙이지 않았을 때의 차이를 한번 살펴봅시다.


ChildWidget의 생성자

```dart
const ChildWidget({Key? key}) : super(key:key);
```

MyHomePage Column 안

```dart
const ChildWidget()
```

다음과 같이 변경시켜주세요.
