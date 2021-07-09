## CATCH FABRIC 프로젝트 Front-end/Back-end 소개

- 명품 직구 사이트 [캐치패션](https://www.catchfashion.com/) 클론 프로젝트

- 짧은 프로젝트 기간동안 개발에 집중해야 하므로 디자인/기획 부분만 클론하였으며, 저희의 아이디어가 담기도록 원단 판매 사이트로 변경하였습니다.

- 개발은 초기 세팅부터 전부 직접 구현했으며, 아래 데모 영상에서 보이는 부분은 모두 백앤드와 연결하여 실제 사용할 수 있는 서비스 수준으로 개발한 것입니다.

## 개발 인원 및 기간
- 개발기간 : 2021/6/7 ~ 2021/6/18
- 개발자 : 유병건 외 2명

## 내가 작성한 기능
- orders app
  - OrdersPayment 클래스
  - OrdersCart 클래스

- products app
  - ProductListInfo 클래스 

## 적용 기술
 - Python, Django web framework, Bcrypt, JWT, MySQL, RESTful API
 - AWS(EC2)를 활용한 배포

## 사이트 기능
#### 장바구니(orders)
 - 장바구니 조회
 - 장바구니 삭제
 - 장바구니 추가
 
#### 상품 리스트(products)
 - Q객체를 활용한 필터기능 구현
 - OrderBy와 슬라이싱을 활용한 최신 게시물 필터 구현
 
## Reference
- 이 프로젝트는 [캐치패션](https://www.catchfashion.com/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.
