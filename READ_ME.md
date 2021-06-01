<html>
<header>
      <div data-spy="affix" data-offset-top="30" class="header-affix affix-item" ">
          <audio autoplay controls> <source src="1.mp3" type="audio/mp3"> </audio>
      </div>
      <meta charset="UTF-8">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>초보자도 할 수 있는 SQL</title>
<style>
      h1 { text-align: center; }
      h3 { text-align: center; }
      p { text-align: center;}
</style>
<link href="https://fonts.googleapis.com/css?family=Nanum+Gothic&display=swap" rel="stylesheet">
<style>
body {font-family: 'Nanum Gothic', sans-serif;}
h1 {margin : 1rem;}
details {padding : 1rem; white-space: pre-wrap;}
.question {margin : 2rem; padding : 1rem; border: 1px solid gray;}

</style>
</header>

<body>

<h1>[초보자도 할 수 있는 SQL]</h1>
<h3>이성규,조태익,강정현</h3>

<div class='question' id='Q1'>

      <h4>1. 직원의 이름과 직책(job_title)을 출력(검색) 단, 사용되지 않는 직책이 있다면 그 직책이 정보도 검색에 포함 검색 정보 이름(2개)들과 job_title(직책) </h4>
      <form action="채점을 해보자">
            <textarea cols="30" rows="5" placeholder="여기에 sql문을 입력후 제출을 눌러주세요 "onfocus="this.placeholder=''"
            onblur="this.placeholder='진짜 입력해보세요 채점해 줄게영'"></textarea>
            <br>
            <br>      
            <input type="onsubmit" value="제출" class="btn btn-success" id="button1" onclick="button1_click();"  />
        <script>
          function button1_click() {
          	alert("연결 안했쥬 속았쥬 모범 답안을 눌러서 비교 해보세여 ㅎㅎ ");
          }
        </script>
        </form>       
      <details>
            <summary>모범 답안</summary>
            <strong>SELECT</strong>e.first_name, j.job_title
            <strong>FROM</strong>employees e join jobs j
            <strong>ON</strong>e.job_id = j.job_id;

            FIRST_NAME                               JOB_TITLE
            ---------------------------------------- ----------------------------------------------------------------------
            William                                  Public Accountant
            Shelley                                  Accounting Manager
            Jennifer                                 Administration Assistant
            Steven                                   President
            Neena                                    Administration Vice President
            Lex                                      Administration Vice President
            Jose Manuel                              Accountant
            Ismael                                   Accountant
            Luis                                     Accountant
            John                                     Accountant
            Daniel                                   Accountant
            Nancy                                    Finance Manager
            Susan                                    Human Resources Representative
            Valli                                    Programmer
            Alexander                                Programmer
            David                                    Programmer
            Bruce                                    Programmer
            Diana                                    Programmer
            Michael                                  Marketing Manager
            Pat                                      Marketing Representative
            Hermann                                  Public Relations Representative
            Guy                                      Purchasing Clerk
            Karen                                    Purchasing Clerk
            Sigal                                    Purchasing Clerk
            Shelli                                   Purchasing Clerk
            Alexander                                Purchasing Clerk
            Den                                      Purchasing Manager
            Gerald                                   Sales Manager
            Alberto                                  Sales Manager
            Karen                                    Sales Manager
            John                                     Sales Manager
            Eleni                                    Sales Manager
            Ellen                                    Sales Representative
            Clara                                    Sales Representative
            Amit                                     Sales Representative
            Elizabeth                                Sales Representative
            David                                    Sales Representative
            Harrison                                 Sales Representative
            Nanette                                  Sales Representative
            Louise                                   Sales Representative
            Tayler                                   Sales Representative
            Kimberely                                Sales Representative
            Danielle                                 Sales Representative
            Peter                                    Sales Representative
            Alyssa                                   Sales Representative
            Charles                                  Sales Representative
            Janette                                  Sales Representative
            Sundita                                  Sales Representative
            David                                    Sales Representative
            Jack                                     Sales Representative
            Mattea                                   Sales Representative
            Allan                                    Sales Representative
            Christopher                              Sales Representative
            Lisa                                     Sales Representative
            Sarath                                   Sales Representative
            Lindsey                                  Sales Representative
            William                                  Sales Representative
            Patrick                                  Sales Representative
            Jonathon                                 Sales Representative
            Peter                                    Sales Representative
            Oliver                                   Sales Representative
            Sundar                                   Sales Representative
            Sarah                                    Shipping Clerk
            Alana                                    Shipping Clerk
            Anthony                                  Shipping Clerk
            Kelly                                    Shipping Clerk
            Julia                                    Shipping Clerk
            Jennifer                                 Shipping Clerk
            Britney                                  Shipping Clerk
            Kevin                                    Shipping Clerk
            Jean                                     Shipping Clerk
            Timothy                                  Shipping Clerk
            Girard                                   Shipping Clerk
            Douglas                                  Shipping Clerk
            Vance                                    Shipping Clerk
            Samuel                                   Shipping Clerk
            Donald                                   Shipping Clerk
            Randall                                  Shipping Clerk
            Nandita                                  Shipping Clerk
            Martha                                   Shipping Clerk
            Winston                                  Shipping Clerk
            Alexis                                   Shipping Clerk
            Mozhe                                    Stock Clerk
            Laura                                    Stock Clerk
            Peter                                    Stock Clerk
            Stephen                                  Stock Clerk
            John                                     Stock Clerk
            Michael                                  Stock Clerk
            Curtis                                   Stock Clerk
            Ki                                       Stock Clerk
            Renske                                   Stock Clerk
            James                                    Stock Clerk
            Jason                                    Stock Clerk
            Steven                                   Stock Clerk
            James                                    Stock Clerk
            Randall                                  Stock Clerk
            Irene                                    Stock Clerk
            Julia                                    Stock Clerk
            TJ                                       Stock Clerk
            Joshua                                   Stock Clerk
            Hazel                                    Stock Clerk
            Trenna                                   Stock Clerk
            Payam                                    Stock Manager
            Kevin                                    Stock Manager
            Adam                                     Stock Manager
            Shanta                                   Stock Manager
            Matthew                                  Stock Manager
            
      </details>

