# github_c

## 1.[깃설치](https://git-scm.com/download/win)
          git을 통해서 github와 연결할 수 있다


- 깃에 올려야 할 폴더에 가서 shift + 우클릭하여 powershell창 열기
                     git init 
      
      
- .git 폴더가 생성됨
----------------------Cancel changes

## 2. 깃 설치후 git bash 열기 (마우스 오른쪽)

          * 유저 이름 설정하기
          git config --global user.name"김민주"

          * 유저 이메일 설정하기 (반드시 github에 가입했던 이메일 주소와 동일해야 한다) 
          git config --global user.email "vousmeu@naver.com"
          
          * 내 정보 확인하기
          git config --list
          
## 위의 연결은 해당 컴퓨터에서 한번에 실행하면 됨 한번하고 또 할 필요 없다
--------------------------------------------------------------

# github에 코드 업로드하기
          * 초기화
            git init
          * 추가할 파일(폴더 안에 내용을 모두 올림, .은 모든 파일을 의미)
            git add .
          * 히스토리 만들기(-m은 메세지를 의미함 ""안에는 히스토리 이름을 적음
            git commit -m "first commit"
          * Github의 repository를 만들고 그 주소와 연결하기
            git remote add origin https://github.com/minjukimmm/css_flex.git
          * 연결이 잘 되었는지 확인하기 (사용 안 해도 됨)
            git remote -v
          * github에 올리기
            git push origin master
            
-----------------------------------
            
## 수정하여 다시 업로드할때

1. 기존의 코드를 다운받는 행위를 해야 한다.
          git pull origin master
          
2. 다시 push 해야 한다
          git push origin master
          
-----------------------------------

# Github 협업하는 방법

1. 소스코드 다운로드 

   git clone 주소 (넣을 폴더 만들고 <> code 초록창 html)
   
   git clone https://github.com/minjukimmm/hanacard.git
   
   
2. 수정 뒤 브랜치(branch) 만들기

   git checkout -b "kim"
   
   ![image](https://github.com/minjukimmm/github_c/assets/129017089/66b41dcb-7531-485d-abb5-24d7981bf13a)

          
          
      
