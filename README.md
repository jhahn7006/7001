<!DOCTYPE html>

<html>



<head>

<meta charset="ISO-8859-1">

<title>고속/시외버스 차량정보</title>

<style></style>



</head>


<div module="layout_logincheck">
    <!--
        $url = /member/login.html
    -->
<body>

     <h3>저장과 전송버튼을 모두 눌러주세요</h3>

     <table border="2" >



     <!-First row->

          <tr>

               <td>

                    기점출발시간
               </td>

               <td>

                    <input type="text" name="기점출발시간"></input>

               </td>

          </tr>



     <!-third row->

          <tr>

               <td>

                    차량번호

               </td>

               <td>

                    <input type="text" name="차량번호"></input>

               </td>

          </tr>


     <!-fourth row->

          <tr>

               <td>

                    차종 

               </td>

               <td>

                    <input type="text" name="차종"></input>

               </td>

          </tr>




     <!-Fifth row->

          <tr>

               <td>

                        제조사

               </td>

               <td>

                    <input type="checkbox" name="현대">현대</input>

                    <input type="checkbox" name="기아">기아</input>

                    <input type="checkbox" name="대우">대우</input>

               </td>

          </tr>


     <!-Fifth row->

          <tr>

               <td>

                        차량등급

               </td>

               <td>

                    <input type="checkbox" name="일반">일반</input>

                    <input type="checkbox" name="우등">우등</input>

                    <input type="checkbox" name="프리미엄">프리미엄</input>

               </td>

          </tr>


     <!-Seventh row->

          <tr>

               <td>

                    <input type="button" name="btn1" value="저장" onclick="alert('저장에 성공했습니다')">
                    <input type="button" name="btn2" value="전송" onclick="alert('전송에 성공했습니다')">

               </td>


          </tr>



     </table>



</body>

</html>
