<article class="book-card">
  <figure class="book-card__cover">
    <img src="{{ '/images/apache-iceberg-ko-cover.jpg' | relative_url }}" alt="아파치 아이스버그 완벽 가이드 표지" width="500" height="652">
  </figure>
  <div class="book-card__body">
    <p class="book-card__eyebrow">예약 판매 중</p>
    <p class="book-card__title">아파치 아이스버그 완벽 가이드</p>
    <p class="book-card__subtitle">차세대 데이터 레이크하우스 구축과 성능 최적화</p>
    <p class="book-card__desc">아파치 아이스버그 테이블의 구조와 읽기·쓰기 내부 동작, 성능 최적화, Spark·Flink·Dremio 연동을 다루는 오픈 데이터 레이크하우스 실전 안내서입니다.</p>
    <nav class="book-card__actions" aria-label="도서 자료">
      <a class="book-card__action book-card__action--primary" href="{{ '/errata/' | relative_url }}">정오표</a>
      <a class="book-card__action" href="https://github.com/developer-advocacy-dremio/definitive-guide-to-apache-iceberg">원서 예제</a>
    </nav>
    <dl class="book-card__meta">
      <dt>영문 제목</dt>
      <dd><a href="https://www.oreilly.com/library/view/apache-iceberg-the/9781098148614/">Apache Iceberg: The Definitive Guide</a></dd>
      <dt>지은이</dt>
      <dd>토메르 시란, 제이슨 휴즈, 알렉스 메르세드</dd>
      <dt>옮긴이</dt>
      <dd>이동진</dd>
      <dt>출판사</dt>
      <dd>제이펍</dd>
      <dt>ISBN</dt>
      <dd>9791124205778</dd>
    </dl>
    <nav class="book-card__actions" aria-label="구입처">
      <a class="book-card__action" href="https://product.kyobobook.co.kr/detail/S000221509839">교보문고</a>
      <a class="book-card__action" href="https://www.11st.co.kr/products/9649506943">11번가</a>
      <a class="book-card__action" href="https://www.aladin.co.kr/shop/wproduct.aspx?ISBN=9791124205778">알라딘</a>
      <a class="book-card__action" href="https://www.yes24.com/product/goods/197214448">YES24</a>
    </nav>
  </div>
</article>

{% include update-section.html section_id="topic-updates" title="관련 주제 업데이트" updates=site.posts empty_text="관련 주제 업데이트를 준비하고 있습니다." archive_url="/topic-updates/" %}

{% assign other_updates_collection = site.collections | where: "label", "related_posts" | first %}
{% include update-section.html section_id="other-updates" title="기타 업데이트" updates=other_updates_collection.docs empty_text="기타 업데이트를 준비하고 있습니다." archive_url="/other-updates/" %}

<aside class="homepage-section" aria-labelledby="related-title">
  <h2 id="related-title" class="homepage-section__title">연관 서적</h2>
  <ul class="related-books">
    <li>
      <a class="related-book" href="https://dongjinleekr.github.io/kafka-the-definitive-guide-v2/">
        <img class="related-book__cover" src="{{ '/images/kafka-2nd-ko-cover.jpg' | relative_url }}" alt="" width="500" height="652">
        <span class="related-book__text">
          <span class="related-book__title">카프카 핵심 가이드 (개정증보판)</span>
        </span>
      </a>
    </li>
  </ul>
</aside>
