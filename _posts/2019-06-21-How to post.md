---
layout: post
title:  "Welcome to SHINDAWIT!"
date:   2019-06-21 13:48
categories: DAWIT
---
cd ~
cd SHINDAWIT.github.io
~에 있는 자신의 깃허브 저장소로 이동합니다.
git status
파일의 상태를 확인합니다. 새로 만들어진 파일이 있거나 수정된 파일이 있거나 삭제된 파일이 있을 경우 하단에 붉은색 글자로 그 파일의 상태를 보여줍니다.
git add *
새로 만들어진 파일을 커밋할 수 있게 바꿔줍니다.
git status
다시 상태를 확인해 봤습니다. 새로 만들어진 파일이 있고 그 파일이 커밋될 수 있다는 의미로 초록색으로 표시된 걸 확인했습니다.

git commit -m "~ commit"
커밋을 하고 커밋 메세지를 입력합니다. 메세지는 꼭 입력해야 한다.
git status
현재 수정되거나 삭제되거나 새로 만들어진 파일이 있는 지 없는 지 확인해 봅니다.
git remote -v
현재 리모트 저장소를 확인하기 위해 명령어를 입력해봤습니다.
git push
이 명령어를 입력하면 이제 깃허브 블로그에 작성했던 글이 보이게 됩니다.
깃허브 저장소에 커밋된 파일들을 밀어넣습니다.
