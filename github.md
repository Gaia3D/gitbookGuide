# 작업할 책을 GitHub에서 받아와 열기

## GitHub 저장소에 쓰기 권한 요청하기 {#join}

GitHub 저장소의 내용을 받아오기만 할 때는 쓰기 권한이 필요하지만 공동작업을 위해서는 반드시 쓰기 권한이 필요합니다. 때문에 관리자에게 이를 요청해야 하는데 GitHub의 Issue 기능을 이용하면 요청내용을 관리자에게 알릴 수 있습니다.

각 문서를 만들기 위한 저장소의 GitHub 주소는 다음과 같습니다.

* PostgreSQL 안내서: [https://github.com/PostgreSQL-Korea/pgdoc-kr](https://github.com/PostgreSQL-Korea/pgdoc-kr)
* QGIS 초급자용 교재: [https://github.com/osgeo-kr/qgisdoc101](https://github.com/osgeo-kr/qgisdoc101)

GitHub에서 참여를 원하는 저장소에 가셔서 \[Issues\] 탭을 누르고 \[New issue\] 버튼을 눌러 이슈를 만드시면 요청내용이 관리자에게 전달됩니다. 여기에 다음 예처럼 관리자에게 책 만들기에 참여하고자 한다는 내용으로 간단히 써주시면 됩니다.

![](/assets/access_request.png)

## 관리자의 권한부여 절차 {#accept}

관리자가 Issue를 확인하면 자동으로 권한이 부여되는 것은 아니고 수동으로 권한을 부여해야 합니다. 관리자가 GitHub 저장소의 \[Settings\]  탭의 \[Collaborators & teams\] 탭에 있는 \[Collaorators\] 기능을 이용해 권한을 요청한 사용자를 Collaborator로 지정해야 합니다.

![](/assets/add_autor.png)

이렇게 한 명 한명 등록하는 과정을 거쳐야 하기에 신청후 확인을 하고 권한을 부여하는데 시간이 걸릴 수 밖에 없으니 권한 부여가 조금 늦어지더라도 양해 부탁드립니다.

## 작업할 책을 GitHub 저장소에서 받기 {#clone}

공동 저작 작업을 진행할 책은 Git 명령 혹은 SourceTree 등의 도구를 이용해 GitHub의 저장소에서 받아오실 수 있습니다. 이 문서에서는 git 명령을 이용하는 방법을 설명합니다

1. 도스창\(cmd\)이나 Terminal을 엷니다.
2. 저장소를 받아오기 원하는 폴더로 이동합니다.
3. git clone 명령으로 작업할 저장소를 받아옵니다.
   * PostgreSQL 안내서의 경우: `git clone https://github.com/PostgreSQL-Korea/pgdoc-kr.git`
   * QGIS 초급자용 교재의 경우: `git clone https://github.com/osgeo-kr/qgisdoc101.git`





책을 작업하는 화면은 일반적인 문서편집기와 유사합니다.

