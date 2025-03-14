# 연습 - Microsoft 365 Copilot과 함께 예제 데이터를 사용하여 팔로우

이 모듈에서는 다음 파일을 참조하는 Microsoft 365 Copilot용 프롬프트를 만들어 보겠습니다.

- [Market Analysis Report for Mystic Spice Premium Chai Tea.docx](https://go.microsoft.com/fwlink/?linkid=2268826)
- [Mystic Spice Premium Chai Market Analysis Presentation.pptx](https://go.microsoft.com/fwlink/?linkid=2268768)
- [Mystic Spice Premium Chai Tea product description.docx](https://go.microsoft.com/fwlink/?linkid=2268929)
- [Fabrikam Q1 marketing campaigns.xlsx](https://go.microsoft.com/fwlink/?linkid=2269124)

**참고**: 이 파일들은 모듈 전체에서 참조할 파일입니다. 하지만 이 랩에서는 모든 파일을 **OneDrive**에 업로드하여 나중에 Copilot 프롬프트에 액세스할 수 있도록 하겠습니다.

## OneDrive에 파일 업로드

아래 단계에 따라 필요한 모든 파일을 **OneDrive**에 업로드합니다.

1. 테넌트 공급자가 제공한 가상 머신에 로컬 **관리자** 계정으로 암호를 사용하여 로그인합니다.`Pa55w.rd`
2. Windows 작업 표시줄에서 **Microsoft Edge**를 선택합니다.
3. 주소 표시줄에 `https://www.office.com`을 입력합니다.
4. **Microsoft 365 시작**에서 **로그인**을 선택합니다.
5. **로그인 프롬프트**에서 `userx@yourtenant.onmicrosoft.com`(테넌트가 제공한 사용자 이름과 테넌트) 입력 후 **다음**을 선택합니다.

    [![Skillable의 리소스 창 스크린샷](../media/lab_resources_password.png)](../media/lab_resources_password.png#lightbox)

6. **암호 입력** 화면에서 사용자 계정의 암호(테넌트 공급자가 제공)를 입력한 후 **로그인**을 선택합니다.
7. **로그인 유지**라는 메시지가 표시되면 **다시 표시하지 않음**을 선택한 다음 **예**를 선택합니다.
8. **Microsoft 365**에서 **앱**을 선택합니다.
9. **앱**에서 **OneDrive**를 선택합니다.
10. **OneDrive**의 왼쪽 상단에서 **+**(새로 추가) > **파일 업로드**를 선택합니다.
11. **파일 탐색기**에서 **내 PC** > **로컬 디스크(C:)** 를 선택하고 **ResourceFiles** 폴더를 엽니다.
12. **ResourceFiles** 폴더 내의 모든 파일을 선택한 다음 **열기**를 선택하여 **OneDrive**에 업로드합니다.
13. 업로드가 완료되면 화면 중앙 하단에 **내 파일에 29개 항목 업로드됨**이 표시됩니다.
14. **Edge**를 열어 두고 다음 작업으로 이동합니다.

### 참조 파일

Copilot에서 파일을 참조할 때 제공된 제안에서 일부 파일을 찾을 수 없습니다. Copilot의 특정 환경에서는 MRU(가장 최근 사용) 목록의 파일만 참조하는 반면 다른 환경에서는 OneDrive에서 파일을 직접 찾아볼 수 있기 때문에 이러한 현상이 가끔 발생합니다. 해당 목록에 추가하는 것은 적절한 Microsoft 365 앱에서 여는 것만큼 쉽습니다.  열면 MRU 목록에 표시됩니다.

> [!IMPORTANT]
> Microsoft 365 Copilot은 OneDrive에 저장된 파일에서만 작동합니다. PC에 로컬로 저장된 파일은 해당 파일을 OneDrive로 이동하여 Copilot을 활성화해야 합니다.

모듈을 진행하면서 이러한 파일에 대해 다른 프롬프트를 사용해 볼 수 있으며 프롬프트 기술을 탐색하고 향상시키기 위해 그렇게 하는 것이 좋습니다.
