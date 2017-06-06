#__GIT Command Line 명령어 정리__
* * *
#### __1. 환경설정__
> - git config --global user.name "사용자명"
> 사용자명을 등록합니다 (필수)
> 
> - git config --global user.email "이메일주소" 
> 이메일 주소를 등록합니다. (필수)

#### __2. 기본명령어__
> -  git init
> 현재 디렉토리에 git 저장소를 생성합니다.
> 
> - git status
> 파일의 상태를 확인합니다.
>
> - git add 파일명
> Untracked files을 Staging Area에 올립니다.
> - git commit -m "커밋 메시지"
> Staging Area에 있는 파일을 저장소에 추가한다.
> - git checkout 브랜치명
> ![Alt text](/uploads/git/gitFile.png)
> 과거의 작업 폴더로 되돌아간다.

#### __3. 원격저장소__
> - git clone 저장소주소
> 원격저장소를 복제하여 저장소를 생성합니다.
> - git remote add 이름 저장소주소
> 새로운 원격 저장소를 추가합니다.
> - git remote
> 추가한 원격저장소의 목록을 확인합니다.
> - git remote rm 이름
> 원격저장소를 제거합니다.

#### __4. Branch & Merge__
> - git branch 
> 브랜치의 종류와 현재 작업중인 브랜치를 확인 할수 있습니다.
>  ![Alt text](/uploads/git/branchFile.png)
> - git branch 브랜치명
> 새로운 브랜치를 생성합니다.
> ![Alt text](/uploads/git/branchFile2.png)
> - git branch -d 브랜치명
> ![Alt text](/uploads/git/branchFile3.png)
> - git merge 브랜치명
> 현재 작업중인 브랜치에 다른 브랜치에서 작업한 내용을 추가합니다.
