## Cloud Pub/Sub の概要
Google Cloud Pub/Subは、GCPが提供するリアルタイムメッセージングサービス. 
データを効率的に送受信して、アプリケーション間の通信を簡単に行えるように設計されている。
Pub/Subの由来は、「Publish」、「Subscribe」

### 主な機能と特徴
1. リアルタイムメッセージング:高速で効率的なメッセージングが可能、リアルタイム処理や分散システムの構築に適している
2. グローバルなメッセージ配信：Cloud Pub/SubはGCPのインフラを利用して、世界中にメッセージを配信できる
3. 高いスケーラビリティ：大量のメッセージを処理できて、リクエストに応じて、自動的にスケーリングされる
4. 疎結合なアーキテクチャ：発行者と購読者が直接接続せず、システム全体の耐障害性や拡張性が向上する
5. アトリビュートによるメッセージのフィルタリング：メッセージにアトリビュートを追加することで、購読者が特定の条件を満たすメッセージだけを受信できる

### ユースケース
1. Iotデバイスデータの収集:Iotデバイスからリアルタイムで、データを収集し、そのデータを分析サービスやストレージサービスに送信できる
2. リアルタイムアナリティクス：ユーザーアクションやアプリケーションイベントをリアルタイムで収集し、データ分析やダッシュボード表示に活用できる
ストリーミングデータ分析
4. 分析システムの構築：サービス間で、メッセージをやり取りすることで、複雑な分散システムを構築できる
5. ワークフローの自動化：タスクの完了をトリガーにして次のタスクを自動的に開始するようなワークフローを実現できる
6. モバイルアプリケーションとの通信：モバイルアプリケーションとバックエンドサーバー間で、リアルタイムにメッセージをやりとりできる
モバイルアプリのプッシュ通知
