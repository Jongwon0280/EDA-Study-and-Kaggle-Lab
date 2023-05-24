### 멜론 음원 크롤링
> 멜론 스트리밍웹의 장르별 음악의 제목과 아티스트, 가사정보를 얻기위해 Selenium라이브러리를 활용하여 크롤링 하였습니다.

  <table border="1" width ="500" height="300" align = "center">
	<th>장르코드</th>
	<th>장르명</th>
	<tr><!-- 첫번째 줄 시작 -->
	    <td> GN0100 </td>
	    <td> 발라드 </td>
	</tr><!-- 첫번째 줄 끝 -->
  	<tr><!-- 첫번째 줄 시작 -->
	    <td> GN0200 </td>
	    <td> 댄스 </td>
	</tr><!-- 첫번째 줄 끝 -->	<tr><!-- 첫번째 줄 시작 -->
	    <td> GN0300 </td>
	    <td> 랩 힙합 </td>
	</tr><!-- 첫번째 줄 끝 -->	<tr><!-- 첫번째 줄 시작 -->
	    <td> GN0400 </td>
	    <td> R&B </td>
	</tr><!-- 첫번째 줄 끝 -->	<tr><!-- 첫번째 줄 시작 -->
	    <td> GN0500 </td>
	    <td> 인디음악 </td>
	</tr><!-- 첫번째 줄 끝 -->	<tr><!-- 첫번째 줄 시작 -->
	    <td> GN0600 </td>
	    <td> 락메탈 </td>
	</tr><!-- 첫번째 줄 끝 -->
  	</tr><!-- 첫번째 줄 끝 -->	<tr><!-- 첫번째 줄 시작 -->
	    <td> GN0700 </td>
	    <td> 트로트 </td>
	</tr><!-- 첫번째 줄 끝 -->
  	</tr><!-- 첫번째 줄 끝 -->	<tr><!-- 첫번째 줄 시작 -->
	    <td> GN0800 </td>
	    <td> 포크/블루스 </td>
	</tr><!-- 첫번째 줄 끝 -->
    </table>
    
<br>

장르별로 규정된 코드를 통해 각 장르별 음원차트의 각페이지당 50개의 음악 정보를 가져왔고, 

![image](https://github.com/Jongwon0280/EDA-Study-and-Kaggle-Lab/assets/56438131/1fd4d48a-c0db-47fa-8891-0c3c3e0663e1)

각 음원의 상세 페이지에 접근하여 가사정보 및 음원정보를 가져왔습니다.

<br>

### 결과물
> 각 장르별 음원의 메타정보를 csv파일 형태로 가져올 수 있었습니다.

![image](https://github.com/Jongwon0280/EDA-Study-and-Kaggle-Lab/assets/56438131/69eed29c-ad9b-451e-98b9-b9d7ba8bdad7)


