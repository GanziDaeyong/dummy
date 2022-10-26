# Spectra

## 추가 설명

계정자산 감소(eth) - 보유한 이더가 설정된 기간 동안 설정된 기준량 이상 감소한 경우를 탐지하는 항목입니다. 이 항목이 탐지되는 경우에는 설정된 기간 동안의 모든 이더 전송 관련 트랜잭션을 보여줍니다.
Decrease in asset (ether)

This item detects when the amount of Ether you have has decreased by more than the set threshold during the set period. If this item is detected, it will show all Ether transfer related transactions for the set period

---

계정자산 감소(ERC-20) - 보유한 ERC-20이 설정된 기간 동안 설정된 기준량 이상 감소한 경우를 탐지하는 항목입니다. 이 항목이 탐지되는 경우에는 설정된 기간 동안의 해당 ERC-20과 관련된 트랜잭션을 보여줍니다.

Decrease in asset (ERC-20) - This item detects when the ERC-20 you have has decreased by more than the set reference amount during the set period. If this item is detected, it shows the transactions related to that ERC-20, which decreased, for the set period.

---

계정자산 감소(ERC-721) - 보유한 ERC-721이 이전되는 경우를 탐지하는 항목입니다. 이 항목이 탐지되는 경우에는 이전된 ERC-721 토큰 및 관련 트랜잭션을 보여줍니다.

Decrease in asset (ERC-721) - This item detects when the ERC-721 you have has transferred. If this item is detected, it shows the transferred ERC-721 tokens and related transactions.

---

의심스러운 주소 발견 - 트랜잭션에서 의심스러운 주소가 발견되는 경우를 탐지하는 항목입니다. 이 항목이 탐지되는 경우, 발견된 의심스러운 주소와 트랜잭션을 보여줍니다.

Detection of suspicious address - This item detects when a suspicious address is found in a transaction. If this item is detected, it shows the suspicious addresses and related transactions.

---

임계치 이상의 트랜잭션 발생 - 트랜잭션이 설정된 기간 동안 설정된 기준량 이상 발생하는 경우를 탐지하는 항목입니다. 이 항목이 탐지되는 경우, 설정된 기간 동안의 트랜잭션을 모두 보여줍니다.

Transaction count above threshold - This item detects when a transaction occurs more than the set threshold for the set period. If this item is detected, it shows all transactions for the set period.

---

범위 밖 컨트랙트 상태 조회 결과값 - 컨트랙트의 상태를 조회하는 메서드에서, 사용자의 입력 값에 따른 출력 값이 지정한 범위를 벗어나는 경우를 탐지하는 항목입니다. 이 항목이 탐지되는 경우, 범위를 벗어난 출력 값과 관련 트랜잭션을 보여줍니다.

Retrieved contract states out of range - This item detects when the output value according to the user's input value is out of the specified range in contract state 'view' methods. If this item is detected, it shows the out-of-range output value and related transaction.

---

범위 밖 메서드 입력값 - 사용자 지정 범위를 벗어난 입력 파라미터로 메서드가 호출되는 경우를 탐지하는 항목입니다. 이 항목이 탐지되는 경우, 범위를 벗어난 입력 값과 관련 트랜잭션을 보여줍니다.

Method input value out of range - This item detects when a method is called with an input parameter that is outside the user-specified range. If this item is detected, it shows the out-of-range input value and related transaction.

---

의심스러운 주소 발견 - 트랜잭션에서 의심스러운 주소가 발견되는 경우를 탐지하는 항목입니다. 이 항목이 탐지되는 경우, 발견된 의심스러운 주소와 트랜잭션을 보여줍니다.

Detection of suspicious address - This item detects when a suspicious address is found in a transaction. If this item is detected, it shows the suspicious addresses and related transactions.

---

임계치 이상의 트랜잭션 발생 (메서드 기준) - 특정 메서드가 설정된 기간 동안 설정된 기준량 이상 호출된 경우를 탐지하는 항목입니다. 이 항목이 탐지되는 경우, 설정된 기간 동안의 해당 메서드 호출 관련 트랜잭션을 보여줍니다.

Transaction count above threshold (method base) - This item detects when a specific method is called more than the set threshold during the set period. If this item is detected, it shows the transaction related to that method call during the set period.

---

임계치 이상의 트랜잭션 발생 (호출자 기준) - 동일한 호출자가 설정된 기간 동안 설정된 기준량 이상 트랜잭션을 발생시킨 경우를 탐지하는 항목입니다. 이 항목이 탐지되는 경우, 설정된 기간 동안의 해당 호출자가 발생시킨 트랜잭션을 모두 보여줍니다.

Transaction count above threshold (caller base) - This item detects when the same caller has made transactions more than the set threshold during the set period. If this item is detected, it shows all transactions made by that caller during the set period.

---

동일 호출자의 동일 메서드 연속 호출 - 동일한 호출자가 설정된 기간 동안 설정된 기준량 이상 동일 메서드를 연속하여 호출한 경우를 탐지하는 항목입니다. 이 항목이 탐지되는 경우, 설정된 기간 동안 해당 호출자가 연속으로 호출한 메서드 관련 트랜잭션을 모두 보여줍니다.

Consecutive method calls from the same caller - This item detects when the same caller consecutively calls the same method over the set threshold during the set period. If this item is detected, it will show all method related transactions consecutively called by that caller during the set period.

---

재진입 공격 징후 감지 - 재진입 공격이 의심되는 경우를 탐지하는 항목입니다. 이 항목이 탐지되는 경우, 트랜잭션에서 발생한 컨트랙트의 재진입 횟수 및 메시지 콜을 보여줍니다.

Detection of reentrancy attack - This item detects when a re-entrancy attack is presumed. If this item is detected, it shows the number of reentrances and message calls of the contract executed in the transaction.

---

사용자 지정 이벤트 - 사용자가 지정한 이벤트가 발생하는 경우를 탐지하는 항목입니다. 이 항목이 탐지되는 경우, 발생한 이벤트와 이벤트 내 파라미터를 보여줍니다.

User custom event - This item detects when a user-specified event occurs. When this item is detected, it shows the event that occurred and the parameters within the event.
