# sass 사용거의안함, scss를 사용한다. scss-->샤스라고 읽음
![image](https://github.com/1004minjeong/sass/assets/129016976/3a0eb45f-1164-48af-ae72-9e3f1e89390e)

# scss 컴파일
![image](https://github.com/1004minjeong/sass/assets/129016976/7a1b7a4c-9e5d-4f65-8963-9d4882de245e)

# css 위치변경
![image](https://github.com/1004minjeong/sass/assets/129016976/8c54e40d-b625-4c2b-a9b7-fee01c74b883)

# savePath:null이면 scss파일과 같은위치에 style.css가 생긴다
![image](https://github.com/1004minjeong/sass/assets/129016976/e9d3fc9d-fa8a-4691-ac42-403f3e0dcf06)

# "~"은 style.scss를 의미, "/"는 style.scss가 있는폴더 (css폴더는 scss의 자식폴더가 됨)
![image](https://github.com/1004minjeong/sass/assets/129016976/05b2a55f-dc41-425d-8183-07a6ecaf88cd)

# ../css는  scss의 상위폴더로 생성
![image](https://github.com/1004minjeong/sass/assets/129016976/ee01aadd-fb5b-426c-8236-d69b5567aa70)

# 주석처리 방법 (//사용)
# (//)주석처리방법은 CSS로 컴파일되지 않는다
# (/* */)주석처리 방법은 css로 컴파일되어 나타남
![image](https://github.com/1004minjeong/sass/assets/129016976/5f34daca-8b00-4ae1-bd84-7f8ee5f01b12)

# 변수만들기 --> 앞에 $로 시작함,(영문,숫자, - , _ )만 사용할수 있음, 숫자로 시작할수 없음!
![image](https://github.com/1004minjeong/sass/assets/129016976/0acbdb56-cad8-4343-81c1-4fbeba1c4565)

# 변수과정
![image](https://github.com/1004minjeong/sass/assets/129016976/3936cf9a-40b8-4ab7-aad6-6d8da56ec307)


# wrap안에있는
![image](https://github.com/1004minjeong/sass/assets/129016976/19c8a825-53bc-4ec4-a6e3-d211e1df2e45)

# Partials(파샬)
 --관련된것끼리 묶어서 분리/ 소스에 반복되는 부분들을 분리 분산시켜 모듈화(부품화) 시키는 기능
 
 * partials의 파일명은 "_"로 시작하며
 * 불러들일때는 @import '파일명' 이때 파일명에 "_"는 포함시키지않고, 확장명도 포함시키지 않는다. 

※ Scss는 "_"로 시작하는 파일은 컴파일 하지 않는다.
![image](https://github.com/1004minjeong/sass/assets/129016976/928a1dd8-849f-4280-adad-8c6287da2d63)

# @import -- 변수가 중복될때는 아래의 것이 적용된다.
![image](https://github.com/1004minjeong/sass/assets/129016976/4667d71f-601b-4822-8e00-5482e9dce3f6)


# @use --> 변수이름이 같을때 에러발생, @use를 사용할때는 앞에 파일명을 추가해서 파일명,변수명
![image](https://github.com/1004minjeong/sass/assets/129016976/1a2c36c9-1fae-45eb-b8c2-f7adedaba988)

# as 뒤에 별명을 붙여서 사용할수 있다.
![image](https://github.com/1004minjeong/sass/assets/129016976/126e54c0-0410-452c-93a4-a8957e488977)

# @forward 는 파샬을 묶어줌
![image](https://github.com/1004minjeong/sass/assets/129016976/48c0f882-69c1-4240-a37a-a227a695ff47)






