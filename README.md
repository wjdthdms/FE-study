# Q. == 과 === 의 차이점 / 얕은 복사와 깊은 복사

## 1. == 과 === 의 차이점

> == (동등 연산자), === (일치 연산자)

* == (Loose Equality): 값이 같으면 true, 다르면 false 반환 / 값이 같아도 타입이 다르면 자동 변환 후 비교

```
1 == '1' (true), null == undefined (true)
```
* === (Strict Equality): 값과 타입이 모두 같아야 true 반환
```
1 === '1' (false), null === undefined (false)
```
