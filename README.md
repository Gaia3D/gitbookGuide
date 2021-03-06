# GitBook을 이용한 오픈소스 매뉴얼 작업 가이드

이 문서는 한국 PostgreSQL 사용자 모임 및 OSGeo 한국어 지부에서 여러 사용자가 협동하여 오픈소스 매뉴얼을 만들기 위해, GitBook을 작업도구로 사용하는 과정을 가이드하는 문서입니다.

이 가이드는 충돌을 최소화 하면서 공동 작업을 하기 위한 워크플로우를 설명하고, 한글을 사용하는 문서작업시의 문제를 해결하는 것에 중점을 맞추어 작성되었습니다.

GitBook을 이용한 작업은 일반적인 문서 작성에서의 내용작성\(컨텐츠 생산\)과 조판\(랜더링\)의 과정이 분리되어 있으며, 이 문서에서는 내용작성\(컨텐츠 생산\)에 해당하는 과정만을 기술합니다. 참고로 조판\(랜더링\)과정은 Publish라고 표현되며 원하는 스킨을 입혀 웹페이지나 PDF 등의 형태로 만들 수 있습니다.

실제 문서제작 협업을 위해서는다음과 같은 과정을 거치게 됩니다.

1. [Git Client, GitBook Editor 등 필요 프로그램을 설치하고 GitHub 계정을 만듭니다.](/program_account.md#install)
2. [편집을 원하는 책이 있는 GitHub 저장소의 Issiue에 편집 참여를 원한다는 내용으로 이슈를 만듭니다.](/github.md#account)
3. [관리자가 이 이슈를 확인하고, 해당 사용자에게 저장소에 쓸 수 있는 권한을 부여합니다.](/github.md#accept)
4. [git의 clone 명령을 이용해 GitHub에서 파일들을 받아옵니다.](/github.md#clone)
5. [GitBook Editor에서 git 저장소를 Open 하고 Sync 후 편집을 시작합니다.](/write_content.md#open)
6. [자신이 작성 원하는 챕터를 \[Add an article\] 기능을 이용해 만들어 줍니다. 혹은 이미 만들어진 챕터를 선택합니다.](/write_content.md#newchaptor)
7. [자신이 작성하는 챕터의 내용을 작성하고 저자가 작성의 작은 단위가 끝났다 판단할 때 \[Save\] 합니다.](/write_content.md#write)
8. [하루의 작업을 끝낼 때, 혹은 그보다 더 자주 \[Sync\] 기능을 이용해 GitHub의 저장소에 올려 공동 작업자들이 받을 수 있게 합니다.](/write_content.md#sync)



