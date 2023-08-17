# 로그 분석을 통한 유저 행동 분석

### 1 프로젝트 소개
1.1 프로젝트 개요   
* 로그 분석을 통해 웹 및 앱 애플리케이션의 사용자 행동 및 패턴을 이해하고 이를 바탕으로 애플리케이션 개선을 위한 액션을 도출하고자함.
    
1.2 프로젝트 소개
* 프로젝트 기간 : 2023.07.17 - 2023.07.21
* 기술 스택 : ```Python```
* 1인 프로젝트

<br> 
  
### 2 프로젝트 진행절차
2.1 데이터 소개
* 데이터 shape : 301861 rows × 7 columns
* columns : actiontype, ismydoc, ext, sessionid, documentposition, datetime, screen
* 출처 : Kaggle
  
2.2 데이터 전처리
* datetime은 datetime으로 타입 변환.
* 요일 컬럼 생성.
* sessionid의 경우 보기 쉽게 int로 변경.  
  ![image](https://github.com/KIMJEONGSU/logs/assets/23291338/53c16fc1-8502-419b-be56-973e21ad233d)


2.3 EDA
<table>
  <tr>
    <td>
      <img src='photo/.png' width="100%" height="100%">
    </td>
    <td>     
        <p><customer 데이터></p>
    </td>
  </tr>
    <tr>
    <td>
      <img src='photo/.png' width="100%" height="100%">
    </td>
    <td>     
        <p><customer 데이터></p>
    </td>
  </tr>
</table>

### 3. 결론
### 4. 한계점 및 개선사항
* 한계점
  * 2016년 7월의 데이터만 존재하고 시간 데이터는 존재하지 않는점.
* 개선사항
  * 추후에 직접 로그 데이터를 수집하여 분석 예정