</div>


<div class=question id=Q2>
      <h4>2. 직원들의 이름(first_name), 입사일, 부서명(department_name) 검색하기</h4>
      <form action="채점을 해보자">
            <textarea cols="30" rows="5" placeholder="여기에 sql문을 입력후 제출을 눌러주세요 "onfocus="this.placeholder=''"
            onblur="this.placeholder='진짜 입력해보세요 채점해 줄게영'"></textarea>
            <br>
            <br>      
            <input type="onsubmit" value="제출" class="btn btn-success" id="button1" onclick="button1_click();"  />
        <script>
          function button1_click() {
          	alert("연결 안했쥬 속았쥬 모범 답안을 눌러서 비교 해보세여 ㅎㅎ ");
          }
        </script>
        </form>    
      <details>
            <summary>모범 답안</summary>
            <strong>SELECT</strong>first_name, hire_date,department_name
            <strong>FROM</strong>employees e <strong>LEFT OUTER JOIN</strong> departments d
            <strong>ON</strong>e.department_id = d.department_id;

            FIRST_NAME                               HIRE_DAT DEPARTMENT_NAME
            ---------------------------------------- -------- ------------------------------------------------------------
            Jennifer                                 03/09/17 Administration
            Pat                                      05/08/17 Marketing
            Michael                                  04/02/17 Marketing
            Karen                                    07/08/10 Purchasing
            Guy                                      06/11/15 Purchasing
            Sigal                                    05/07/24 Purchasing
            Shelli                                   05/12/24 Purchasing
            Alexander                                03/05/18 Purchasing
            Den                                      02/12/07 Purchasing
            Susan                                    02/06/07 Human Resources
            Douglas                                  08/01/13 Shipping
            Donald                                   07/06/21 Shipping
            Kevin                                    06/05/23 Shipping
            Alana                                    06/04/24 Shipping
            Vance                                    07/03/17 Shipping
            Samuel                                   06/07/01 Shipping
            Britney                                  05/03/03 Shipping
            Sarah                                    04/02/04 Shipping
            Randall                                  07/12/19 Shipping
            Timothy                                  06/07/11 Shipping
            Jennifer                                 05/08/13 Shipping
            Kelly                                    05/06/14 Shipping
            Anthony                                  07/02/07 Shipping
            Julia                                    06/06/24 Shipping
            Alexis                                   05/02/20 Shipping
            Nandita                                  04/01/27 Shipping
            Girard                                   08/02/03 Shipping
            Martha                                   07/06/21 Shipping
            Jean                                     06/02/23 Shipping
            Winston                                  06/01/24 Shipping
            Peter                                    06/07/09 Shipping
            Randall                                  06/03/15 Shipping
            Curtis                                   05/01/29 Shipping
            Trenna                                   03/10/17 Shipping
            Joshua                                   06/04/06 Shipping
            John                                     06/02/12 Shipping
            Stephen                                  05/10/26 Shipping
            Renske                                   03/07/14 Shipping
            Hazel                                    08/02/06 Shipping
            Ki                                       07/12/12 Shipping
            Michael                                  06/08/26 Shipping
            Jason                                    04/06/14 Shipping
            TJ                                       07/04/10 Shipping
            James                                    05/02/16 Shipping
            Mozhe                                    05/10/30 Shipping
            Laura                                    05/08/20 Shipping
            Steven                                   08/03/08 Shipping
            James                                    07/01/14 Shipping
            Irene                                    06/09/28 Shipping
            Julia                                    05/07/16 Shipping
            Kevin                                    07/11/16 Shipping
            Shanta                                   05/10/10 Shipping
            Payam                                    03/05/01 Shipping
            Adam                                     05/04/10 Shipping
            Matthew                                  04/07/18 Shipping
            Diana                                    07/02/07 IT
            Valli                                    06/02/05 IT
            David                                    05/06/25 IT
            Bruce                                    07/05/21 IT
            Alexander                                06/01/03 IT
            Hermann                                  02/06/07 Public Relations
            Charles                                  08/01/04 Sales
            Jack                                     06/04/23 Sales
            Jonathon                                 06/03/24 Sales
            Alyssa                                   05/03/19 Sales
            Ellen                                    04/05/11 Sales
            Sundita                                  08/04/21 Sales
            Elizabeth                                07/03/24 Sales
            William                                  07/02/23 Sales
            Tayler                                   06/01/24 Sales
            Harrison                                 06/03/23 Sales
            Lisa                                     05/03/11 Sales
            Amit                                     08/04/21 Sales
            Sundar                                   08/03/24 Sales
            David                                    08/02/23 Sales
            Mattea                                   08/01/24 Sales
            Danielle                                 07/03/19 Sales
            Clara                                    05/11/11 Sales
            Sarath                                   06/11/03 Sales
            Louise                                   05/12/15 Sales
            Lindsey                                  05/03/10 Sales
            Allan                                    04/08/01 Sales
            Patrick                                  04/03/04 Sales
            Janette                                  04/01/30 Sales
            Oliver                                   07/11/23 Sales
            Nanette                                  06/12/09 Sales
            Christopher                              06/03/30 Sales
            Peter                                    05/08/20 Sales
            David                                    05/03/24 Sales
            Peter                                    05/01/30 Sales
            Eleni                                    08/01/29 Sales
            Gerald                                   07/10/15 Sales
            Alberto                                  05/03/10 Sales
            Karen                                    05/01/05 Sales
            John                                     04/10/01 Sales
            Lex                                      01/01/13 Executive
            Neena                                    05/09/21 Executive
            Steven                                   03/06/17 Executive
            Luis                                     07/12/07 Finance
            Jose Manuel                              06/03/07 Finance
            Ismael                                   05/09/30 Finance
            John                                     05/09/28 Finance
            Daniel                                   02/08/16 Finance
            Nancy                                    02/08/17 Finance
            William                                  02/06/07 Accounting
            Shelley                                  02/06/07 Accounting
            Kimberely                                07/05/24                                    US

      </details>

