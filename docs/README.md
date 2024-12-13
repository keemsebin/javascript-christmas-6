## 구현할 기능 목록

### **input**

- [ ]  예상 방문 날짜
- [ ]  주문하실 메뉴와 개수

### **output**

- [ ]  주문 메뉴, 할인 전 총주문 금액, 증정 메뉴, 혜택 내역, 총혜택 금액, 할인 후 예상 결제 금액, 12월 이벤트 배지 내용

### **process**

- [ ]  크리스마스 디데이 할인 기간 (12.1~12.25)
    - [ ]  1000원부터 시작, 날마다 할인 금액 100원 증가
- [ ]  평일 할인, 디저트 메뉴 1개당 2023원
- [ ]  주말 할인, 메인 메뉴 1개당 2023원
- [ ]  특별 할인, 별이 존재하는 날은 총주문 금액에서 1000원 할인
- [ ]  증정 이벤트, 할인 전 총 주문 금액이 12만원 이상일 때, 샴페인 1개 증정
- [ ]  디데이 할인을 제외한 모든 이벤트는 12.1~12.31까지 적용
- [ ]  12월 이벤트 배지 부여
    - [ ]  총 혜택 금액이 5천원 이상 - 별, 1만원 이상 - 트리, 2만원 이상 - 산타

### **validation**

- [ ]  10000원 이상부터 이벤트 적용
- [ ]  음료만 주문 시, 주문 불가
- [ ]  메뉴는 한번에 최대 20개 주문 가능
- [ ]  방문 날짜는 1이상 31이하의 숫자만 가능
- [ ]  메뉴의 개수는 1이상의 숫자만 가능
- [ ]  메뉴 중복 불가

### **constants 목록**

- [ ]  `안녕하세요! 우테코 식당 12월 이벤트 플래너입니다.`
- [ ]  `12월 중 식당 예상 방문 날짜는 언제인가요? (숫자만 입력해 주세요!)`
- [ ]  `주문하실 메뉴를 메뉴와 개수를 알려 주세요. (e.g. 해산물파스타-2,레드와인-1,초코케이크-1)`
- [ ]  `12월 3일에 우테코 식당에서 받을 이벤트 혜택 미리 보기!`
- [ ]  `<주문 메뉴>`
- [ ]  `<할인 전 총주문 금액>`
- [ ]  `<증정 메뉴>`
- [ ]  `<혜택 내역>`
- [ ]  `<총혜택 금액>`
- [ ]  `<할인 후 예상 결제 금액>`
- [ ]  `<12월 이벤트 배지>`

### error constants 목록

- [ ]  `[ERROR] 유효하지 않은 날짜입니다. 다시 입력해 주세요."라는 에러 메시지를 보여 주세요.`
- [ ]  `[ERROR] 유효하지 않은 주문입니다. 다시 입력해 주세요.`