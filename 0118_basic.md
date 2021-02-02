# 기초 문법

### print

- `print();print()` 하면 연결해서 출력 가능 but 잘 쓰지 않음
- print문 내에서 그냥 줄바꾸면 syntax error (\로 해결가능 but 잘 쓰지 않음)
- print문 내에 여러 줄을 쓰고 싶으면 `print("""       """)`



### 식별자

- `keyword.kwlist` 키워드 사용 불가



### 이스케이프 시퀀스

- `\n` 줄 바꿈
- `\t` 탭
- 문장부호를 그대로 출력하려면 앞에 `\` 붙이기



### 포매팅

1. `%d`: 정수   `%f` : 실수   `%s`: 문자열
   - `%s' % name` 이런식으로 사용
2. `'{}.format(name)'` 
   - `'hello, {}'.format(name)` 이런식으로 사용
3. `f'{name}'`
   - `f'hello {name}'` 이런식으로 사용





pi = 3.141592

`pi: .4` : 3.142 넷째자리에서 반올림



### Boolean

- False type: 0, 0.0, (), [], {}, '', None



### 형변환

- 암시적 형변환
  - bool + int = int
  - int + float = float
  - int + complex = complex
- 명시적 형변환
  - str(int) + str = str
  - int(str) + int = int
  - float(str)  # str은 글자가 숫자일때만 형변환 가능
  - int(float) -> 소수점 제외하고 정수 반환 (srt '3.5'는 int로 변환 불가)
  - 















