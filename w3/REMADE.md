# 2023_OSS
## 2023 OSS 수업 

-----
### 3주차 git

### 이미지
![한국항공대학교 로고](https://github.com/nparkcourage/2023-kau-0504/blob/main/w3/2023_OSS/img/kau/kau.png)


### 링크   
[LMS](https://lms.kau.ac.kr "항공대학교 강의관리시스템")

#### ProGit 링크
[ProGit](https://git-scm.com/book/ko/v2 "git 문서, 한국어")


##### 주요 git 명령어
* add : 파일을 추적 대상으로 포함시킬 때, 또는 커밋 대상으로 포함시킬 때 사용
    * 예) git add <file name>
* commit
* git reset HEAD <file> : stage된 파일을 unstaged로 변경
* git checkout -- <file> : stage되어 있는 파일을 수정한 후 수정 전으로 되돌림 
* branch
* merge
* status
* log
    * 예) git log --oneline --decorate --graph --all

------
### 2주차 숙제

```bash

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
echo "file path :"
echo "$FILE_PATH"
echo " "
echo "----------"
echo "line number :"
echo "$LINE_NUMBER"
echo " "
echo "----------"
echo "last line :"
echo "$LAST_LINE"

```

## 마크다운
### 목록
#### 번호 있는 목록 : 내림차순 정렬
1. 첫번째
3. 세번째
2. 두번째

#### 번호 없는 목록 : *, -, +
* 첫번째
- 세번째
+ 두번째
-----
* 빨강
  * 녹색
    * 파랑

### 강조
*single asterisks*    
_single underscores_    
**double asterisks**    
__double underscores__    
~~cancelline~~    
