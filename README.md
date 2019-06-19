# Spring-Security-thymeleaf-demo

## abstract
SpringSecurityとThmeleafの組み合わせを検証するアプリです。
### 認証方法
フォーム認証です。以下のユーザ名/パスワードの組み合わせでログインできます。
* testuser/useruser
* testadmin/adminadmin

### 権限
SpringSecurityの権限オブジェクトを「thymeleaf-extras-springsecurity5」の仕組みを用いて、
thymeleafから使用できるようにしています。そうすることで、権限による制御をhtmlに埋め込むことができます。

