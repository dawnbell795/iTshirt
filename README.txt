개발자 티셔츠 쇼핑몰 오픈소스

1) git 처음 생성시 - git init : 초기화 과정으로 로컬저장소 생성
2) .git 폴더를 로컬저장소라고 한다.
3) 버전 관리를 위해 자신의 정보 등록 (email, name)
    $ git config --global user.email "git에 로그인하는 email"
    $ git config --global user.name "누가 만들었는지 구분하기 위한 이름"
4) 커밋에 파일 추가
    $ git add 파일명
5) 커밋 실행 - 상세 설명 추가 가능
    $ git commit -m "사이트 설명 추가"
6) 