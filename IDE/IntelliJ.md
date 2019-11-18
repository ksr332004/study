# 1. Toolbox
- IDE의 버전 관리
   - 신규 제품 다운로드 및 설치
   - 일괄 최신 버전으로 업데이트
   - 이전 버전 설치
   - 설치 제품 삭제
- 프로젝트 관리
- 각 IDE만의 JVM 옵션 관리

# 2. 메인 메소드 생성 및 실행
- 코드 템플릿 생성
   - [참고URL](https://118k.tistory.com/802)
- 프로젝트의 패키지, 클래스 등 생성 단축키
   > command + n
- 현재 포커스에서 실행
   > control + shift + R
- 이전 실행
   > control + R

# 3. 라인 수정하기
- 라인 복사하기
   > command + D
- 라인 삭제하기
   > command + backspace
- 라인 합치기
   > control + shift + J
- 구문 단위로 코드 이동
   > shift + command + 방향키(위/아래)
- 라인 단위로 코드 이동
   > shift + option + 방향키(위/아래)
- Element 단위로 이동
   > option + shift + command + 방향키(좌/우)

# 4. 코드 즉시 보기
- 인자값 즉시 보기
   > command + P
- 코드 구현부 즉시 보기
   > command + space
- DOC 즉시 보기
   > F1

# 5. 포커스 에디터
- 라인의 처음/끝 이동
   > fn + 방향키(좌/우)
- 페이지 단위로 이동
   > fn + 방향키(위/아래)

# 6. 포커스 특수키
- 포커스 범위 한 단계씩
   > option + 방향키(위/아래)
- 이전/이후 포커스 위치 이동
   > command + [   
   > command + ]
- 멀티 에디트 포커스
   > option + option + 방향키(아래)
- 오류 라인 자동 포커스
   > F2

# 7. 검색 텍스트
- 현재 파일 내에서 검색
   > command + F
- 현재 파일 내에서 특정 문구 교체
   > command + R
- 전체에서 검색
   > command + shift + F
- 전체에서 특정 문구 교체
   > command + shift + R
- 현재 파일 내 혹은 전체에서 검색시 Regex 선택하면 정규표현식을 이용하여 검색 가능

# 8. 검색 기타
- 파일명으로 검색
   > shift + command + O
- 메소드명으로 검색
   > option + command + O
- Action으로 검색
   > shift + command + A
- 최근 열었던 파일 목록 보기
   > command + E
- 최근 수정했던 파일 목록 보기
   > command + shift + E

# 9. 자동완성
- 스마트 자동 완성
   > control + shift + space
- static 메소드 자동 완성
   > control + space + space
- getter/setter/생성자 자동 완성
   > command + N
- Override 메소드 자동 완성
   > control + I

# 10. Live Template
- 현재 포커스에서 가능한 Live Template 목록 보기
   > command + J

# 11. 리팩토링 단축키
- 변수 추출하기
   > command + option + V
- 파라미터 추출하기
   > command + option + P
- 메소드 추출하기
   > command + option + M
- Inner 클래스 추출하기
   > F6
- 이름 일괄 변경하기
   > shift + F6
- 타입 일괄 변경하기
   > shift + command + F6
- Import 정리하기
   > control + option + O
   * Action에서 'optimize import on'을 검색 후 on하면 저장 시점에 자동 import를 정리함
- 코드 자동 정렬하기
   > command + option + L