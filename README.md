# PriceTracker

<aside>
쿠팡, SSG 등 이커머스 내에서 판매하는 식료품에 대한 평균가를 계산하고 이커머스끼리 가격 추이 비교
</aside>

### 개요

현재 물가가 급등하고 있는 현대 사회 속에서 손쉽게 이커머스 사이트 가격 비교를 할 수 있도록 한다. 이커머스에서 판매하는 항목별 식료품의 가격이 평균적으로 어느 사이트가 저렴한 지, 가격 추이가 어떻게 변화하였는지 알아보기 위하여 시작하게 되었다. 가격은 계속 변화하기 때문에 이를 준실시간으로 데이터를 수집해 시각화하기로 결정했다.

### 쿠팡 크롤링 실행

```python -m crawling.coupang.crawling```