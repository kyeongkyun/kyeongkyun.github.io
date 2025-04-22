
### 연산자자
연산자                | 의미                   | 사용 위치     | 예시                             | 설명
-------------------|----------------------|-----------|--------------------------------|----------------------
?.                 | null-safe 접근 (읽기 전용) | 속성, 메서드   | _obj?.ToString()               | _obj가 null이 아니면 호출
?[]                | null-safe 인덱서 접근     | 배열, 컬렉션   | _dict?["key"]                  | _dict가 null이면 null 반환
??                 | null 병합 연산자          | 변수 할당, 반환 | var name = input ?? "default"; | null이면 오른쪽 값 사용
??=                | null이면 대입            | 변수 초기화    | x ??= new List<int>();         | x가 null일 때만 새로 할당
is null            | null 비교              | 조건문       | if (x is null)                 | x == null과 동일
is not null        | not null 비교          | 조건문       | if (x is not null)             | x != null과 동일
! (null-forgiving) | 컴파일러 null 경고 무시      | 변수 뒤에     | str!                           | null 아님을 강제로 보증

