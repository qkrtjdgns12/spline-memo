# <git 설치하기>
# 1.git 검색하기 
https://git-scm.com/

# 2. 설치후 Git bash열기 
![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/51a170f5-ba65-43e5-87d7-703dd96559ce)

# 2-1 유저이름 설정
- 임의로 이름을 넣으면 된다



---
git config --global user.name "park"
---



* 우클릭 > paste로 붙이기
![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/56be2799-65b0-4828-8286-f87b50a1cf8b)


# 2-2 유저 이메일 설정하기
- 반드시 gitHub가입시 사용한 이메일을 써주어야 한다. ★★★★

(sangd456@naver.com) 이다.

---

git config --global user.email "sangd456@naver.com"
---

![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/6a813935-5e24-4d5b-bd08-1203ce010d77)


# 2-3 정보 확인하기

↓ 입력하기
---
git config --list
---

![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/170e57d6-84d2-4467-be8f-7320684f3a49)


=================================위 작업은 한 컴퓨터에 한 번만 하면 된다

# GitHub에 처음으로 코드 업로드하기

※ 참고
![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/14f6ee6e-c7a1-4a74-bc71-dffb6b62c269)

## 1. 초기화

 ---
 git init
 ---
 ![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/a9b7e8c9-7dcb-422b-8757-8d797e2499f5)
![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/66ab2e1e-f0bb-4680-b00b-f5c4145b9426)

## 2. 추가할 파일 더하기

 ---
 git add .
 ---
![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/8c4fa614-9190-46bf-95cf-64110001f68f)



*.(점)은 모든 파일이라는의미, 선택적으로 올리고 싶으면 add 뒤에 파일이름을 붙여줌 (git add index.html)

## 3. 히스토리 만들기 - "first commit"에는 수정 및 등록에 대한 메모를 적음

 ---
 git commit -m "first commit"
 ---
 *-m은 메세지의 준말
 

master자리에 branch이름이 main이라는 의미
 ---
 git branch -M main
 ---

![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/fcfccab0-83ba-4264-8f14-39e8453019b4)

## 4.gitHub repository와 내 로컬 프로젝트랑 연결

---
git remote add origin https://github.com/qkrtjdgns12/flex-site.git
---
![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/7c6a7567-1d54-4bdf-969d-7909e4ef4d1c)


## 5. Github에 올리기
---
git push -u origin main
---
### 순서
![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/4a3feaa4-29b6-4302-b3ca-067ebd48c8f1)
![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/a3e4911b-9a5f-46eb-ad77-ac89e84988bc)




==========================================================================
# ＆ Github에 계속 업데이트 하는 방법 

# 1. 추가할 파일 더하기 
---
git add .
---
새로운 터미널을 연다.
![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/16f5c61b-c887-4595-a14b-758b047f8bda)


# 2. 히스토리 만들기

---
git commit -m"417 업그레이드"
---
![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/84339910-04a4-44b0-94fe-2e6a66c658ed)


# 3. Github에 올리기

---
git push -u origin main
---
![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/137d35b3-b8de-49be-9439-c582026a0083)

![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/4b627891-8f2f-4814-be7c-514b46212506)


# ??
![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/593b1785-eb46-4b5b-8bb2-5219723d61f8)
![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/e1cd1d0d-3e89-4f2c-9a55-6be04edf5afc)
![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/06ce6e6d-9428-4e71-8f35-0d5f2a68e2ef)

![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/90de54ab-50fe-4fd4-a13c-a28697024a17)






 