</div>


<div class=question id=Q3>
      <h4>3.위치(LOCATIONS)와 부서(DEPARTMENTS) 테이블에서 지역이름(location_id)를
            이용하여 각 부서가 존재하는 나라의 코드(COUN)를 출력하시오. </h4>
      <h4>(단 나라의 코드는 중복되지 않게 하나만 나올 수 있도록 하며 부서의 위치가 없는 곳은 제외한다.)</h4>
      <form action="채점을 해보자">
            <textarea cols="30" rows="5" placeholder="여기에 sql문을 입력후 제출을 눌러주세요 "onfocus="this.placeholder=''"
            onblur="this.placeholder='진짜 입력해보세요 채점해 줄게영'"></textarea>
            <br>
            <br>      
            <input type="onsubmit" value="제출" class="btn btn-success" id="button1" onclick="button1_click();"  />
        <script>
          function button1_click() {
          	alert("연결 안했쥬 속았쥬 모범 답안을 눌러서 비교 해보세여 ㅎㅎ ");
          }
        </script>
        </form>    
      <details>
            <summary>모범 답안</summary>
            <strong>SELECTT DISTICT</strong>locations.country_id
            <strong>FROM</strong> departments, locations
            <strong>WHERE</strong> departments.location_id = locations.location_id(+);
            
            COUN
            ----
            US
            CA
            DE
            UK

      </details>

</div>

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap-theme.min.css">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>


<ul class="pager">
<li>
            <A href="https://github.com/magmom7"><IMG src="a.jpg" width="300" height="300" >
            <A href="https://github.com/Siho02"><IMG src="3.png" width="300" height="300" >
            <A href="https://github.com/Puzzle928"><IMG src="2.png" width="300" height="300" > </A>     
</li>
</ul>
<p style="font-size: 25px; color:blue">사진을 누르시면 깃허브 주소로 갈 수 있습니당!</p>
</body>
</html>
