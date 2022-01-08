
### display:flex 와 같은 레벨의 디자인전용 레이아웃 속성(property)

- flex 속성과 비슷한 구조를 띄고 있다.
-- 부모태그와 자식태그와의 관계를 이해하고 활용한다.
-- 자식(item) 태그의 레이아웃을 정하기 위해서 부모태그(container)에 속성을 할당(assign)한다.

- 기준이 되는 속성과 하위 성격의 속성이 존재한다.

기준속성
display:flex;
하위속성
justify-content:center; <-- display:flex를 할당하지 않으면 사용할 수 없다.


- 하위속성 종류가 많다.

--------------------------------------------------------

# display:grid
- 그리드 레이아웃 속성이 생긴이유
- 디자이너의 니즈 발생
- 기존 방식 float으로 어렵게 작업했어야만 했음

### 그리드 = 격자
- "격자 모양의 레이아웃을 만들고싶다"

display:grid;
  - block level 그리드 요소로 자식태그가 배치방식의 정의된다.
display:inline-grid;
  - inline level 그리드 요소로 자식태그가 배치방식의 정의된다.




