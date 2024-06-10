스타벅스 크로링 및 시각화 차트.
BeautifulSoup와 Selenium Webdriver 사용.
HTML태그는 비동기방식 xpath를 사용하여 가져왔고, 매장이름, 매장좌표는 가져왔으나 하위태그가 2번들어가는 p태그는 못가져왔기 때문에, RestfulAPI인 KakaoAPI를 이용해서 매장좌표 -> 매장주소 리스트를 뽑아서 사용함. 사실 객체.select('태그.가져오려는 속성이름') 를 이용하면 되었으나, find_elements메서드만 이용하는 줄 알고 실수. 따라서, 매장주소를 제외한 크롤링.
서울의 스타벅스 매장만을 활용. 서울시 스타벅스와 구별로 뽑아서 구별 스타벅스 현황 을 csv로 제작
그외에 pieChart와 varChart이용.