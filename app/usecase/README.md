### UseCase Layer

- UseCase
- OutputDTO
- InputDTO

Entity Layer のオブジェクトや関数を用いて、ユースケースの処理を実行する
domain と同じようにディレクトリを構成する
各ドメインでは、ユースケースごとにファイルを分けて実装する

アプリケーションのユースケースを実行する
Interface Adapter Layer（[infrastructure](../infrastructure/README.md)・[presentation](../presentation/README.md)）とのデータのやり取りは、InputDTO と OutputDTO を用いる
