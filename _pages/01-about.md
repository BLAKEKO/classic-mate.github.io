---
layout: archive
permalink: /about/
title: "120% 활용하기"
author_profile: true
---

**랜덤 추천받기**

스테이지에 상관없이 새로운 음악이 듣고 싶을 때는 “Ok Google, 클래식 메이트한테 랜덤추천받기”라고 말해보세요. 오늘의 음악을 듣다가도 "Ok Google, 랜덤곡 들려줘"라고 하시면 새로운 음악을 소개해드린답니다!

---

**루틴 설정하기**

구글홈 루틴 설정을 이용하시면 정해진 시간에 클래식 메이트가 찾아와요!

<iframe width="560" height="315" src="https://www.youtube.com/embed/-g97MQl6RXw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

1. 루틴 클릭
2. 루틴 관리 클릭
3. 루틴 추가 클릭
4. 원하는 명령어 및 날짜 설정, 적용할 스피커 선택
5. 작업 추가 클릭하고 "클래식 메이트한테 말하기" 입력
6. 저장!

---

**클래식 메이트의 공연 추천**

음악 감상이 끝나고 클래식 메이트가 공연 추천을 해주기도 한답니다. 깜짝 선물처럼 찾아오는 공연 추천을 놓치지 마세요!
아래 올해의 추천 공연도 확인해보세요!

**10월**

* 2019년 10월 15일<br>
[제 16회 차이콥스키 콩쿠르 우승자 갈라콘서트](http://www.clubbalcony.com/home/library/leaflet_list.aspx?Mode=r&mid=8&pid=&bid=38926&Se=TITLE&Sestr=&page=1)

* 2019년 10월 25일<br>
[미샤 마이스키 ＆ 무직콜레기움 빈터투어](http://www.clubbalcony.com/Home/classic/ticket_detail.aspx?Id=27891&perfmode=inter)

**11월**

* 2019년 11월 13-17일<br>
[장한나 & 트론헤임 심포니 오케스트라 (협연: 임동혁)](http://www.clubbalcony.com/home/library/leaflet_list.aspx?Mode=r&mid=8&pid=&bid=38904&Se=TITLE&Sestr=&page=1)

* 2019년 11월 29일<br>
[안네-소피 무터 리사이틀](http://www.clubbalcony.com/Home/classic/ticket_detail.aspx?id=27968&perfmode=inter&y=2019&m=11&s=0)

**12월**

* 2019년 12월 01일<br>
[지용 The Age of Maturity](http://www.clubbalcony.com/home/library/leaflet_list.aspx?Mode=r&mid=8&pid=&bid=38901&Se=TITLE&Sestr=&page=1)

* 2019년 12월 08일<br>
[백혜선 세계 무대 데뷔 30주년 기념 리사이틀](http://www.clubbalcony.com/Home/classic/ticket_detail.aspx?id=28683&perfmode=inter&y=2019&m=12&s=0)

* 2019년 12월 22일<br>
[크리스마스 콘서트 [유키 구라모토와 친구들]](http://www.clubbalcony.com/Home/classic/ticket_detail.aspx?id=28882&perfmode=inter&y=2019&m=12&s=0)

* 2019년 12월 25일<br>
[금난새의 크리스마스 선물](http://www.clubbalcony.com/Home/classic/ticket_detail.aspx?id=28893&perfmode=inter&y=2019&m=12&s=0)

* 2019년 12월 25일<br>
[리처드 용재 오닐 [선물]](http://www.clubbalcony.com/home/library/leaflet_list.aspx?Mode=r&mid=8&pid=&bid=38924&Se=TITLE&Sestr=&page=1)

* 2019년 12월 29일<br>
[사라 장 바이올린 리사이틀](http://www.clubbalcony.com/home/library/leaflet_list.aspx?Mode=r&mid=8&pid=&bid=38897&Se=TITLE&Sestr=&page=1)

{% assign postsByYear = site.posts | group_by_exp:"post", "post.date | date: '%Y'"  %}
{% for year in postsByYear %}
  <h2 id="{{ year.name | slugify }}" class="archive__subtitle">{{ year.name }}</h2>
  {% for post in year.items %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}