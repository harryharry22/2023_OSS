#2023_OSS

3주차 강의 : [w3 디렉토리](./w3/README.md)

##w3
![이미지](https://github.com/nparkcourage/2023-kau-0504/blob/main/w3/2023_OSS/img/kau/kau.pn)

[LMS](https://lms.kau.ac.kr/)

[ProGit 링크](https://git-scm.com/book/ko/v2)

[주요 git 명령어]

add : 파일을 추적 대상으로 포함시킬 때, 또는 커밋 대상으로 포함시킬 때 사용
   예) git add
commit
git reset HEAD : stage된 파일을 unstaged로 변경
git checkout -- : stage되어 있는 파일을 수정한 후 수정 전으로 되돌림
branch
merge
status
log
예) git log --oneline --decorate --graph --all

##2주차 숙제

\`\`\`c

STUDENT_ID="2020125049"
NAME="이종엽"

FILE_PATH=$(find /home/kau2 -name "w2_homework.txt")

LINE_NUMBER=$(wc -l < "$FILE_PATH")
LAST_LINE=$(tail -n 1 "$FILE_PATH")

echo "----------"
echo "name :"
echo "$NAME"
echo " "
echo "----------"
echo "student id :"
echo "$STUDENT_ID"
echo "----------"
echo " "
echo "file path:"
echo "$FILE_PATH"
echo " "
echo "----------"
echo "line number :"
echo "$LINE_NUMBER"
echo " "
echo "----------"
echo "last line :"
echo "$LAST_LINE"

\`\`\`
