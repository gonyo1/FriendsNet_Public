# FriendsNet

FriendsNet은 학생들의 설문 결과를 기반으로 한 교우관계 그래프를 생성하여 학급 내 사회적 관계를 시각화하는 프로그램입니다. 사용자는 구글 설문지를 통해 학생들의 응답을 일괄 다운로드하여 프로그램에 입력하거나, 학생들이 직접 응답한 내용을 수동으로 입력할 수 있습니다. FriendsNet을 학급운영에 사용하면 학급 내 사회적 관계를 더 잘 이해하고 관리할 수 있도록 도와줍니다.
<p align="center">
<img src="https://i.imgur.com/6YS0BN4.png" width="60%"/>
</p>

## 사용방법
https://github.com/gonyo1/FriendsNet_Public/assets/121369699/e4dd8ced-3b9a-4bc5-9ec0-af6920fd38ff

1. **[FriendsNet.ext]** 을 클릭하여 프로그램 실행하기
2. **[설문지 생성 및 결과 입력]** 클릭
3. **[NEIS > 학급담임 > 명렬표출력 > 조회 > 명렬표내용선택]** 클릭 후 성별 추가하여 **[엑셀내려받기]**
4. 학생명렬표.xlsx 를 프로그램(설문지 생성하기 탭) 에 드래그하여 데이터 입력
5. **[설문지 생성]** 버튼 클릭 후 hwp 파일 출력하기
   * 프로그램 재실행 필요

7. 설문 실시 (두 가지 중 한 가지 선택)
   1) 오프라인으로 실시
      가) 출력물을 나누어주고 교우관계 검사 실시
      나) 학생별 데이터를 **[설문 결과 입력하기]** 에서 입력
      다) **[파일 저장하기]** 클릭하여 csv 데이터 저장하기
         
   2) 온라인으로 실시
      가) Google 설문지 준비
        (1) 프로그램의 **[Google 설문 복제]** 탭 클릭
        (2) **[설문지 준비]** 클릭 후 **[템플릿 사용]** 클릭
        (3) 생성된 설문지의 학생 기본 자료 입력에서 **학생 번호**를 입력하기
        (4) 설문지의 1번 문항에 **학생 이름**을 모두 작성하기
        (5) 문항 아래 쪽의 [복사]를 클릭하여 10개 문항 만들기
        (6) [보내기] 클릭 후 URL을 단축하여 [복사] 버튼 누르기
        (7) 프로그램에서 [QR코드 생성] 클릭 후 설문 실시
      나) Google 설문 결과 입력
        (1) 구글 설문의 [응답] 탭에서 [Sheets에 연결] 클릭
        (2) [새 스프레드시트 만들기 ... > 만들기] 클릭
        (3) 스프레드시트 상단의 [파일 > 다운로드 > 쉼표로 구분된 값(.csv)] 를 순서대로 클릭하여 다운로드
        (4) 프로그램의 [CSV 파일 추가하기] 탭에서 다운로드 한 CSV 파일을 드래그하여 업로드하기
          * 추후에 자동업로딩 기능 탑재 예정
      
8. 교우관계 분석 결과 살펴보기
   1) 대시보드
     - 학급 내 성비, 교우관계 유형, 유형별 학생목록
     - 시기에 따른 학급 밀집도 그래프
     - 위기학생 및 버럭이 리스트
     - 학급 내 영향력 순위 리스트
   2) 설문결과 확인
     - 전체 학생 분포
     - 학생 개인별 연결망 확인

## 기능

### 1. 대쉬보드
- 학급의 기본 정보 표시
- 교우관계 유형별 학생 목록 제공
- 학급 내 밀집도 확인
- 위험군 학생 안내
- 학급 내 영향력 순위 표시

### 2. 설문 결과 분석 페이지
- 학급 내 교우관계 상황에 대한 다양한 정보 제공
- 영향력이 큰 학생들의 시각적 표시: 영향력이 큰 학생들은 교우관계 그래프에서 크게 표시됨
- 긍정적으로 평가되는 학생들의 시각적 표시: 학생들의 긍정적 평가가 화살표로 표시되며, 서로를 긍정적으로 평가하는 경우 진하게 표시하여 사회관계망을 파악 가능
- 개별 학생들의 교우관계 상태 진단: 선택한 학생이 긍정적으로 평가하거나 선택된 학생을 긍정적으로 평가하는 목록을 시각적으로 제공하여 학생의 사회망을 진단 가능
   
   
## 설문 결과 입력
FriendsNet에 설문 결과를 올리는 방법은 다음과 같이 두 가지입니다

### 1. 구글 설문지를 통한 일괄 다운로드
- 사용자는 먼저 구글 설문지를 활용하여 학생들에게 설문을 보냅니다.
- 학생들이 설문에 응답하면, 구글 설문지에서 설문 결과를 다운로드할 수 있습니다.
- FriendsNet 프로그램에서는 이 다운로드된 파일을 입력으로 사용하여 설문 결과를 분석합니다.
- 사용자는 프로그램의 입력 창을 통해 다운로드한 파일을 업로드하여 설문 결과를 즉시 분석할 수 있습니다.

### 2. 수동 입력
- 학생들이 설문에 직접 응답한 내용을 수동으로 입력할 수 있습니다.
- 사용자는 프로그램의 입력 창을 통해 학생들의 응답을 직접 입력할 수 있습니다.
- 이 방법은 구글 설문지를 사용하지 않는 경우로 스마트기기 활용이 원활하지 않은 저학년을 대상으로 진행할 때 사용할 수 있습니다.


### Contributor
KimTaeha, AhnJongho
