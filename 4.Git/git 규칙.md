## 나만의 Git commit 규칙
아무리 혼자 프로젝트를 하더라도 버전 관리는 정말 중요하다.  
성능을 비교해본다던지, 실행 시간을 비교해본다던지 여러가지 이유에 의해 이전 코드가 필요한 경우도 있는데, 제대로 관리하지 않으면 굉장히 곤란해진다 ...  
유의미한 수정이 있을 때마다 git에 commit하고 있는데, 내가 정한 나만의 commit 규칙을 정리해보려고 한다!

#### 명확하게 잘 사용하고 있다고 생각되는 commit 들
* `refactor` : 코드 리팩토링. 로직은 수정하지 않는다.
* `feature` : 새로운 기능(function, class, method 등)을 추가한다.
* `improve` : 로직을 개선한다. 
* `fix` : 에러가 발생하는 경우에 코드를 개선한다. (오타 수정부터 예외 처리를 못한 경우까지)
* `rename` : 파일 이름을 변경한다.

### 고민해볼 사항
* `update`, `modified` : refacor와 섞어쓰고 있다. 명확한 분리가 필요하다.