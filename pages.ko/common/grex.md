# grex

> 정규 표현식을 생성.
> 더 많은 정보: <https://github.com/pemistahl/grex>.

- 간단한 정규 표현식 생성:

`grex {{공백으로_구분된_문자열}}`

- 대소문자를 구분하지 않는 정규식을 생성:

`grex -i {{공백으로_구분된_문자열}}`

- 숫자를 '\d'로 변경:

`grex -d {{공백으로_구분된_문자열}}`

- 유니코드 단어 문자를 '\w'로 변경:

`grex -w {{공백으로_구분된_문자열}}`

- 공백을 '\s'로 변경:

`grex -s {{공백으로_구분된_문자열}}`

- 반복되는 하위 문자열에 대한 {min, max} 수량자 표현을 추가:

`grex -r {{공백으로_구분된_문자열}}`
