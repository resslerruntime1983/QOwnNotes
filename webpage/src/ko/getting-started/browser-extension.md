---
image: /img/bookmarks.png
---

# QOnNotes 웹 지원 브라우저 확장

브라우저 페이지에서 클리핑하고 브라우저 및 운영 체제에서 브라우저 북마크를 관리할 수 있습니다.

::: 팁 정보
- 웹 지원 브라우저 확장이 작동하려면 QOnNotes가 실행 중이어야 합니다.
- 인터넷 연결이 필요하지 않습니다. 브라우저 확장은 **오프라인**으로 작동합니다. :::

## 설치

1. 확장 가져오기
    - [Chrome 웹 스토어](https://chrome.google.com/webstore/detail/qownnotes-web-companion/pkgkfnampapjbopomdpnkckbjdnpkbkp)
    - [Firefox 부가 기능 페이지](https://addons.mozilla.org/firefox/addon/qownnotes-web-companion)
    - [GitHub](https://github.com/qownnotes/web-companion/)에서도 확장 버전을 찾을 수 있습니다.
2. 확장을 구성하려면 보안 토큰을 추가하십시오.
    - QOnNotes 브라우저 확장 아이콘을 처음 누르면 보안 토큰이 있는 대화상자가 나타납니다. 토큰을 복사합니다.
    - 브라우저의 확장 관리 위치로 이동합니다. QOnNotes 확장 세부사항을 누릅니다.
    - 토큰을 보안 토큰 필드에 붙여넣습니다.

## 웹 클리퍼

![웹 클리퍼](/img/web-clipper.png)

웹 페이지 또는 선택한 텍스트를 마우스 오른쪽 버튼으로 클릭하여 **웹 클리퍼** 기능을 사용합니다. 여기서 현재 웹 페이지의 **스냅샷** 으로 새 노트를 만들 수도 있습니다.

::: 팁 웹 클리퍼는 또한 스크립팅이 가능합니다! 웹 페이지에서 클리핑한 내용을 제어하려면 [websocketRawDataHook](../scripting/hooks.md#websocketrawdatahook)을 살펴 보십시오. :::

## 북마크

![북마크](/img/bookmarks.png)

브라우저 북마크를 완전히 제어하고 **다른 브라우저 및 운영 체제에서 사용하려면** QOnNotes 브라우저 확장자를 사용하십시오.

기본적으로 브라우저 확장은 브라우저에서 QOnNotes 아이콘을 누르면 팝업에 **현재 노트의 모든 링크**를 표시합니다. 이러한 링크는 `현재` 태그가 표시됩니다.

노트 태그 `북마크`를 사용하여 **노트의 북마크를 관리**할 수도 있습니다 (설정에서 변경 가능). 이러한 링크에는 브라우저 확장에 표시될 태그와 설명이 있을 수도 있습니다.

새 북마크는 `북마크`라는 노트에 저장됩니다 (설정에서도 변경 가능).

::: 팁
웹 지원 브라우저 확장자를 사용하여 브라우저 북마크를 QOnNotes로 가져올 수도 있습니다!
:::

### 북마크 링크 구문

```markdown
- [Webpage name](https://www.example.com)
- [Webpage name](https://www.example.com) #tag1 #tag2
- [Webpage name](https://www.example.com) 일부 설명만
- [Webpage name](https://www.example.com) #tag1 #tag2 일부 설명 및 태그
* [Webpage name](https://www.example.com) 대체 목록 문자도 작동합니다
```

브라우저 확장에서 이름, url 태그 또는 설명을 검색할 수 있습니다.