<h5>
개발 환경 : Windows 10 OS - 64bit<br>
개발 Tool : Spring<br>
DataBase : Oracle<br>
Open API : Kakao map API
  </h5>

<br>
<br>

# 카카오 맵 API를 활용한 웹 사이트
<p>카카오 맵 API를 이용해 웹 사이트에서 지도 객체를 생성해 사용할 수 있습니다. 
간단한 조작으로 원하는 장소의 카페를 찾을 수 있습니다.</p>

<br>
<br>

# 기능 구현
<h3>메인 홈 화면</h3>
<p>메인 홈페이지입니다. 상단의 Navigation으로 페이지를 쉽게 이동할 수 있으며, Navigation 아래로 페이지가 바뀝니다.
중앙에 지도는 Kakao 지도의 Javascript API를 활용하여 필요한 기능만 구성함과 동시에 기존의 지도와 동일한 조작이 가능합니다. 
</p>
<h3>지도</h3>
<p>중앙의 지도를 드래그하여 원하는 곳에 움직이면, 지도의 표시 범위를 기준으로 Kakao REST API에 ajax를 사용해 동적으로 카테고리에서 카페를 찾는 URL를 보냅니다.<br>
성공적으로 응답을 받으면 결과를 지도 하단에 표로 나타냅니다.
</p>
<h3>드래그 기능</h3>
<p>드래그 이후 다른 곳으로 지도를 이동 후 다시 API와 통신하여 결과를 받아온 후 표를 재 작성 합니다</p>
<h3>회원가입</h3>
<p>아이디, 패스워드, 이메일을 입력 받아 회원가입하는 페이지입니다.
datalist 태그를 사용하여 도메인 선택하거나 입력 가능하도록 구현하였습니다. 
</p>
<h3>로그인</h3>
<p>DB에 등록되어 있는 아이디, 패스워드를 입력 받아 로그인 하는 페이지입니다. 
회원가입이 되어 있지 않은 사용자는 회원가입 버튼을 클릭하여 회원가입 페이지로 이동할 수 있습니다. 
</p>
<h3>제보 작성 화면</h3>
<p>DB에 등록되어 있는 카페나 등록되지 않은 카페에 대하여 사용자가 제보할 수 있는 게시물 등록 양식입니다. 관리자는 이를 확인하고 제보 받은 사항을 적용할 수 있습니다</p>
<h3>제보 상세 화면</h3>
<p>등록되어 있는 글의 상세 내용을 볼 수 있는 화면입니다. 댓글을 작성할 수 있고, 해당 글의 작성자는 글을 수정하거나 삭제할 수 있습니다. 하단 부분에서 해당 글에 대해 작성된 댓글의 목록을 함께 볼 수 있습니다.
</p>
<h3>제보 목록 화면</h3>
<p>등록되어 있는 게시물의 목록을 볼 수 있는 화면입니다. 검색범위 설정 후 키워드를 검색하면 해당되는 게시물이 보여지도록 구현하였습니다.
</p>
