# 알아야하는 git 명령어 저장
---

```bash
cd my-new-project      # 새 디렉토리로 이동
git init               # 새 Git 리포지토리 초기화
git remote add origin "내 깃 주소" # 깃 주소는 .git으로 된 주소
git checkout -b main   # 새 브랜치(main) 생성
git add .
git commit -m "첫 커밋"
git push -u origin main

git clone https://github.com/otheruser/their-repo.git
cd their-repo
rm -rf .git                    # 기존 Git 이력 제거
git init                       # 내 Git으로 새로 시작
git remote add origin https://github.com/yourname/your-repo.git
git checkout -b main
git add .
git commit -m "내 버전 시작"
git push -u origin main


```