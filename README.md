# deep_into_us

* scuba-it은 scuba diving과 관련한 정보를 공유합니다.
* 편집에 자유롭게 참여 가능 합니다. 
* 단순한 정보의 갱신은 "Pull requests" 기능을 사용할 수 있습니다.
* 자주 업데이트 하고 싶다면 권한을 요청하세요.

## 알아야 할 기술들

### jekyll(지킬) - 지킬은 github.com 에서 page를 작성하고 관리하는 기본 툴.

* 공식 : https://jekyllrb.com/
* 한국어 : https://jekyllrb-ko.github.io/

### Markdown

#### Kramdown - github에서 사용하는 markdown

* https://kramdown.gettalong.org/

#### Markdown 목차 생성하기(TOC - Table of Contents)

* Makrdown 기본기능에는 목차 생성기능이 없어서 긴 post를 볼때 인덱스를 통해 원하는 주제를 찾기 어렵다.
* 외부 툴을 이용해서 생성을 해주는게 가능하며 각 IDE에서 Plugin형태로 지원하는 것을 사용하는게 편하다.
  * Visual Stdio Plugin : <https://marketplace.visualstudio.com/items?itemName=AlanWalk.markdown-toc>
  * ATOM : <https://atom.io/packages/markdown-toc>
  * VIM : <https://www.vim.org/scripts/script.php?script_id=5460>
* 웹페이지를 통한 TOC생성
  * <https://ecotrust-canada.github.io/markdown-toc/>

#### Youtube Video 첨부하기

* 유투브 영상을 바로 넣을 수 는 없고 이미지형태로 변경하여 넣어야합니다.
  *
    ```
    <a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
    " target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
    alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
    Or, in pure Markdown, but losing the image sizing and border:
    ```
    ```
    [![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
    ```
  * <http://embedyoutube.org/>

### github pages

* awesome doc: http://jmcglone.com/guides/github-pages/

### Customized

* Auto Play Video when Visualable
   *  class 에 "autoplayable" 적용

## 더 읽을 거리들

* THEME 커스텀하기: http://jihyeleee.com/blog/third-designer-can-make-jekyll-blog/

## 사용한 THEME

* prologue https://github.com/chrisbobbe/jekyll-theme-prologue

