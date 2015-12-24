번역된 문서들은 먼저 일본어로 번역된 https://github.com/niku/elixir-lang.github.com 를 바탕으로 한국어로 번역하였습니다.

일본어 사이트를 참고한 이유는 구글 번역기가 일본어를 한국어로 잘 번역하기 때문이기도 하고 이를 컴파일 하여 Github pages에 한국어 문서를 호스팅하기 위해 git repository를 사용하였습니다.
하지만 번역기만 사용한것은 아니며 영어원문을 참고하여 재번역하였습니다.

아직 번역되지 않는 페이지는 첨부된 구글 웹사이트 번역기를 통해서 볼 수 있습니다.

### Contents for Elixir website hosted at elixir-lang.org

It is automatically transformed by [Jekyll](http://github.com/mojombo/jekyll) into a static site.

### Development

Development is done in the `next` branch, while `master` contains the docs and guides for the latest stable release.

### Contributing to the blog

  Create a new file inside `_posts/YYYY-MM-DD-post-title.markdown` following the template:

    ---
    layout: post
    title:
    author:
    category:
    excerpt:
    ---

    Body text goes here...

  Or use `_bin/newpost` to bootstrap a new post file:

    export EDITOR=vim; _bin/newpost 'Post title'

### Contributing improvements or bug fixes

1. Fork elixir-lang.github.com

2. Make your changes

3. Test it locally

   You need to install `jekyll`, `jekyll-redirect-from` and `redcarpet`

   ```shell
   $ gem install jekyll jekyll-redirect-from redcarpet
   $ jekyll serve # check localhost:4000
   ```

4. Send a pull-request for your changes.

### License

* "Elixir" and the Elixir logo are copyrighted to [Plataformatec](http://plataformatec.com.br/). You may not reuse anything therein without permission.

* The HTML and CSS are copyrighted to [AlienWp](http://alienwp.com/) under [GPL license, version 2](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html).

* The Social Icons are copyrighted to [Xeloader](http://xeloader.deviantart.com/art/Socialis-2-Freebie-213292616).

* The written textual contents available in the guides and blog are licensed under Apache 2.0.

* The available docs are licensed under the same license as their projects.
