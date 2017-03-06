# 새로운 문서 작성 프로젝트 만들기

이 챕터는 문서만들기에 참여하시는 분들 대부분은 알지 않아도 되는 정보가 담겨 있습니다. 하지만, 직접 새로운 문서 프로젝트를 만들고자 하시는 분께는 도움이 될 수도 있는 내용입니다.

## 새 책 만들기

새 책을 만들기 위해서는 GitBook Editor를 실행하고 첫 화면에서 하단에 있는 \[+ New Book\] 버튼을 눌러야 합니다.

![](/assets/new_book.png)

그 다음 적절한 책 이름을 입력하고 \[Confirm\] 버튼을 누르면 새 책이 만들어 집니다.

새 책의 데이터 파일은사용자  일반적으로 사용자 계정 아래의 ~/GitBook/Library/ 폴더 아래에 생기게 됩니다. GitBook의 데이터 파일인 md 파일들과 그림들이 모두 이 폴더 안에 들어가게 됩니다. 이 파일들을 적절히 일반 에디터로 수정하여 좀 더 복잡한 작업도 가능합니다. 하지만, 이 중 README.md 파일과 SUMMARY.md은 주의가 필요합니다. README.md 파일은 삭제하거나 이름을 바꾸면 안되고, SUMMARY.md 파일은 임의로 편집하는 것을 권장하지 않습니다.

## GitHub 저장소 연결하기

먼저 [https://github.com](https://github.com\) 에 가셔서 GitHub에 저장소\(Repository\)를 만들어 줍니다. 저는 이 문서를 만들기 위해 [https://github.com/Gaia3D/gitbookGuide]\(https://github.com/Gaia3D/gitbookGuide) 라는 저장소를 만들어 주었습니다. 이 저장소는 처음 만들어 비어있는 상태면 되고 README.md 등의 파일 자동생성도 안 하는 것이 좋습니다.

그리고 GitBook Editor에 이 저장소를 연결해 줍니다. GitBook Editor에서 \[Book\]-\[Repository Sittings...\] 메뉴를 이용하면 됩니다. Repository Settings 대화상자에 Github 접근경로를 적어주시면 됩니다.

![](/assets/new_book_repo.png)

이 후 저장소와 동기화를 위해 \[Book\]-\[Sync\] 메뉴를 누르시면 동기화가 진행되어 내가 새로 만든 GitBook이 새로 만든 GitHub 저장소에 올라가게 됩니다. 이 때 GitHub 계정에 대한 정보가 입력되지 않은 상태라면 계정 정보를 물어볼 수도 있습니다.

![](/assets/ㅜㄷㅈ_ㅠㅐㅐㅏ_햐소ㅕㅠ_ㅁㅊ채ㅕㅜㅅ.png)

동기화가 완료된 후 GitHub.com의 해당 저장소 페이지에 가서 웹 페이지를 갱신해 보시면 다음처럼 자동생성된 md 파일들을 보실 수 있습니다.

![](/assets/new_book_reop.png)이 GitHub 저장소를 사람들에게 알려주고 clone 받도록 하면 GitBook을 이용해 새로운 문서 프로젝트를 진행하실 수 있습니다.

저의 경우는 GitBook Editor가 업데이트 되면서 이 기능에 갑자기 오류가 생겼습니다. 대신 \[Book\]-\[Sync\] 메뉴을 눌렀더니 저장소 설정을 할 수 있었습니다. 아마 일시적인 버그인 듯 합니다.

## GitHub 저장소를 GitBook 계정에도 올리기

이처럼 GitBook 사이트에서 만들지 않은 책도 GiyHub를 이용해 협동작업이 가능하지만, 이를 웹상에서 보기 쉽게 하려면 Publish가 필요합니다. 이제 GitHub에 올려진 책을 GitBook 계정으로 가져와 봅시다.

이 작업을 위해서는 GitBook 사이트의 자기 계정에 GitHub 플러그인을 연결해야 합니다.

먼저 https://gitbook.com 에 접속해 로그인 합니다. 그리고 상단 오른쪽의 계정 아이콘 옆의 삼각형을 눌러 계정관련 메뉴들을 펼칩니다. 이 중 \[Account Settings\] 메뉴에 GitHub 저장소의 책을 가져오는 기능이 숨어 있습니다.

![](/assets/new_book_import2.png)

Personal settings에서 \[GitHub\] 탭을 선택하고 \[Create a Book from GitHub\] 버튼을 누릅니다.

![](/assets/new_book_repo_create.png)

Create a new book 화면에서 GIT 탭을 선택하고\(GitHub 탭은 자기 계정뿐이 못 보는 문제가 있음\) Title과 Git 저장소의 경로를 입력해 주고 \[Create Book\] 버튼을 누르면 GitHub에 있는 책이 GitBook 계정으로 들어오게 됩니다.

![](/assets/new_book_create_book.png)







