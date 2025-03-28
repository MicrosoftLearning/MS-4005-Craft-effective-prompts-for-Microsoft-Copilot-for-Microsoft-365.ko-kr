# Word에서 Microsoft 365 Copilot을 사용하여 표지, 마케팅 계획 및 개요 초안 작성

Word에서 Microsoft 365 Copilot을 사용하려면 리본의 **홈** 탭에서 Copilot 아이콘을 선택하여 **Copilot** 창을 열거나 문서 내에서 바로 쓰기를 시작합니다.

![Word 리본 메뉴의 Copilot 아이콘 스크린샷.](../media/create_copilot-ribbon-word.png)

문서 본문에서 바로 초안 작성을 시작하려면 다음을 수행합니다.

1. Microsoft Word를 열고 새 빈 문서를 시작합니다.

1. 프롬프트를 **Copilot으로 초안 작성** 상자에 입력하거나 붙여넣습니다.

1. **생성**을 선택하면 Copilot에서 새 콘텐츠를 초안으로 작성합니다.

Copilot이 콘텐츠를 생성한 후, **유지**를 선택하여 콘텐츠를 유지하거나 **다시 생성**을 선택하여 응답을 다시 생성하거나 **취소**를 선택하여 콘텐츠를 삭제하거나, "_더 간결하게 만들어 줘_"와 같은 세부 정보를 작성 상자에 입력하여 초안을 미세 조정할 수도 있습니다.

![Word의 Copilot으로 작성된 초안을 사용한 후 옵션 모음의 스크린샷.](../media/create_copilot-prompt-box-word.png)

다음 예제에서는 Word의 Copilot에서 기본 프롬프트를 필요한 정보를 필요한 방식으로 제공하는 잘 구성된 상황에 맞는 프롬프트로 전환해 보겠습니다.

## 사용해 보겠습니다.

먼저 **_[Contoso CipherGuard Product Specification.docx](https://go.microsoft.com/fwlink/?linkid=2269123)_** 파일을 다운로드하고 아직 다운로드하지 않은 경우 **OneDrive 폴더**에 저장합니다.

Word에서 문서를 연 다음 리본의 **홈** 탭에서 Copilot 아이콘을 선택하여 **Copilot** 창을 엽니다. 아래 프롬프트를 입력하고 따라합니다.

> [!NOTE]
> 시작 프롬프트:
>
> _마케팅 제안 초안을 작성해 줘._

이 간단한 프롬프트에서는 기본 **목표**인 _새 마케팅 제안서 작성_으로 시작합니다. 그러나 해당 제안이 무엇을 지원하는지 또는 누가 관련되어 있는지에 대한 정보는 없습니다.

| 요소 | 예시 |
| :------ | :------- |
| **기본 프롬프트:** 목표로 **시작** | **_마케팅 제안 초안을 작성해 줘._** |
| **좋은 프롬프트:** 컨텍스트 **추가** | **컨텍스트**를 추가하면 Copilot이 만들 문서의 종류와 사용할 문서를 이해하는 데 도움이 될 수 있습니다. "_...Contoso의 최신 제품인 CipherGuard에 대해서, 마케팅 캠페인을 위한 세 가지 아이디어를 내 줘..."_ |
| **더 나은 프롬프트:** 원본 **지정** | **원본**을 추가하면 Copilot이 특정 정보를 찾을 수 있는 위치를 파악하는 데 도움이 됩니다. _"... 제품 사양 및 요구 사항을 사용해서 해 줘."_ |
| **최상의 프롬프트:** 명확한 **기대치 설정** | 마지막으로 **기대치**를 추가하면 Copilot이 문서를 작성하고 서식을 지정하는 방법을 이해하는 데 도움이 됩니다. _"제품, 각 아이디어에 대한 장단점 및 ROI 프로젝션에 대한 간략한 개요를 포함해 줘. 문서를 두 페이지로 유지하고 낙관적이고 설득력 있는 언어로 써 줘."_ |

> [!NOTE]
> **완성된 프롬프트**:
>
> _Contoso의 최신 제품인 CipherGuard에 대한 마케팅 제안 초안을 작성해야 해. 제품 사양 및 요구 사항을 사용하여 마케팅 캠페인에 대한 세 가지 아이디어를 내 줘. 제품에 대한 간략한 개요, 각 아이디어에 대한 장단점 및 ROI 프로젝션을 포함해 줘. 문서를 두 페이지로 유지하고 낙관적이고 설득력 있는 언어로 써 ._

프롬프트의 결과를 검토하고 질문이나 개선 사항이 있으면 추가 작업을 한 다음 이를 새 섹션의 문서 끝에 추가합니다. 파일을 **저장**하여 나중에 사용할 수 있도록 합니다.

이 프롬프트는 Copilot에게 **목표**, **컨텍스트**, **원본**, **기대치** 등 올바른 답을 도출하는 데 필요한 모든 정보를 제공합니다.

### 원본 참조

Copilot이 이미 있는 파일에서 새 문서를 기반으로 하려면 이 작업을 수행하도록 지시할 수 있습니다. **Copilot으로 초안 작성** 대화 상자에서 **파일 참조**를 선택하여 새 문서를 작성할 때 Copilot이 참조할 **_최대 3개의 파일_** 을 선택합니다.

작성 상자에 '/'와 참조하려는 파일 이름을 입력하면 선택 메뉴에 표시된 파일 옵션이 업데이트됩니다.

> [!IMPORTANT]
> 참조하는 파일에 액세스할 수 있는 권한이 있어야 하며, 해당 파일이 조직의 SharePoint 또는 OneDrive에 있거나 또는 Word 또는 PowerPoint 파일 형식이어도 됩니다.

## 추가 탐색

한번 사용해 보시겠? 사용자 고유의 문서 및 프레젠테이션을 사용하여 만든 프롬프트를 사용합니다. 그 후에 시도해 볼 수 있는 다른 프롬프트에 대한 몇 가지 제안 사항이 있습니다.

- _일과 삶의 균형을 만드는 것의 중요성에 대한 문서를 작성합니다._

- _프로젝트 관리에 대한 백서를 작성합니다_.

- _Contoso의 영업직에 대한 채용 제안서를 작성해 줘. 시작 날짜는 8월 1일이고 급여는 연봉 $60,000에 보너스를 추가한 금액이야_.
