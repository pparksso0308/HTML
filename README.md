# HTML

# 태그

## 단락 - p
문단을 나누는 태그

    <p>내용</p>             
    
## 줄바꿈 - br

    <br>

한개씩 존재

## 이미지 -img

    <img src="img.jpg" height ="300" alt="고양이 이미지" title = "고양이">

## 표 - table

    <table  border="1">                                // 테두리 굵기 설정
      <thead>                                          // table head  (두꺼운 글씨)
        <tr>                                             // table row(행)
          <td>이름</td> <td>성별</td> <td>나이</td>       // table data
        </tr>
      </thead>
      <tbody>                                           //table body
        <tr>   
          <td>소연</td> <td>여자</td> <td>21</td>
        </tr>
        <tr>
          <td>영준</td> <td>남자</td> <td>17</td>
        </tr>
      </tbody>
      <tfoot>
        <tr>
          <td>합계</td> <td></td> <td>38</td>             // 합계   (공백)    38
     </table>
