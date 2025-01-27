# Project - ALD


## ABSTRACT

 이 프로젝트에서는 한국의 온-오프라인 서점 알라딘에서의 최저가 장바구니 알고리즘을 제안한다. 

알라딘은 새 책을 판매할 뿐만 아니라 중고책들도 훼손의 정도에 따라 가격을 차등하여 판매하고 있다.
이렇게 소비자에게 넓은 선택의 폭을 제공하는 것은 알라딘 만의 큰 장점이나, 선택할 수 있는 옵션이 여러가지인 만큼 옵션 중 최저가인 옵션을 알아내는 일은 수고스러운 일이 된다. 

 예를 들어, {'책_ㄱ':15,000 #직배송, '책_ㄱ':13,000 #뉴욕점 , '책_ㄱ': 14,000 #파리점, '책_ㄴ':6,000 #파리점, '책_ㄴ':5,000 #서울점}의 딕셔너리가 있다고 가정해보자.
소비자가 '책_ㄱ','책_ㄴ'을 구매하려 할 때 선택할 수 있는 옵션은 총 3*2가지 이다. 
이 옵션 중 단순히 책의 가격만 생각하여 최저가를 구한다면 각 책마다의 최저가인 뉴욕점에서 '책_ㄱ', 서울점에서 '책_ㄴ'을 구매하여 18,000원이 지출비용이겠으나 매장마다 총 비용이 20,000원이 넘지 않는다면 각 매장마다 2,000원의 배송료가 붙으므로 총 비용은 22,000원이 된다.
하지만 파리점 한 곳에서 '책_ㄱ','책_ㄴ'을 구매한다면 배송비 0원에 총 비용 20,000원으로 책 각각의 최저가를 선택하여 구매하는 것 보다 2,000원 저렴하고, 높아진 각각의 책 가격만큼 책 컨디션도 보다 좋을 것으로 기대할 수 있다. 

 가격만을 고려하는 본인같은 소비자를 위하여 구매할 책의 리스트를 인풋한다면 알라딘에서 구매할 수 있는 최저가 옵션을 출력하도록 프로그램을 구성하였다.
 

## robots.txt

[CHECK](https://www.aladin.co.kr/robots.txt) Aladin's robots.txt

### User-agent: *
* Disallow: /mobile/
* Disallow: /js/
* Disallow: /aaintraweb/
* Disallow: /account/
* Disallow: /api/
* Disallow: /errormng/
* Disallow: /intranet/
* Disallow: /jiny/
* Disallow: /login/
* Disallow: /mail/
* Disallow: /mng/
* Disallow: /order/
* Disallow: /scm/
* Disallow: /search/
* Disallow: /ttb/
* Disallow: /webservice/
* Disallow: /wservice/
* Disallow: /*?EventId=201357
* Disallow: /*?EventId=199338
* Disallow: /*?EventId=198631
* Disallow: /shop/book/wletslookViewerNew.aspx
* Disallow: /*.swf$
* Allow: /
  
### User-Agent: QuerySeekerSpider ( http://queryseeker.com/bot.html )
* Disallow: /

### User-agent: AhrefsBot
* Disallow: /
  
### User-agent: MJ12bot
* Disallow: /
  
### User-agent: SemrushBot
* Disallow: /

### User-agent: Baiduspider
* Disallow: /
  
### User-agent: Ezooms
* Disallow: /
  
### User-agent: YandexBot
* Disallow: /
  
### User-agent: ltx71
* Disallow: /
  
### User-agent: zgrab/0.x
* Disallow: /

Sitemap: https://www.aladin.co.kr/ucl_editor/util/sitemap/sitemap.xml


## Role
 ///////    //      //     //////        ///       /////////
//          //      //   //      //     // //    //
////////    //      //   //      //    //   //   //////////
//    //    //      //   //      //   /////////          //
//    //     //    //    //      //  //      //         // 
///////        ////        //////    //      //  ////////

aladin.robots.txt에서 허락한 /shop/UsedShop 을 사용하도록 한다.
