# 목적

- 현재 레파지토리의 목적은 DID의 개념을 이해하고 싶거나, 솔루션을 개발하고자 하는 일반인과 개발자분들의 이해를 돕고 하나 이상의 시나리오를 구현할 수 있도록 돕고자 하는데 있습니다.
- 이를 위해 상세한 개념적 설명과 예시 코드 및 테스트 환경을 제공하고자 합니다.

# 목표

아래와 같은 모듈들을 만들어 여러 시나리오에 적용하고, 테스트 합니다.

- SSI(Self-sovereign Identity) Wallet: DID의 Holder 역할을 수행하며, Issuer와 연결하여 VC를 발급 받고, Verifier에게 VP를 제출하여 서비스를 요청합니다.
- did-core: DID를 구현하기 위한 핵심적인 기능을 이해하고 구현할 것입니다.
- VDR(Verifiable Data Registry): DID와 DID Document 등의 데이터를 저장하고, VC의 유효기간, 만료 등에 대한 정보를 저장하고 갱신할 수 있도록 구현할 것입니다.
- Issuer: VC를 발급하고 관리합니다.
- Verifier: VP를 검증하고 서비스를 제공합니다.

# 참여 및 기여

- 참여 및 기여를 원하실 경우 아래의 메일로 연락을 주시거나
  - SSI-KOREA(ssikorea.community@gmail.com)
- 이슈 및 토론에 참여해 주시면 됩니다.

# 라이센스

- 본 프로젝트는 [GPL-3.0 라이센스](https://github.com/ssi-korea/did-core/blob/main/LICENSE)를 가지고 있습니다.
