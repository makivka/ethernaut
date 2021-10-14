自分のコードではないものを使うときには、そのコードに慣れ親しんで、すべてがどのように組み合わされているかをよく理解しておくとよいでしょう。これは、複数のレベルのインポートがある場合 (自分のインポートにインポートがある場合) や、権限制御を実装している場合 (例えば、人が何かをすることを許可したり禁止したりしている場合) に特に重要になります。この例では、開発者はコードに目を通し、トークンを移動させるには `transfer` が唯一の方法だと思うかもしれませんが、驚いたことに、同じ操作を別の実装で行う方法もあります。