# tot_cmd

# **Intro**
- 패키징 및 숫자 입력, 계산 기능(더하기, 빼기, 곱하기)

## 최신 version
- 0.3.9

# **Usage**
## 설치 방법
```
$ pip install tot_cmd
```

## 더하기
```
$ tot_plus <숫자> <숫자>
<숫자> + <숫자> = <결과>
<예시> 1 + 2 = 3
```

## 빼기
```
$ tot_minus <숫자> <숫자>
<숫자> - <숫자> = <결과>
<예시> 10 - 5 = 5
```

## 곱하기
```
$ tot_multi <숫자> <숫자>
<숫자> * <숫자> = <결과>
<예시> 10 * 2 = 20
```

### cmd.py
```
from tot_plus.plus import plus
from tot_minus.minus import minus
from tot_multi.multi import multi

def call_plus():
	plus()

def call_minus():
	minus()

def call_multi():
	multi()
```
