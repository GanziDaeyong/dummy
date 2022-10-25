# Spectra

## 추가 설명

계정자산 감소(eth) - 보유한 이더가 설정된 기간 동안 설정된 기준량 이상 감소한 경우를 탐지하는 항목입니다. 이 항목이 탐지되는 경우에는 설정된 기간 동안의 모든 이더 전송 관련 트랜잭션을 보여줍니다.
Decrease in asset (ether) - Decrease in ether exceeds the base amount in the base time. If detected, it shows all the transactions related to the transfer of ether in the base time.

---

계정자산 감소(ERC-20) - 보유한 ERC-20이 설정기준시간동안 기준량 이상 감소한 경우입니다. 해당 사항이 탐지되는 경우, 기준시간 동안 해당 ERC-20과 관련된 트랜잭션을 보여줍니다.
Decrease in asset (ERC-20) - Decrease in ERC-20 exceeds the base amount in the base time. If detected, it shows all the transactions related to the given ERC-20 transfer in the base time.

---

계정자산 감소(ERC-721) - 보유한 ERC-721이 이전되는 경우입니다. 해당 사항이 탐지되는 경우, 이전된 ERC-721 토큰 및 트랜잭션을 보여줍니다.
Decrease in asset (ERC-721) - Transfer of ERC-721 happens. If detected, it shows the ERC-721 token that has been transferred and related transaction.

---

의심스러운 주소 발견 - 트랜잭션에서 의심스러운 주소가 발견되는 경우를 탐지하는 항목입니다. 이 항목이 탐지되는 경우, 발견된 의심스러운 주소와 트랜잭션을 보여줍니다.
Detection of suspicious address - Suspicious address is detected in the transactions related to the current account. If detected, it shows the detected one, which is suspicious, and related transaction.

---

임계치 이상의 트랜잭션 발생 - 트랜잭션이 기준시간 동안 기준량 이상 발생하는 경우입니다. 해당 사항이 탐지되는 경우, 기준시간 동안의 트랜잭션을 모두 보여줍니다.
Transaction count above threshold - The number of transactions exceeds the base amont in the base time. If detected, it shows all the transaction in the base time.

---

범위 밖 컨트랙트 상태 조회 결과값 - 컨트랙트의 상태를 조회하는 메서드에서, 사용자의 입력 값에 따른 출력 값이 지정한 범위를 벗어나는 경우입니다. 해당 사항이 탐지되는 경우, 범위를 벗어난 출력 값과 관련 트랜잭션을 보여줍니다.
Retrieved contract states out of range - For methods that retrieves contract states, the output value of the given input gets out of range. If detected, it shows output value that is out of range, and related transaction.

---

범위 밖 메서드 입력값 - 사용자 지정 범위를 벗어난 입력 파라미터로 메서드가 호출되는 경우입니다. 해당 사항이 탐지되는 경우, 범위를 벗어난 입력 값과 관련 트랜잭션을 보여줍니다.
Method input value out of range - Method is called with input parameter that is out of given range. If detected, it shows input value that is out of range, and related transaction.

---

의심스러운 주소 발견 - 컨트랙트와 연관된 트랜잭션에서 의심스러운 주소가 발견되는 경우입니다. 해당 사항이 탐지되는 경우, 발견된 의심스러운 주소와 트랜잭션을 보여줍니다.
Detection of suspicious address - Suspicious address is detected in the transactions related to the current contract. If detected, it shows the detected one, which is suspicious, and related transaction.

---

임계치 이상의 트랜잭션 발생 (메서드 기준) - 특정 메서드가 기준시간 동안 기준량 이상 호출된 경우입니다. 해당 사항이 탐지되는 경우, 기준시간 동안의 해당 메서드 호출 관련 트랜잭션을 보여줍니다.
Transaction count above threshold (method base) - The number of certain method called exceeds the base amount in the base time. If detected, it shows all the transactions related to the given method.

---

임계치 이상의 트랜잭션 발생 (호출자 기준) - 동일한 호출자가 기준시간 동안 기준량 이상 트랜잭션을 발생시킨 경우입니다. 해당 사항이 탐지되는 경우, 기준시간 동안 해당 호출자가 발생시킨
트랜잭션을 모두 보여줍니다.
Transaction count above threshold (caller base) - The number of transactions made by the same caller exceeds the base amount duriin the base time detected, it shows all the transactions related to the contract that are made by the caller.

---

동일 호출자의 동일 메서드 연속 호출 - 동일한 호출자가 기준시간동안 기준량 이상 동일 메서드를 호출한 경우입니다. 해당 사항이 탐지되는 경우, 기준시간 동안 해당 호출자가 연속으로 호출한 메서드 관련 트랜잭션을 모두 보여줍니다.
Consecutive method calls from the same caller - The number of consecutive calls to certain method exceeds the base amount during the base time. If detected, it shows all the consecutive method-related transactions that are made by the caller during the base time.

---

재진입 공격 징후 감지 - 재진입 공격이 의심되는 경우입니다. 해당 사항이 탐지되는 경우, 트랜잭션에서 발생한 컨트랙트의 재진입 횟수 및 메시지 콜을 요약해서 보여줍니다.
Detection of reentrancy attack - Reentrancy attack is presumed. If detected, it shows the number of reentrances took place from the transaction, and summarized message calls.

---

사용자 지정 이벤트 - 사용자가 지정한 이벤트가 발생하는 경우입니다. 해당 사항이 탐지되는 경우, 발생한 이벤트와 이벤트 내 파라미터를 보여줍니다.
User custom event - User selected event is emitted. If detected, it shows the emitted event and its parameters.
