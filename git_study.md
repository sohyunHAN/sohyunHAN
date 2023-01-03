# 깃 설치하기
-깃에 가서 다운 받아서 설치한다
    -- 깃의 브랜치를 main에서 master로 변경

# 깃으로 관리할 폴더 선택해서 git bash열기
- 해당 폴더에 오른쪽 버튼 git bash here로 쉘 명령어열기

# 깃의 초기 설정하기
-(개인용 PC 일경우) 한번 설정 하면 됨 (아이디,이메일-gmail사용 권장)
    
    git config --global user.name "깃 허브 아이디"
    git config --global user.email "깃 허브 계정메일"

# 깃 초기화된 환경 확인하기
    git config --global --list

# 깃의 상태 확인하기
    git status

# 깃이 관리하는 폴더로 만드려면
    git init
- 주의! 하위 폴더는 깃의 관리 대상이 됨 
- __그러므로 하위폴더를 git init 하면 안됨!!__
- cd.하위폴더명 -> 하위폴더로 들어갈 수 있음

# staging area에 파일 올리기
    git add 파일명.확장자
    git add 폴더명// 해당 폴더를 올린다.
    git add . // 모든 파일을 다 올린다.


## 연습
- c.txt를 만들고 그곳에 임의의 문자 입력 후 깃 상태확인
- 깃 상태 확인 후 commit 