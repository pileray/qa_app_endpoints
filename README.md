# qa_app_endpoints
|やりたいこと|HTTPメソッド|エンドポイント|コントローラ#アクション|
|:----|:----|:----|:----|
|ユーザー登録画面を表示する|GET|/users/new|users#new|
|ユーザー登録をする|POST |/users |users#create |
|ログイン画面を表示する|GET |/login |session#new |
|ログインする|POST |/login |session#create |
|ログアウトする|DELETE |/logout |session#destroy |
|質問一覧を表示する（全て）|GET |/questions |questions#index |
|質問一覧を表示する（未解決）|GET |/questions/unsolved |questions#show_unsolved |
|質問一覧を表示する（解決済み）|GET |/questions/solved |questions#show_solved |
|質問投稿ページを表示する|GET |/questions/new |questions#new |
|質問投稿をする|POST |/questions |questions#create |
|質問詳細を表示する|GET |/questions/:id |questions#show |
|質問編集ページを表示する|GET |/questions/:id/edit |questions#edit |
|質問を削除する|DELETE |/questions/:id |questions#destroy |
|回答する|POST |/questions/:id/answers |answers#create |
|ユーザー一覧を表示する|GET |/users |users#index |
|管理画面用のログインページを表示する|GET |/admin/login |session#admin_new |
|管理画面用のログインをする|POST |/admin/login |session#admin_create |
|（管理画面）質問一覧ページを表示する|GET |/admin/questions |questions#admin_index |
|（管理画面）質問を削除する|DELETE |/admin/questions/:id |questions#admin_destroy |
|（管理画面）ユーザー一覧ページを表示する|GET |/admin/users |users#admin_index |
|（管理画面）ユーザーを削除する|DELETE |/admin/users/:id |users#admin_destroy |
