# 파이썬 경진대회 1팀
> 파이썬 경진대회 1팀입니다. 모르는게 있으면 질문하도록 합시다


python selenium을 잘 다루도록 노력합니다

## pip 설치

```sh
pip install selenium
```
## sqlite3 db 생성

```sh
./sqlite3 [DB이름]
```

## sqlite3 table 생성

```sh
# db 접속
./sqlite3 [DB이름].db

# db 접속 후 create
create table [table이름](
   TransSeq int primary key,
   FromSaupjaRegNo text,
   FromSaupjangNo text
);
```

## 개발기간

* 2021/07/27
    * table 생성 및 개발 시작
* 2021/07/29
    * 브라우저에 인증서 가져오기
    * 여러 회사일 경우 이름만 바꾸면 패스워드와 인증서가 자동으로 바뀌게 설정
* 2021/08/02
    * 더블클릭 오류로 데이터를 볼수있는 방법 탐색
    * 상세보기 클릭으로 데이터를 가져오는 방법 채택
* 2021/08/03
    * db에 데이터 축적 시작
    * 승인번호가 안가져와지는 에러 발생
* 2021/08/04
    * 승인번호 안가져와지는 에러 해결
    * 에러 해결후 중복이 언되도록 승인번호를 기준으로 중복값 판단
* 2021/08/05
    * 접속하는 시간이 너무 길어 Explicit Waits 방식 채택
    * 로딩이 끝날때 바로 실행 할수 있도록 설정
* 2021/08/06
    * 가끔씩 로딩을 2번하는 경우가 있어 Explicit Waits가 에러를 발생
    * 몇몇 구간은 sleep으로 처리
* 2021/08/23
    * 소장님께 완료 보고

