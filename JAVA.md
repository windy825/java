# 01.16 JAVA



- **자료형**

  > `Primitive type` 기본형

  ```python
  정수형 (byte, short, int, long) 값 범위 >>> -2**(n-1) ~ 2**(n-1) # n은 비트 수
  	
  # int 타입의 경우 대략 10자리 수(대략 -20억 ~ 20억 표현 가능)
  # 7~9자리 수를 표현할때는 넉넉하게 long 타입(약 19자리)을 사용하자
  ```

  

  - `boolean`은 true 와 false 두 가지 값만 표현하면 되므로 가장 작은 크기인 *1 byte*
  - `char` 은 자바에서 유니코드(2 byte 문자체계)를 사용하므로 *2 byte*
  - `byte`는 크기가 1byte이므로 *1 byte*
  - `int`*(4 byte)*를 기준으로 짧아서 `short`(2 byte), 길어서 `long`*(8 byte)*
  - `float`은 실수값을 부동소수점(floating-point)방식으로 저장하기 때문에 *4 byte*
  - `double`은 float보다 두배 크기를 갖기 때문에 *8 byte*
  - 

  > `Reference type`