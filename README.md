# OSS-Governance
opensource governance

# Contribution
## Rule
### CLA서명

### 저작권
### 지식재산

## 절차

### Issue 생성 및 관리
+ Issue유형
- 프로그램 버그
- 프로그램 개선사항 및 아이디어
- 일반 문의
- 
+ 생성 및 관리
- Issue를 생성하고 관리할 수 있는 Tools(Git-Issue, jira 등)를 사전에 정의하라
- 식별된 Issue에 대해 중복으로 등록이 되는 것을 막아라
- Issue Template을 작성하여 일관성있는 Issue Format을 유지하라
- Issue Label을 생성하여 Issue를 효율적으로 

### Pull Request
Pull Request는 local에서 작업이 완료된 소스를 remote repository에 push를 요청하는 절차이며 아래 사항에 유의해야 한다
+ 유의사항
- 기존에 생성된 Issue에 관련된 내용만 Pull Request를 요청하며, 요청 시에는 해당 Issue Number를 Mapping 해주어야 한다
- Pull Request 요청 전 해당 프로젝트의 Pull Request 요건(CLA서명, Commit Rule 등)을 확인한다

+ 절차
- 생성된 Issue를 확인하고 local에 Fork된 소스를 수정한다
- Pull Request 요건을 확인하여 적절히 요청한다
- Pull Request Trigger에 의해 Build, Code Coverage, Test 등의 프로세스가 자동으로 수행된다
- 모든 내용이 통과한 후 관리자는 검토 후에 Merge 여부를 검토한다

### Documentation

### Feedback
관리자는 Contributor에게 프로그래밍 내역에 대해 상세한 설명을 요구할 수 있으며 그에 따라 개발된 소스의 Merge여부가 결정될 수 있다
이는 Contributor의 개발 능력의 관점보다는 프로젝트의 Rule, 목적에 기반한다
+ Pull Request에 대한 무응답
- 일정기간동안 관리자로부터 응답이 오지 않을 경우 멘션(@)기능을 통해 관리자에게 notify를 해라
- 개인적으로는 연락을 하지 않는다
+ 수정 요청 시
- 수정요청을 받을 경우 즉시 대응해야 한다. PR(Pull Request)가 열려둔 상태로 남겨저 있으면 안되기 때문이다. 만약 수정이 불가할 경우 관리자에게 해당 내용을 notify하여
  해당 PR를 Close하거나 다른 사람이 해결할 수 있도록 해야 한다
+ 거절 될 경우
- 거절된 내용이 이해가 가지 않을 경우 설명을 요청하라. 하지만 이에대해 논쟁을 하거나 강압적으로 승인을 요청하는 것을 절대 금기이다. 만약 의견 조율이 되지 않는다면
  자신의 repository에 fork를 하여 개별프로젝트로 직접 진행하면 된다
