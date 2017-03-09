# 필요 프로그램과 계정 {#install}

GitBook은 문단양식, 강조, 색상, 그림삽입, 링크, 각주, 수식 등 간단한 편집을 지원하는 위드프로세서와 유사한 편집기를 제공해 손쉽게 문서를 작성할 수 있게 해주는 도구입니다.

GitBook에서 작성된 문서는 실제로는 MarkDown\(이하 md 파일\)이라는 간단한 텍스트 기반 문서파일로 저장되게 됩니다. md 파일은 GitHub 둥에서 그림이나 링크, 소스 등을 포함하는 문서를 만들기 위해 많이 사용되며 특히 프로젝트를 설명하는 README.md 파일은 거의 필수로 사용됩니다. md 파일은 간단한 몇 가지 텍스트 기반 마크를 이용해 HTML 등 문서를 손쉽게 만들 수 있게 해 줍니다.

GitBook의 데이터 파일인 md 파일들은 git 저장소를 이용해 버전이 관리됩니다. 때문에 git의 특성이 그대로 반영되어 여러 사람이 동시에 분산된 환경에서 작업이 가능하게 됩니다. GitBook 작업에서도 commit, push, pull, brench 등 git의 기능들이 사용되지만 UI를 이용해 \[Save\], \[Sync\] 등의 버튼으로 좀 더 간단히 작업이 필요합니다.

때문에 GitBook 작업을 하기 위해서는 GitBook Editor와 Git Client 프로그램이 필요하고, GitBook과 GitHub의 계정이 필요합니다.

## Git Client 설치

GitBook을 설치하기 전에 GitBook의 동작 기반이 되는 Git을 먼저 설치해 주는 것이 좋습니다. 이미 설치가 되어 있는 분은 설치된 버전일 이용하시면 됩니다.

아직 Git이 설치되지 않으신 분은 각 OS에 맞게 Git Client를 설치해 주십시오. 대부분의 OS에는 Git이 기본으로 설치되어 있으나 윈도우에는 별도의 설치가 필요합니다. 설치가 필요한 사용자는  [https://git-scm.com/download](https://git-scm.com/download) 에서 각 OS에 맞는 Git Client를 다운받아 설치하시면 됩니다.

설치를 하시 후에는  도스창\(cmd\) 혹은 terminal 등 OS Command를 입력할 수 있는 창을 띄워 'git' 명령을 입력해 도움말이 나오는지 확인하시면 됩니다.

![](/assets/git_win.png)

![](/assets/git_linux.png)

## GitBook Editor

GitBook Editor는 다음 경로에서 받으실 수 있습니다.  [https://www.gitbook.com/editor/](https://www.gitbook.com/editor/)

윈도우, OS X, Ubuntu 용 설치파일이 있으니 사용자의 OS에 적합한 설치파일을 받아 설치하시면 됩니다.

GitBook Editor를 사용하기 위해 꼭 GitBook 계정이 필요하지는 않습니다. 설치 후 GitBook Editor를 실행하시면 첫 화면에서 로그인 정보를 요구하지만, 이를 무시하고_** \[GitBook Editor\]-\[Import...\]**_ 등의 메뉴를 이용해 계정 없이 책 만들기 작업에 참여 가능합니다.

![](/assets/GitBookLogin.png)

## GitHub 계정

하지만 협동 작업을 위해 GitHub의 계정은 반드시 필요합니다. 계정이 없어도 저장소의 컨텐츠를 받아와 GitBook Editor에서 마음대로 수정할 수는 있지만, 공동작업을 하는 저장소에 쓸 권한을 받을 수는 없습니다.

때문에 혹시 GitHub 계정이 없으신 분은 꼭 계정을 생성해 주시고, 작업에 참여하실 분들인 참여를 원하는 계정을 [GitHub의 Issue 기능을 이용해 관리자에게 알려 주십시오](/github.md#join).

