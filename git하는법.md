# git 설치하기
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
- ![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/138d1326-325d-4468-89f4-72f42aa211e5)

# 2-2 유저 이메일 설정하기
- 반드시 gitHub가입시 사용한 이메일을 써주어야 한다. ★★★★

(sangd456@naver.com) 이다.

---

git config --global user.email "sangd456@naver.com"
---

![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/56679397-e957-4887-ada5-fdc91820798f)

# 2-3 정보 확인하기

↓ 입력하기
---
git config --list
---

![image](https://github.com/qkrtjdgns12/spline-memo/assets/163283968/1bac872a-5cee-40ed-844e-4bc337b2698f)

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

##2. 추가할 파일 더하기

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

master자리에 branch
 ---
 git branch -M main
 ---

## 4.gitHub repository와 내 로컬 프로젝트랑 연결

---
git remote add origin https://github.com/qkrtjdgns12/flex-site.git
---

## 5. Github에 올리기
---
git push -u origin main
---








 
