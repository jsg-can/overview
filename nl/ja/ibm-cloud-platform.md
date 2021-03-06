---


copyright:
  years: 2016, 2018
lastupdated: "2018-11-30"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# {{site.data.keyword.Bluemix_notm}} プラットフォームとは何ですか?
{: #whatis}

IBM のクラウド・プラットフォームは、Platform as a Service (PaaS) と Infrastructure as a Service (IaaS) を組み合わせて、統合エクスペリエンスを提供します。このプラットフォームは、小規模な開発チームと組織、および大規模な企業ビジネスの両方を拡大およびサポートします。世界中のデータ・センターにグローバルにデプロイされる、{{site.data.keyword.cloud}} で構築するソリューションは、テスト済みでサポートされた、信頼できる環境で、高速かつ確実に稼働します。
{: .shortdesc}

{{site.data.keyword.Bluemix_notm}} プラットフォームは、連携する複数のコンポーネントで構成されており、一貫性のある信頼できるクラウド・エクスペリエンスを提供します。 

  * 数百の {{site.data.keyword.Bluemix_notm}} オファリングで構成されるカタログ
  * クラウド・リソースの作成、表示、管理のフロントエンドとして機能する堅固なコンソール
  * 両方のプラットフォーム・サービスのユーザーを安全に認証し、{{site.data.keyword.Bluemix_notm}} 全体で一貫してリソースへのアクセスを制御する ID およびアクセス管理コンポーネント
  * リソースをフィルタリングおよび識別するための検索およびタグ付けのメカニズム
  * 価格設定プランおよびセキュア・クレジット・カード詐欺防止のために正確な使用量を提供するアカウントおよび請求管理システム

## ホスティング環境の選択
{: #choose-compute}

{{site.data.keyword.Bluemix_notm}} を使用すれば、新規のアプリのテストや実行のためにハードウェアに多額の投資を行う必要がなくなります。 代わりに、IBM がすべてを管理し、使用した分だけ課金されるようになります。 クラウド・サーバー環境は、インフラストラクチャー・レイヤーの基本です。単一のオプションを選択することも、より複雑な環境に対してオプションの組み合わせを選択することもできます。 

アプリをホストするためのさまざまなオプションがあり、必要に応じてインフラストラクチャーを自由に制御できます。アプリは以下のどの方法でも実行できます。

  * サーバーレス機能として実行
  * Cloud Foundry アプリとして実行
  * Kubernetes クラスター上の Docker コンテナーとして実行
  * VMware として実行
  * 仮想マシンとして実行
  * 高性能な{{site.data.keyword.baremetal_short}}上で実行 

{{site.data.keyword.baremetal_short}}は、単一の顧客専用のシングル・テナントの物理サーバーです。サーバー・ホストから RAM およびストレージ・デバイスまで、ほとんどすべてを制御します。これらのサーバーは、数カ月などの長期間にわたってコンピュート能力を必要とするワークロードで使用されます。 

{{site.data.keyword.baremetal_short}} は、パブリック・インスタンスまたは専用インスタンスとしてデプロイできます。パブリック・インスタンスでは、サーバーのリソースは他のお客様と共有されます。これはマルチテナント環境とも呼ばれます。専用インスタンスでは、物理サーバーのリソースは、同じサーバー上に 1 つ以上の仮想マシンを持つことができる 1 人のお客様専用になります。これらのサーバーは、数週間など、限られた期間実行されるワークロードに最適です。ワークロードの例としては、開発とテスト、バックアップとリカバリー、および災害復旧などがあります。サーバー・オプションについて詳しくは、『[Bare metal servers vs. virtual servers: Choosing the best option for you](https://www.ibm.com/blogs/bluemix/2018/06/bare-metal-virtual-servers-works/){: new_window} ![外部リンク・アイコン](../icons/launch-glyph.svg "外部リンク・アイコン")』を参照してください。

コンピュート・オプションの要約については、以下の表を確認してください。

| オプション | 説明 | 
|--------|---------------|
| [{{site.data.keyword.baremetal_short}}](/docs/bare-metal/about.html)  | お客様専用で、サーバー・リソースを含むどの部分でも他のお客様と共有されない、時間単位または月単位のシングル・テナント・サーバー。|
| [{{site.data.keyword.BluVirtServers_short}}](/docs/vsi/vsi_about.html) | 専用のコアおよびメモリー割り振りと共に購入される拡張が容易な仮想サーバー。 |
| [{{site.data.keyword.vmwaresolutions_short}}](/docs/services/vmwaresolutions/vmonic/prod_overview.html) | スケーラブルでセキュアでハイパフォーマンスのインフラストラクチャー、および業界最先端の VMware ハイブリッド仮想化テクノロジーを使用して、オンプレミスの VMware ワークロードを迅速かつシームレスに統合またはマイグレーションします。|
| [{{site.data.keyword.containerlong_notm}}](/docs/containers/cs_why.html) | Docker コンテナー、Kubernetes テクノロジー、直観的なユーザー・エクスペリエンス、標準装備のセキュリティーと分離機能を結合させることにより、コンピュート・ホストのクラスター内でコンテナー化アプリのデプロイメント、操作、スケーリング、モニタリングを自動化します。|
| [{{site.data.keyword.cfee_full_notm}}](/docs/cloud-foundry/index.html) | 複数の分離したエンタープライズ・グレードの Cloud Foundry プラットフォームをオンデマンドでインスタンス化します。|
| [{{site.data.keyword.openwhisk_short}}](/docs/openwhisk/index.html) | Apache OpenWhisk に基づく Functions-as-a-Service (FaaS) プログラミング・プラットフォーム。|
{: caption="表 1. 計算オプション" caption-side="top"}

## アプリケーションの作成
{: #build-apps}

最新化してクラウドに取り入れる[既存のコード](/docs/apps/tutorials/tutorial_byoc.html)があるか、[まったく新しいアプリケーション](/docs/apps/tutorials/tutorial_starter-kit.html)を開発しているかにかかわらず、開発者は、{{site.data.keyword.Bluemix_notm}} で使用可能なサービスおよびランタイム・フレームワークの急速に成長しているエコシステムを活用できます。

稼働に役立つ[プログラミング・ガイド](https://cloud.ibm.com/docs/home/build){: new_window} ![外部リンク・アイコン](../icons/launch-glyph.svg "外部リンク・アイコン") が言語ごとに用意されています。{{site.data.keyword.baremetal_short}}から、サーバーレス機能としての実行まで、{{site.data.keyword.Bluemix_notm}} インフラストラクチャーを使用してアプリをホストするための多数のオプションがあります。

## サービスの接続
{: #connect-services}

カタログには、選択できるサービスが 190 個以上あるため、ニーズに合わせて調整されたソリューションを作成できます。ユース・ケースに適合すれば、{{site.data.keyword.Bluemix_notm}} 外部のアプリにサービスを容易に接続できます。外部利用者を {{site.data.keyword.Bluemix_notm}} サービスに手動で接続させたい場合、資格情報の新しいセットを生成することができます。 例えば、{{site.data.keyword.Bluemix_notm}} 外部のアプリを Watson サービスに接続しようとすると、それらを相互に接続する新しい資格情報が生成されます。非常に簡単です。詳しくは、[資格情報の追加](/docs/resources/service_credentials.html#service_credentials)を参照してください。

## アカウントのセットアップ

{{site.data.keyword.Bluemix_notm}} を試用する場合は、そのままカタログに移動して、検討したいサービスのチェックを始めて、トライアル・アカウントまたはライト・アカウントに追加することができます。ただし、開発者グループ用または組織全体用の環境で開始して、アプリを実動環境で実行する準備ができている場合は、ご使用のアカウントに以下の基本を設定することを検討してください。

* ユーザーおよびサービス ID を 1 つのエンティティーに編成して、アクセス権の割り当てを、合理化されたプロセスにするためのユーザー・アクセス・グループ。
* リソースを編成してリソース・セットへのアクセス権の割り当てを素早く簡単にするためのリソース・グループ。
* IAM アクセス・ポリシーまたは Cloud Foundry の組織とスペースの役割を必要とするアクセス・グループまたは個々の開発者のアクセス・ポリシー。

詳しくは、『[アカウントをセットアップするためのベスト・プラクティス](/docs/account/bp_account.html#account_setup)』および『[アクセス権限を割り当てるためのベスト・プラクティス](/docs/iam/bp_access.html)』を参照してください。また、すぐに開始できる場合は、『[アカウント階層](/docs/account/account_overview.html#overview)』の各部分を確認してください。

## 価格設定および請求処理

アカウント・タイプに関係なく、無料の割り当て量を提供するサービスに対してライト・プランを使用して {{site.data.keyword.Bluemix_notm}} を探索できます。カタログからサービスを選択してタイルを選択するときに、別のタイプの使用可能プランがある場合は、価格設定情報の詳細を表示できます。有料プランでサービス・プランを選択する場合は、コスト見積もりツールを使用してコストを見積もることができます。詳しくは、[コストの見積もり](/docs/billing-usage/estimating_costs.html#cost)を参照してください。

{{site.data.keyword.Bluemix_notm}} の請求処理は、{{site.data.keyword.Bluemix_notm}} プラットフォームが価格設定、アカウント、使用量などを安全に管理できるようにする複数のサービスを提供しています。

### {{site.data.keyword.Bluemix_notm}} アカウント管理
{: #account}

アカウント管理は、顧客との請求関係を維持します。各アカウントは、1 人の顧客を表す請求エンティティーです。このサービスは、アカウント・ライフサイクル、アカウント・サブスクリプション、アカウント・ユーザー関係、およびアカウント組織を制御します。

### {{site.data.keyword.Bluemix_notm}} 価格設定
{: #pricing}

{{site.data.keyword.Bluemix_notm}} 価格設定プラットフォーム・サービスは、ユーザーが {{site.data.keyword.Bluemix_notm}} カタログ内のリソースの価格情報を定義、管理、および取得するのに役立ちます。

### {{site.data.keyword.Bluemix_notm}} Metering Collector
{: #metering}

{{site.data.keyword.Bluemix_notm}} Usage Metering は、{{site.data.keyword.Bluemix_notm}} ユーザーによってプロビジョンされたリソース・インスタンスについて収集されたメトリックをサービス・プロバイダーが送信できるようにするプラットフォーム・サービスです。{{site.data.keyword.Bluemix_notm}} で統合請求サービスを提供するサード・パーティー・サービス・プロバイダーは、すべてのアクティブ・サービス・インスタンスの使用量を 1 時間ごとに送信する必要があります。使用量を報告できないと IBM が収益を回収できなくなり、サード・パーティー・サービス・プロバイダーも収益の分配を受け取れなくなる可能性があるため、送信は重要です。

## {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM)
{: #iam}

{{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) を使用すると、プラットフォーム・サービスに関してユーザーをセキュアに認証でき、また {{site.data.keyword.Bluemix_notm}} プラットフォーム全体で一貫してリソースへのアクセスを制御できます。 詳細については、[IAM とは?](/docs/iam/index.html) を参照してください。 IAM は、トークン、アクセス・グループ、およびポリシーの管理に役立つ CLI コマンドおよび API を提供します。


## リソースの作成
{: #provisioning-layer}

リソース・コントローラーは、顧客アカウント内の {{site.data.keyword.Bluemix_notm}} リソースのライフサイクルを管理する、次世代の {{site.data.keyword.Bluemix_notm}} プラットフォーム・プロビジョニング・レイヤーです。リソースは、アカウント有効範囲内でグローバルにプロビジョンされます。リソース・コントローラーは、リソースの同期および非同期の両方のプロビジョニングをサポートします。プロビジョニング・レイヤーは、お客様のアカウントのリソースのライフサイクルの制御およびトラッキングを担当します。 リソースは、アプリケーションまたはサービス・インスタンス用にプロビジョンまたは予約できる物理コンポーネントまたは論理コンポーネントです。 リソースの例としては、データベース、アカウント、プロセッサー、メモリー、およびストレージ制限などがあります。 一般に、プロビジョニング・レイヤーでトラッキングされるリソースは、使用量メトリックと請求を関連付けるよう意図されていますが、必ずしもそうとは限りません。 場合によっては、リソース・ライフサイクルをアカウント・ライフサイクルとともに管理できるように、リソースがプロビジョニング・レイヤーに関連付けられていることがあります。 リソース・コントローラーは、プロビジョニング・レイヤーに対して実行されるアクションの認証および許可のために IAM を使用します。

### リソース・ライフサイクルの管理
{: #lifecycle}

リソース・コントローラーは、プロビジョニング (インスタンスの作成) からバインディング (アクセス資格情報の作成)、アンバインディング (アクセス権限の削除)、プロビジョニング解除 (インスタンスの削除) までのリソースのライフサイクルを制御するための一般的な API を提供します。

リソース・コントローラーには、リソース・ライフサイクルの以下の要素の管理に役立つ API が用意されています。
* プロビジョニング
* リソース・インスタンスの更新
* バインディング
* リソース・キー
* アンバインディング
* プロビジョニング解除


## リソースの管理
{: #resource-manager}


{{site.data.keyword.Bluemix_notm}} リソース・マネージャーは、[リソース・グループ](/docs/overview/resource-groups.html#whatis)によるリソースの収集を管理します。リソース・グループはアカウントに属します。すべての {{site.data.keyword.Bluemix_notm}} リソースをリソース・グループ内でプロビジョンする必要があります。アカウントが中断されると、対応するリソース・グループも中断され、リソース・グループ内のすべてのリソースが中断されます。ユーザーがアカウントを作成すると、アカウントにデフォルトのリソース・グループが作成されます。{{site.data.keyword.Bluemix_notm}} IAM 対応リソースはすべて、リソース・グループ内でプロビジョンする必要があります。アカウントが中断されると、対応するリソース・グループも中断され、リソース・グループ内のすべてのリソースが中断されます。標準アカウントの場合、ユーザーは 1 つのリソース・グループしか持つことができません。従量課金 (PAYG) アカウントまたはサブスクリプション・アカウントの場合、ユーザーは複数のリソース・グループを作成できます。 


## {{site.data.keyword.Bluemix_notm}} カタログ
{: #catalog}

{{site.data.keyword.Bluemix_notm}} カタログは、{{site.data.keyword.Bluemix_notm}} コンソールに表示されるリソースのオファリング定義 (説明、機能、イメージ、URL など) を保管します。 カタログ・サービスは、複数の地域にわたるオファリングを SoR (System of Record、定型業務処理システム) として管理します。カタログは、CLI および RESTful API をサポートします。この API では、既存のオファリングに関する情報を取得し、オファリングを作成、管理、および削除することができます。基本 URL から開始し、エンドポイントを使用してカタログ内のサービスに関するメタデータを取得し、サービスの可視性を管理します。オブジェクトの種類に応じて、メタデータには価格設定、プロビジョニング、地域などに関する情報を含めることができます。詳しくは、『[カタログ資料の管理](/docs/overview/catalog.html#global-catalog-overview)』を参照してください。

## リソースの検索とタグ付け
{: #search-and-tag}

検索サービスは、{{site.data.keyword.Bluemix_notm}} プラットフォーム内に統合されるグローバルの共有リソース・プロパティー・リポジトリーです。これは、クラウド・リソースの属性を保管および検索するために使用されます。これは、リソースをカテゴリー化して分類します。リソースは、{{site.data.keyword.Bluemix_notm}} プラットフォーム内のリソース・プロバイダー (Cloud Foundry、IBM Containers、またはリソース・コントローラーなど) によって制御および所有されます。リソースは、[クラウド・リソース名](/docs/overview/crn.html#crn) ID (CRN) によって一意的に識別されます。リソースのプロパティーには、タグとシステム・プロパティーが含まれます。どちらのプロパティーも {{site.data.keyword.Bluemix_notm}} 請求アカウント内で定義され、多くの地域にまたがっています。

このサービスは、リソースに関連付けられたタグも管理します。タグ付け API を使用して、タグの作成、削除、検索、添付、または切り離しを行うことができます。タグは、クラウド・リソース名 (CRN) ID によって一意的に識別されます。タグには名前があります。その名前は、請求アカウント内で固有でなければなりません。タグは、`key:value` の形式またはラベル形式で作成できます。

