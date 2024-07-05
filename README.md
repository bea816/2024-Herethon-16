# 2024-Herethon-16
2024 여기톤 : HERETHON 16조

<hr/>

- **서비스 소개**

블라블라

- **기술 스택**

  <span>프론트엔드: </span> <img src="https://img.shields.io/badge/html-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">

  <span>백엔드: </span><img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> <img src="https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=Django&logoColor=white">

  <span>기획·디자인: </span> <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">

- **팀원 소개**
  <table border="" cellspacing="0" cellpadding="0" width="100%">
  <tr width="100%">
  <td  align="center">정다은</a></td>
  <td  align="center">유동은</a></td>
  <td  align="center">박유채</a></td>
  <td  align="center">박지혜</a></td>
  <td  align="center">김나영</a></td>
  <td  align="center">정세윤</a></td>
  </tr>
  <tr width="100%">
  <td  align="center"><a href="https://imgbb.com/"><img src="https://i.ibb.co/sWXnzcJ/befbedf87e51f5b02aac8b882ada60fd-sticker.png" border="0" width="90px"></a></td>
  <td  align="center"><a href="https://imgbb.com/"><img src="https://i.ibb.co/2WR24Hr/image.png" border="0" width="90px"></a></td>
  <td  align="center"><a href="https://imgbb.com/"><img src="https://i.ibb.co/sqLZXG8/image.png" border="0" width="90px"></a></td>
    <td  align="center"><a href="https://imgbb.com/"><img src="https://i.ibb.co/V3pySTC/5319-CD6-B-9-BA7-4841-A518-5-CFC40800289.png" border="0" width="90px"></a></td>
  <td  align="center"><a href="https://imgbb.com/"><img src="https://i.ibb.co/dKy52WJ/image.png" border="0" width="90px"></a></td>
  <td  align="center"><a href="https://imgbb.com/"><img src="https://i.ibb.co/2KDG82L/d006044e5996d0023cd2e18425aa4677-sticker.png"  border="0" width="90px"></a></td>
  </tr>
  <tr width="100%">
  <td  align="center">기획·디자인</td>
  <td  align="center">프론트엔드</td>
  <td  align="center">프론트엔드</td>
  <td  align="center">프론트엔드</td>
  <td  align="center">백엔드</td>
  <td  align="center">백엔드</td>
  </tr>
      <tr width="100%">
          <td  align="center"><p>성신여자대학교</p><p>전체 서비스 기획 및 디벨롭</p><p>전체 페이지 디자인</p></td>
           <td  align="center"><p>숙명여자대학교</p><p>..</p><p>..</p></td>
            <td  align="center"><p>성신여자대학교</p><p>..</p><p>..</p></td>
            <td  align="center"><p>서울여자대학교</p><p>..</p><p>..</p></td>
            <td  align="center"><p>덕성여자대학교</p><p>유저 기능</p><p>마이페이지 기능</p></td>
            <td  align="center"><p>동덕여자대학교</p><p>메인 페이지 기능</p><p>포트폴리오 기능</p></td>
     </tr>
  </table>

- **폴더 구조**

  ```
  📂 all_project
  +---accounts
  |   +---__pycache__
  |   +---migrations
  |   |   \---__pycache__
  |   +---static
  |   |   +---css
  |   |   +---img
  |   |   \---js
  |   +---templates
  |   |   +---accounts
  |   |   |   +---create_my_video.html
  |   |   |   +---create_myportfolio.html
  |   |   |   +---index.html
  |   |   |   +---login.html
  |   |   |   +---mylike.html
  |   |   |   +---mypage.html
  |   |   |   +---myviewhistory.html
  |   |   |   +---signup.html
  |   |   |   +---update_my_video.html
  |   |   |   \---update_myportfolio.html
  |   +---__init__.py
  |   +---admin.py
  |   +---apps.py
  |   +---forms.py
  |   +---models.py
  |   +---tests.py
  |   +---urls.py
  |   \---views.py
  +---danjang_prj
  |   +---__pycache__
  |   +---__init__.py
  |   +---asgi.py
  |   +---settings.py
  |   +---urls.py
  |   \---wsgis.py
  +---media
  |   \---media
  |   |   \---default_mypage_image.jpg
  +---portfolios
  |   +---__pycache__
  |   +---migrations
  |   |   \---__pycache__
  |   +---static
  |   |   +---css
  |   |   +---img
  |   |   \---js
  |   +---templates
  |   |   +---portfolios
  |   |   |   +---portfolio_detail.html
  |   |   |   \---portfolio_list.html
  |   +---__init__.py
  |   +---admin.py
  |   +---apps.py
  |   +---models.py
  |   +---tests.py
  |   +---urls.py
  |   \---views.py
  +---videos
  |   +---__pycache__
  |   +---migrations
  |   |   \---__pycache__
  |   +---static
  |   |   +---css
  |   |   +---img
  |   |   \---js
  |   +---templates
  |   |   +---videos
  |   |   |   +---search.html
  |   |   |   +---video_detail.html
  |   |   |   \---video_list.html
  |   +---__init__.py
  |   +---admin.py
  |   +---apps.py
  |   +---models.py
  |   +---tests.py
  |   +---urls.py
  |   \---views.py
  ```

- **개발환경에서의 실행 방법**
  ```
  $ python -m venv newvenv    #가상환경 생성
  $ source newvenv/Scripts/activate
  $ pip install django
  $ python -m pip install Pillow # 이미지 처리를 위한 라이브러리 설치
  $ cd danjang_prj
  $ python manage.py runserver
  ```
  <hr/>
