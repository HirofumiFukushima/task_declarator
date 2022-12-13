# task_declarator
## util
- Valueクラス？  
    数値（テンプレート）と単位名を保持する型  
    - 数値が演算可能な型で、型単位名が同じなときのみ加減算可能  
    - 乗算・除算いる？

## コア部分
- Taskクラス  
    タスク名・タスク説明・目標値（Valueクラス）
- UserAccountクラス  
    ユーザー名・email・所属組織・権限  
- UserTaskクラス  
    UserAccount、Taskと進捗list（date, Value のタプルのlist）