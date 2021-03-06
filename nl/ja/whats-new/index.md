---

copyright:

  years: 2015, 2018

lastupdated: "2018-11-30"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# {{site.data.keyword.Bluemix_notm}} の新機能
{: #whatsnew}

{{site.data.keyword.Bluemix_notm}} エクスペリエンスを最大限に活用するために、{{site.data.keyword.Bluemix}} で利用可能な新しいフィーチャーおよびサービスについて常に最新情報を入手するようにしてください。 更新は、[{{site.data.keyword.Bluemix_notm}} プラットフォーム](index.html#platform_category) ([{{site.data.keyword.Bluemix_local_notm}} および {{site.data.keyword.Bluemix_dedicated_notm}}](index.html#dedicatedandlocal))、[コンピュート](index.html#compute_category)、および [サービス](index.html#services_category)のカテゴリーに編成されています。
{:shortdesc}

## {{site.data.keyword.Bluemix_notm}} プラットフォーム
{: #platform_category}


### {{site.data.keyword.Bluemix_notm}} の新しいサポート・エクスペリエンス
最新情報: 2018 年 11 月 30 日 
{: #support}

サポート・センターを使用して、{{site.data.keyword.Bluemix_notm}} に関連したすべての問題の解決に取り組むことができます。ランディング・ページには FAQ が用意されており、{{site.data.keyword.Bluemix_notm}} に連絡しなくても質問の答えを見つけることができます。また、ライブ・サポート担当員とチャットするオプションもあります。お客様の Case を単一の場所から管理できるようになりました。**「サポート」** &gt; **「Case の管理」**に移動して、Case を作成、表示、または編集します。

また、サポート・センターから[「状況」ページ ](https://cloud.ibm.com/status){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・リンク")を参照することもできます。このページは、{{site.data.keyword.Bluemix_notm}} のプラットフォーム、インフラストラクチャー、および主要サービスに影響を与える重要なイベントに関する計画外のインシデント、計画保守、告知、およびセキュリティー情報の通知をすべて組み込むように拡張されました。サポート・センターから**「クラウドの状況の表示」**をクリックします。この新しいエクスペリエンスを確認するには、ログインして[サポート・センター](https://cloud.ibm.com/unifiedsupport/supportcenter){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") にアクセスしてください。 

### {{site.data.keyword.Bluemix_notm}} での統合ログイン、API キー、およびユーザーとアクセスの管理
最新情報: 2018 年 11 月 30 日
{: #useraccess}

最新の更新により、ID タイプに関係なくすべてのユーザーが使用できる簡易セキュア・ログインを利用できるようになりました。IBM ID と SoftLayer ID のどちらを使用している場合でも、拡張ログイン・ページから {{site.data.keyword.Bluemix_notm}} コンソールに素早くログインできます。また、{{site.data.keyword.Bluemix_notm}} 全体でセキュアな API 呼び出しを行い、IAM API キーまたは IAM アクセス・トークンを使用して CLI ログインを自動化することもできます。 

ログインすると、「アクセス (IAM)」UI の「ユーザー」ページに、プラットフォームおよびクラシック・インフラストラクチャーのユーザーを含むすべてのユーザーが表示されるようになります。アカウント内の他のユーザーを表示するためのアクセス権限に応じて、アカウント・ユーザー、クラシック・インフラストラクチャーのユーザー、または Cloud Foundry 組織によってビューを素早くフィルターに掛けることができます。また、フィルターを使用して、名前、E メール、または状況で素早くユーザーを検索することもできます。

すべてのユーザーが単一のコンソールに表示されるようになったので、同じ場所からすべてのタイプのリソースへのアクセスを管理できます。アクセスはユーザーから開始されるため、最初にリストからユーザーを選択します。次に、アクセス権を割り当てるリソースのタイプに応じて、IAM アクセス・ポリシー、Cloud Foundry アクセス権限、またはクラシック・インフラストラクチャーの許可から選択できます。IAM アクセス・ポリシーを割り当てるだけの場合は、アクセス・グループを作成して、同じポリシーを割り当てる必要があるすべてのユーザーを同じアクセス・グループに追加することで、アクセス管理プロセスの簡素化を試行してください。

### すべての {{site.data.keyword.Bluemix_notm}} CLI プラグイン資料を 1 カ所で見つける
最新情報: 2018 年 11 月 30 日
{: #cli}

{{site.data.keyword.Bluemix_notm}} CLI プラグインのすべての資料に 1 カ所でアクセスできるようになり、{{site.data.keyword.Bluemix_notm}} プラットフォームで探している CLI コマンドを見つけやすくなりました。[CLI 資料](/docs/cli/index.html#overview)の『リファレンス』セクションを確認してください。

### 新しいダッシュボードとリソース・リストを確認する
最新情報: 2018 年 11 月 30 日
{: #dash}

最新の更新により、すべてのプラットフォームおよびインフラストラクチャーのサービスが同じ場所に表示されるようになりました。ログインすると、新しいダッシュボードをすぐに確認できます。カタログからアカウントにリソースを追加すると、リソース・リストを使用してアカウント・リソースの全体を表示できます。今回の変更に関する詳細の一部を以下に示します。

* ダッシュボードが再設計され、リソース、保守、状況、アプリケーション、サポート、使用状況、およびユーザーの要約を表示できるようになりました。
* リソース・リストでリソースのより詳細な情報を確認できるようになりました。リソースにタグを付けて編成したり、リソースを選択して詳細ページで変更を加えたりすることができます。
* すべてのリソースを 1 つの場所に表示できるようになったので、作成したリソースを素早く見つけてそれらを「リソース・リスト」ページに表示できるように、グローバル検索を追加しました。 
* カタログ結果を検索して、アカウントに追加するリソースを素早く見つけることもできます。  

### プラットフォームおよびインフラストラクチャーのサービスの統合アカウント、請求、およびユーザー・プロファイルの情報
最新情報: 2018 年 11 月 30 日
{: #profile}

アカウント、請求、およびプロファイルの情報が簡素化されました。統合されたコンソールで、すべてのプラットフォームおよびインフラストラクチャーのリソースのアカウント情報を表示できるようになりました。 

* プロファイルと設定の領域には、お客様に関する情報と、すべてのリソース・タイプの E メール通知設定が含まれています。 
* アカウント情報領域には、会社または組織に関する情報、アカウント設定、およびリソース・グループや Cloud Foundry 組織と連携するためのクイック・アクセスが含まれています。素早く稼働するのに役立つベスト・プラクティスを見つけることもできます。
* アカウントの「請求および使用量」領域は、請求の理解、支払いの実行、サブスクリプションのモニター、見積もりの取得、注文の追跡、および消費量通知の設定に役立ちます。

### タグによるリソースの編成
最新情報: 2018 年 11 月 30 日
{: #tag}

タグをクラウド・オブジェクト・ストレージなどのリソースに追加できるようになりました。これにより、リソースを管理し、最も関連性の高いリソースを見つけることができます。例えば、数百のリソースがあり、同じ方法で支払われるいくつかのリソースを区別する場合は、「costcenter: location01」でタグ付けできます。または、いくつかのリソースに対する作業を繰り返し行っているチームがある場合は、「team-blue」などを使用できます。タグによってリソース・リストをフィルタリングし、必要なリソースを素早く編成して見つけることもできます。詳しくは、『[タグの処理](/docs/resources/tagging_resources.html#tag)』を参照してください。

### コスト見積もりツールを使用した正確な月次コストの検出
最新情報: 2018 年 11 月 30 日
{: #cost-estimator}

購入するサービスを決定して分析するために、コスト見積もりツールを使用できます。これで、コンソールを使用して、必要な各サービスを選択し、使いやすいツールですべてのコストを追加できます。また、予想されるデータ使用量、1 秒当たりのルックアップ数、1 秒当たりの書き込み数、および 1 秒当たりの照会数を入力して、月次支出をより正確に見積もることもできます。選択した各カタログ・サービスでコスト見積もりツールを使用することも、コンソール・メニューの「コスト見積もりツール」アイコン ![「見積もりツール」アイコン](../../icons/Estimator.svg) をクリックして見積もりコストの要約を取得することもできます。詳しくは、[コストの見積もり](/docs/billing-usage/estimating_costs.html#cost)を参照してください。

### {{site.data.keyword.cloud_notm}} のグローバル・ロケーション名の更新
最新情報: 2018 年 11 月 1 日

{{site.data.keyword.cloud_notm}} のグローバルな使用可能地域が継続的に拡張されていることに伴って、世界中の地理、地域、およびデータ・センターから成る、理解しやすく一貫性のある階層をサポート強化するために、ロケーション命名構造が更新されることになりました。 現在のグローバル地域に慣れているユーザーは「米国南部」や「シドニー」といった名前で識別できますが、これらのロケーション名は、データ・センターが物理的に存在している都市の名前に変わります。

現時点では、プログラマチック ID は変更されないため、 API の観点からは影響はありません。 以下の表に、古いロケーション名と新しいロケーション名を示します。 データ・センターおよび地域の詳細および包括的リストについては、『[サービスの使用可能地域](/docs/resources/services_region.html)』を参照してください。

| 前のロケーション表示名 | 新しいロケーション表示名 | コード |
|----------|---------|---------|
| 米国南部 | ダラス | us-south | 
| 米国東部 | ワシントン DC | us-east |
| 英国 | ロンドン | eu-gb |
| ドイツ | フランクフルト | eu-de |
| シドニー | シドニー | au-syd |
| アジア太平洋北部 | 東京 | jp-tok |
{: caption="表 1. 新しいロケーション名" caption-side="top"}

### 他のユーザーへのアカウント管理アクセス権限の割り当て
最新情報: 2018 年 10 月 30 日

{{site.data.keyword.cloud_notm}} ID およびアクセス管理 (IAM) を使用して、アカウント管理者として実行する一般的な作業をアカウント内の別のユーザーに委任できます。 使用可能なアカウント管理サービスの 1 つまたはすべてでアクセス・ポリシーを作成することによって、ユーザーの招待と削除、アクセス・グループの管理、サービス ID の管理、プライベート・カタログ・サービスの保守、請求のモニターと使用量の追跡などの作業を簡単に委任できます。 以下のように、4 つの個別アカウント管理サービス・オプションと、すべてのサービスという 1 つのオプションがあり、これらをアクセス・ポリシーのセットアップに使用できます。

* ユーザーの招待と削除のためのユーザー管理
* アクセス権限の作成、編集、削除、更新、および割り当てのための IAM アクセス・グループ 
* アカウント全体のサービス ID および関連付けられた API キーへのアクセス権限の表示、作成、削除、および割り当てのための IAM Identity サービス
* プライベート・カタログ・オファリングの表示、およびオファリングのメタデータおよび可視性の更新のためのグローバル・リソース・カタログ
* 割り当てられた役割に基づいた個別アカウント管理サービス・オプションのそれぞれへのアクセス権限のため、および請求および使用量追跡へのアクセス権限のためのすべてのアカウント管理サービス


どのアカウント管理サービスについてのポリシーを持っているのか、およびどの役割が割り当てられているのかに応じてユーザーが実行できるタスクについて詳しくは、『[プラットフォーム管理の役割とアカウント管理サービスに対するアクションの例](/docs/iam/users_roles.html#platformrolestable2)』を参照してください。 この新機能について詳しくは、[Introducing More Flexibility and Control for IBM Cloud Account Management Services Access](https://www.ibm.com/blogs/bluemix/2018/11/introducing-more-flexibility-and-control-for-ibm-cloud-account-management-services-access/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") ブログ投稿を参照してください。 


### リソースの検索
最新情報: 2018 年 7 月 17 日

{{site.data.keyword.cloud_notm}} コンソール内の任意の場所からリソースを検索できます。 コンソールのメニュー・バーで検索フィールドにリソースの名前を入力します。 スラッシュ・キー (/) を押して、検索を有効にします。

### フェデレーテッド・ユーザーをアクセス・グループに動的に追加
最新情報: 2018 年 7 月 12 日

動的ルールを作成して、特定の ID 属性に基づいてフェデレーテッド・ユーザーをアクセス・グループに自動的に追加することができます。 ユーザーがフェデレーテッド ID を使用してログインすると、ID プロバイダーからのデータは、設定されたルールに基づいてユーザーをアクセス・グループに動的にマップします。 詳しくは、『[アクセス・グループの動的ルールの作成 (Creating dyanmic rules for access groups)](/docs/iam/accessgroup_rules.html#creating-dynamic-rules-for-access-groups)』を参照してください。

### サービス ID および API キーの保護
最新情報: 2018 年 6 月 1 日

サービス ID または API キーの削除が原因で停止または破壊が発生する状態を回避できるように、UI または CLI を使用してサービス ID および API キーをロックできるオプションがあります。 サービス ID をロックすることにより、アクセス・ポリシーの変更、削除、割り当てを防止することもでき、さらに、サービス ID と関連付けられた API キーの作成または削除を防止することもできます。 詳しくは、『[サービス ID のロック](/docs/iam/serviceid.html#locking-a-service-id)』および『[API キーのロック](/docs/iam/userid_keys.html#locking-an-api-key)』を参照してください。

### ライト・アカウントからサブスクリプション・アカウントへのアップグレード
最新情報: 2018 年 5 月 31 日

{{site.data.keyword.Bluemix_notm}} コンソールから直接、ライト・アカウントをサブスクリプション・アカウントにアップグレードできるようになりました。 サブスクリプション・アカウントを使用すると、プラットフォームとインフラストラクチャーの両方のオファリングを使用でき、月次支出額および期間を確約することによって割引価格を利用できます。 また、月次支払いスケジュールに基づく固定された請求処理によって予期しない請求を回避できる一方、ニーズに合わせて注文量を増減できる柔軟性もあります。 詳しくは、『[サブスクリプション・アカウントについての FAQ](/docs/billing-usage/billing-faq.html#subscription-faqs)』を参照してください。 

### {{site.data.keyword.Bluemix_notm}} CLI リブランディング
最新情報: 2018 年 5 月 15 日

{{site.data.keyword.Bluemix_notm}} CLI コマンドは `bluemix` および `bx` から **ibmcloud** に変更されました。 ただし、後日削除されるまで、`bluemix` および `bx` CLI コマンドを引き続き使用できます。 現時点では短縮名はなく、完全な名前 **ibmcloud** のみです。 

### {{site.data.keyword.Bluemix_notm}} アカウントでの多要素認証
最新情報: 2018 年 5 月 2 日

多要素認証 (MFA) ではアカウントにセキュリティーの層が 1 つ追加されて、すべてのユーザーが、ログイン中に標準 IBM ID およびパスワードに加えて、時間ベースのワンタイム・パスコードも入力することが必要になります。 これは、一般的に 2 要素認証 (2FA) とも呼ばれています。 MFA はアカウント単位で有効にされ、いったんオンにされると、そのアカウント内のすべてのユーザーは、追加セキュリティー手段を使用してログインすることが必要になります。

詳しくは、[IBM Cloud Platform now adds support for Multi-Factor Authentication](https://www.ibm.com/blogs/bluemix/2018/05/ibm-cloud-platform-now-adds-support-multi-factor-authentication/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") ブログ投稿を参照してください。

### アクセス・グループを使用した迅速なアクセス権限の割り当て
最新情報: 2018 年 4 月 3 日

可能な限り最小限のポリシーを使用してアクセス権限を素早く割り当てたい場合、 アクセス・グループを使用して行うことができるようになりました。 アクセス・グループを使用すると、ユーザーとサービス ID のセットをグループ化して、グループのすべてのメンバーに適用される単一のポリシーを割り当てることができます。 アクセス・グループを使用することで、アカウント内のユーザーとサービス ID へのアクセス権限の管理に費やす時間を抑えることができます。 詳しくは、「[New feature: Access groups](https://www.ibm.com/blogs/bluemix/2018/04/access-groups/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")」のブログ投稿を確認してください。

### SoftLayer アカウントと {{site.data.keyword.Bluemix_notm}} アカウントのリンク
最新情報: 2018 年 3 月 1 日

SoftLayer アカウントを {{site.data.keyword.Bluemix_notm}} アカウントとリンクして、単一のロケーションである {{site.data.keyword.Bluemix_notm}} コンソールにログインし、Infrastructure as a Service (IaaS) および Platform as a Service (PaaS) の両方のリソースにアクセスできます。 {{site.data.keyword.Bluemix_notm}} を初めて使用する場合、アカウントを作成してリンクすると、無料の {{site.data.keyword.Bluemix_notm}} ライト・アカウントを取得できます。 Paas リソースを含む {{site.data.keyword.Bluemix_notm}} アカウントをすでにお持ちの場合は、アカウントをリンクすることで、IaaS リソースおよび PaaS リソースの両方に関する請求を 1 つにまとめることができます。 アカウントを素早くリンクするには、[IaaS アカウントと PaaS アカウントをリンクする手順](https://www.ibm.com/blogs/bluemix/2018/03/follow-steps-link-iaas-paas-accounts/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")を確認してください。


### {{site.data.keyword.Bluemix_notm}} Foundry Service 米国東部地域が使用可能になりました。
最新情報: 2017 年 12 月 15 日

ワシントン D.C. で新しい米国東部データ・センターが使用可能になりました。 この新規の地域には、`us-east.bluemix.net` エンドポイント使用して到達できます。 この新規の地域で購入可能なサービスについて詳しくは、『[地域別のサービス](/docs/resources/services_region.html#services_region)』を参照してください。

### EU 内のリソースに関するサポート
最新情報: 2017 年 12 月 14 日

サービスおよびデータ・センターがヨーロッパ内にある場合、{{site.data.keyword.Bluemix_notm}} では、EU 内のデータを保護するための追加的な機能を提供するようになりました。 ヨーロッパにあるカスタマー・サクセス・チームによるサポートを依頼することができます。 このサポートは、24 時間 365 日利用可能です。 詳しくは、『[EU サポート対象オプションの有効化](/docs/billing-usage/eusupported.html#bill_eusupported)』および『[EU 内のリソースに関するサポートの依頼](/docs/get-support/howtogetsupport.html#eusupported)』を参照してください。

### TLS 1.0 および 1.1 のサポート終了
最新情報: 2017 年 11 月 28 日

{{site.data.keyword.Bluemix_notm}} は、2018 年 3 月 1 日付けで弊社のクラウド製品ならびにサービスの多くで TLS 1.0 および TLS 1.1 のサポートを終了します。これは、徹底してセキュアなクラウドを提供するための IBM の取り組みの一貫であり、セキュリティーおよびデータ・プライバシーに関する業界のベスト・プラクティスと歩調を合わせるためでもあります。 この変更による影響と、必要となる可能性のあるアクションについて詳しくは、『[TLS 1.0 および 1.1 のサポート終了](/docs/troubleshoot/appsectls.html)』を参照してください。

### アカウント内でリソースを編成する新しい方法
最新情報: 2017 年 11 月 16 日

リソース・グループは、アカウント・リソースのカスタマイズ可能なグループを作成するための新しい方法です。グループとその内部のリソースへのアクセスは、Identity and Access Management (IAM) を使用して管理されます。 すべてのユーザーがデフォルトのリソース・グループから作業を始めます。 このリソース・グループの名前を変更した上で、新規サービス・インスタンスをカタログから作成したときに、そのインスタンスをリソース・グループに追加できます。

従量課金 (PAYG) またはサブスクリプションのアカウントを持つユーザーの場合、追加のリソース・グループを作成して、 割り当て量の管理とリソース・セットの課金使用量の表示をさらに簡単に行うことができます。 また、リソースをグループにまとめて、複数サービスへのアクセス権限を一度に簡単にユーザーに割り当てられるようにすることも可能です。 自分のアカウント用のリソース・グループの処理について詳しくは、『[リソース・グループの管理](/docs/account/resourcegroups.html#rgs)』を参照してください。

### {{site.data.keyword.Bluemix_notm}} IAM の更新
最新情報: 2017 年 11 月 16 日

自分の {{site.data.keyword.Bluemix_notm}} アカウント内に[リソース・グループ](/docs/overview/resource-groups.html#whatis)を導入することで、アクセス権限を割り当てるための新しい方法を利用できるようになりました。 複数のユーザーおよびサービス ID にリソース・グループ内のすべてのサービスへのアクセス権を割り当てることができるため、複数リソースへのアクセス権限を一度に素早く割り当てることができます。 リソース・グループ内の一部のサービスのみへのアクセス権限を割り当てることによって、ユーザーまたはサービス ID ごとにアクセス権限をカスタマイズすることもできます。あるいは単に、サービス・インスタンス・レベルで個別のリソースへのアクセス権限を割り当てることを選択します。

IAM を使用して活用できる機能について詳しくは、『[Cloud IAM の機能にはどのようなものがありますか?](/docs/iam/index.html#features)』を参照してください。

### ダッシュボード・ビューのカスタマイズ
最新情報: 2017 年 11 月 16 日

アカウント内のすべてのリソースを {{site.data.keyword.Bluemix_notm}} コンソール内のダッシュボードから表示および管理できます。 また、フィルターを設定してビューをカスタマイズできるようになりました。 例えば、リソース・グループを基準にフィルター操作して、リソース・グループ内の特定のリソースを表示できます。 地域または Cloud Foundry スペースを基準にフィルター操作することもできます。 詳しくは、『[ダッシュボードでのリソースの管理](/docs/overview/ui.html#dashboardview)』を参照してください。


### サポート・センター
最新情報: 2017 年 11 月 2 日

情報を検索したり、開発者コミュニティーに質問を投稿したり、チケットを管理したりすることができる新しいサポート・センターができました。 {{site.data.keyword.Bluemix_notm}} コンソールのメニュー・バーで**「サポート」>「サポート・センター」**にアクセスしてください。

### IBM Cloud の導入
最新情報: 2017 年 10 月 31 日

Bluemix は IBM Cloud になりました。 新しい名前の発表のみで、変更はありません。 これまでのようにアプリとサービスを容易にビルドして実行できます。 詳しくは、[IBM Cloud ブログ](https://www.ibm.com/blogs/bluemix/2017/10/bluemix-is-now-ibm-cloud/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を確認してください。

### ライト・アカウント
最新情報: 2017 年 10 月 31 日

ライト・アカウントは、選択されたサービスを時間制限なく無料で試用するアクセス権限を付与する新しいアカウント・タイプです。 この新規アカウントには、使用量の追跡と効率的な利用のための機能が含まれ、リソースを管理しやすくしています。 使用可能な機能について詳しくは、『[アカウント・タイプ](/docs/account/index.html#liteaccount)』を参照してください。

### Identity and Access Management アプリケーション認証機能
最新情報: 2017 年 10 月 6 日

Identity and Access Management (IAM) では、サービス ID を作成する機能を提供するようになりました。サービス ID は、アプリが {{site.data.keyword.Bluemix_notm}} サービスでの認証に使用できる ID と考えることができます。 個人ユーザーの資格情報を使用する代わりに、関連付けられた API キーとアクセス許可を持つサービス ID を作成できます。API キーとアクセス許可は、その ID によって認証を行う任意のアプリケーションのアクセスのレベルを制御するためにサービス ID に割り当てられたサービス・ポリシーの形式となっています。

この機能のメリットと、使用を開始する方法について詳しくは、[Introducing IBM Cloud IAM Service IDs and API Keys](https://www.ibm.com/blogs/bluemix/2017/10/introducing-ibm-cloud-iam-service-ids-api-keys/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

### {{site.data.keyword.Bluemix_notm}} グローバル・カタログ
最新情報: 2017 年 7 月 27 日

{{site.data.keyword.Bluemix_notm}} は、コンソールの前回の更新でコンソール内の単一のロケーションからパブリック地域を管理するように拡張され、カタログから選択するアイテムの選択とデプロイのプロセスをさらに合理化するグローバル・カタログを含むようになりました。 コンソールで選択した地域にかかわらず、すべてのパブリック地域にわたって使用可能なすべてのサービスをカタログから表示できるようになりました。 カタログからタイルを選択すると、サービスを使用可能な地域を確認し、それをデプロイする場所を選択することができます。

カタログに対する最新の更新について詳しくは、[A global {{site.data.keyword.Bluemix_notm}} catalog makes building things easier](https://www.ibm.com/blogs/bluemix/2017/07/global-bluemix-catalog-makes-building-things-easier/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

### {{site.data.keyword.Bluemix_notm}} コンソールの更新
最新情報: 2017 年 5 月 23 日

更新された {{site.data.keyword.Bluemix_notm}} コンソールを通じて単一のロケーションからパブリック地域を管理できるようになりました。 地域セレクターにより、合理化された手順でリソースにアクセスでき、他にも可用性の向上やパフォーマンスの改善などの機能強化が加えられています。

この更新については、[New Global Bluemix UI for Higher Availability and More](https://www.ibm.com/blogs/bluemix/2017/05/new-global-bluemix-ui-higher-availability/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を確認してください。

### ID およびアクセス管理
最新情報: 2017 年 5 月 1 日

最新の更新および改善により、{{site.data.keyword.Bluemix_notm}} アカウント所有者または管理者は、新しい統一アクセス制御 UI を使用して、以下の機能を活用できるようになりました。
 * ユーザーが新しいアクセス制御機能を採用したときに、Kubernetes サービスやその他のサービスへのユーザーの微細化されたアクセス権限を管理する。
 * 組織内のユーザーにサービス・ポリシーおよび Cloud Foundry 役割を割り当てる。

さらに、{{site.data.keyword.Bluemix_notm}} プラットフォームのユーザーは、自分のユーザー ID に関連付けられた API キーを作成、削除、およびリストすることができます。 また、プラットフォーム・ユーザーは API または CLI を使用するときにそれらの API キーを使用して認証できます。

最後に、統一されたユーザー管理機能を拡張して、リンクされた IaaS-PaaS アカウントでユーザーが統一された方法で管理されるようにしており、SoftLayer カスタマー・ポータルまたは {{site.data.keyword.Bluemix_notm}} コンソールで別個にユーザーを追加する必要がありません。

最近の更新について詳しくは、 [Introducing Identity & Access Management](https://www.ibm.com/blogs/bluemix/2017/05/introducing-identity-access-management/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") というブログ投稿を確認してください。

### {{site.data.keyword.Bluemix_notm}} 資料のナビゲーション設計の変更
最新情報: 2017 年 4 月 13 日

このナビゲーションの更新によって、資料全体でコンテンツがどのように編成されているかが分かりやすくなり、関連コンテンツをより効率的に見つけることができるようになります。 コンテンツのネストされたレイヤーの数が減り、{{site.data.keyword.Bluemix_notm}} を活用するために必要な資料を見つけるために探し回る必要はなくなります。


## {{site.data.keyword.Bluemix_local_notm}} および {{site.data.keyword.Bluemix_dedicated_notm}}
{: #dedicatedandlocal}

### 管理コンソールについての 2 月の更新
{: #febadminconsole}
最新情報: 2018 年 2 月 28 日

2018 年 2 月の最新の更新により、以下の新しいフィーチャーを使用できるようになりました。

#### 保守更新を管理するための新たな権限

保守更新の承認およびスケジュール変更、さらには、専用環境に保守更新をデプロイできる期間を指定する保守更新期間のセットアップをユーザーが行えるようにするために、新しいユーザー権限が導入されました。
詳しくは、[ビデオ・デモンストレーション](https://youtu.be/7c7jyp_JJWU){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

### 管理コンソールについての 12 月の更新
{: #decemberadminconsole}
最新情報: 2017 年 12 月 14 日

12 月の最新の更新および改善により、以下の新しいフィーチャーを使用できるようになりました。

#### 平均 CPU 使用量しきい値の通知のサブスクライブ

通知サブスクリプションで、しきい値のタイプとして「平均 CPU」が追加されました。 CPU 使用量 (すべての DEA および Diego セルでの平均) が特定のしきい値を超えたかまたは下回ったときに通知を受け取ることができるようになりました。

#### EU 内のクラウド・システムへのアクセスの制御

管理コンソールは、クラウド・リソースをサポートする EU における新機能 (フランクフルトから始まる) と結合して、IBM 担当者によるアクセスを制御するポリシーを定義する機能を持つようになりました。 アクセス制御ポリシーを管理したり、アクセス要求を表示したり、要求に対してアクションをそれらを実行したり、履歴を追跡したりすることができます。

#### セキュリティー・レポート内の情報の拡張

セキュリティー・レポートには、ユーザーおよび組織の固有 ID に加えて、分かりやすい名前も含まれるようになりました。

### 管理コンソールについての 8 月の更新
{: #augustadminconsole}
最新情報: 2017 年 8 月 31 日

8 月の最新の更新および改善により、以下の新しいフィーチャーを使用できるようになりました。

#### {{site.data.keyword.cloudant_short_notm}} サービス使用メトリックに対する更新

  * {{site.data.keyword.cloudant_short_notm}} の使用メトリックの計算が、{{site.data.keyword.cloudant_short_notm}} クラスター内のすべてのノードにわたる使用 GB および使用可能 GB の合計量を反映するように更新されました。 通常、{{site.data.keyword.cloudant_short_notm}} クラスターには 3 つのノードが含まれ、高可用性および災害復旧のためにデータベース内の文書がクラスター内のすべてのノードで複製されます。 8 月の更新では、{{site.data.keyword.cloudant_short_notm}} ダイヤル (_「リソース使用量」>「サービス」_ビューで使用可能) 内の容量メトリックは、クラスター内のすべてのノードにわたるスペースを示します。 例えば、1 つの {{site.data.keyword.cloudant_short_notm}} クラスターが 3 つのノードで構成されていて、それぞれの容量が 1000 GB の場合、容量限度は 3000 GB となります。 その容量のうち 1500 GB が使用されている場合、{{site.data.keyword.cloudant_short_notm}} 使用メトリックは 50% になります。

#### 保守更新のスケジューリングに対する更新

  * {{site.data.keyword.Bluemix_dedicated_notm}} では、ご使用の専用環境をシステム更新のデプロイメントのために使用できる日時をお客様が管理できます。 お客様は、保守更新を専用環境にデプロイ可能な日時とデプロイ不可能な日時を表す、使用可能な時間枠を定義できます。 8 月の更新では、「_使用可能な更新ウィンドウ (Available Update Windows)_」は「_更新ウィンドウ_」という名前に変更され、「_使用不可の更新ウィンドウ (Unavailable Update Windows)_」は「_ブラックアウト・ウィンドウ_」という名前に変更されました。 用語が変更されただけではなく、お客様がブラックアウト (使用不可) の日付を定義する際の柔軟性とマージンが大きくなりました。 要求されたブラックアウト日は IBM の承認が必要であり、承認を得るために要する時間は変動します。 要求したブラックアウト日が承認された場合、IBM は選択不可の期間中に現在スケジュールされている既存の更新を取り消します。 さらに IBM は、これらの更新用に新たなレコードを作成し、承認されたブラックアウト日以外の期間に更新をスケジュールします。

詳しくは、[ビデオ・デモンストレーション](https://bit.ly/2eCQNvu){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

### 管理コンソールについての 7 月の更新
{: #julyadminconsole}
最新情報: 2017 年 7 月 31 日

7 月の最新の更新および改善により、以下の新しいフィーチャーを使用できるようになりました。

#### リソース使用量履歴機能に対する更新

  * 前回の更新 (6 月) では、メモリーおよびディスクの使用量の「履歴」ビューで、直近の 48 時間、30 日間、および 5 カ月間の使用量データの表示を導入しました。 この最新の 7 月の更新では、リソース使用量データを表示する対象期間をカスタマイズできるように、リソース使用量履歴機能が拡張されました。 毎時、日時、月次のビューは残りますが、メモリーとディスクの使用量メトリックを表示する開始日時と期間をユーザーが指定できるようになりました (例えば、2017 年 7 月 1 日からの 15 日間のメモリー使用量を表示します)。
  * CLI でリソース・メトリック履歴を表示する新規 CLI コマンドが導入されました。 `_cf ba resource-metrics-history -help_` と入力すると、このコマンドのパラメーターと使用法の例が表示されます。

詳しくは、[ビデオ・デモンストレーション](https://youtu.be/QBij0jB5qAk){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

### 管理コンソールについての 6 月の更新
{: #juneadminconsole}
最新情報: 2017 年 6 月 26 日

6 月の最新の更新および改善により、以下の新しいフィーチャーを使用できるようになりました。

#### 「リソース使用量」ページに対する更新

  * システム・リソース
    * メモリーおよびディスクの使用量の「履歴」ビューは、48 時間、30 日間、および 5 カ月間のデータを表示するように更新されました。
    * 「履歴」ビューを生成するために管理コンソールのメトリック API がどのように使用されるかを示す「詳細はこちら」リンクが用意されています。
  * アプリケーション
    * 環境内のすべてのアプリケーションの使用量情報を提供します。
    * アプリケーション名、物理メモリー、予約済みメモリー、物理ディスク、予約済みディスク、物理 CPU、または組織名によってソートします。
    * アプリケーション名および組織名によって結果をフィルター操作するための検索機能が提供されています。
    * 「アプリケーション」ビューを生成するために管理コンソールのメトリック API がどのように使用されるかを示す「詳細はこちら」リンクが用意されています。

詳しくは、『[リソース使用量](/docs/hybrid/index.html#resourceusage)』を参照してください。

#### メトリックの API に対する更新

  * 環境統計が追加されました。メモリーおよびディスクの消費量について日ごとまたは月ごとの平均を提供します。

詳しくは、『[メトリックの API](/docs/hybrid/index.html#envappmetricsapi)』を参照してください。


### 管理コンソールについての 5 月の更新
{: #mayadminconsole}
最新情報: 2017 年 5 月 30 日

5 月の最新の更新および改善により、以下の新しいフィーチャーを使用できるようになりました。

 * 「状況」ページが改善され、{{site.data.keyword.Bluemix_notm}} プラットフォームおよびランタイムに影響するインシデントに関してよりきめ細かい診断が含まれるようになりました。
 * セキュリティーの「レポートおよびログ」ページの改善:
   * レポートは表形式で表示されるようになりました。レポートの表示と検索を単純化し、レポート・カテゴリー、ファイル名、または作成日によってソートできるようになっています。
   * フィルター操作が機能拡張され、複数のカテゴリーの同時フィルター操作が含まれるようになりました。
   * レポートの内容を表示するためのフルスクリーン・モード。
   * 「レポート書き込み」権限を持つ管理ユーザーのためのレポートを削除する機能。
   * レポート・リストの表示を高速化。連続スクロールによってオンデマンドで順次ロードし、全体的なパフォーマンスを向上させます。
 * セキュリティー・レポートは、要求の時点から最大で 3 カ月前にさかのぼった時点から開始して、1 週間までの時間範囲内について、オンデマンドで要求できます。 管理ユーザーがこの機能を使用できるようにするためには、事前にいくつかの環境固有の構成を行う必要があることに注意してください。 管理ユーザーは、この機能を使用するために「レポート書き込み」権限が必要です。

### 管理コンソールについての 4 月の更新
{: #apriladminconsole}
最新情報: 2017 年 5 月 2 日

4 月の最新の更新および改善により、以下の新しいフィーチャーを使用できるようになりました。

 * {{site.data.keyword.Bluemix_notm}} 専用環境およびローカル環境用に新たに設計された状況アプリ。 コンポーネント名またはポストの日付によって素早く検索できます。 状況ページにポストされた個別のコンポーネント状況の更新の表示と、環境に固有の通知の間で切り替えることもできます。 詳しくは、[New {{site.data.keyword.Bluemix_notm}} Status Page](https://www.ibm.com/blogs/bluemix/2017/05/new-bluemix-status-page/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") というブログ投稿を参照してください。
 * 選択されたサービスについて、「リソース使用量」タイルからサービス使用量データ。 どのサービスがサポートされているか、および新規ビューで何ができるかについて詳しくは、『[サービス使用量の詳細](/docs/hybrid/index.html#servicesresourceusage)』を参照してください。

## コンピュート
{: #compute_category}

### 仮想サーバーのフィーチャー
最新情報: 2018 年 11 月 16 日

{{site.data.keyword.BluVirtServers_full}} オファリングでは、現在、以下のフィーチャーが使用可能です。

#### インスタンスを使用していないときの請求一時停止
使用した分のみの支払いを希望する場合、 仮想サーバー・インスタンスに対する請求を一時停止できるようになりました。 請求一時停止フィーチャーは、SAN バッキング・ストレージを使用する、時間単位のパブリック・フレーバー・サイズを持つ仮想サーバー・インスタンスで使用可能です。 請求一時停止フィーチャーがサポートされている仮想サーバーの電源を切ると、一定のコンピュート・リソースについてはコストが発生しません。 サーバーの電源が切られると請求は自動的に停止します。 請求一時停止フィーチャーにより、コストが削減され、仮想サーバーのリソースが再び必要になったときに仮想サーバーを再プロビジョンする必要がなくなります。 詳しくは、『[請求一時停止について](/docs/vsi/vsi_about_suspend.html)』または {{site.data.keyword.cloud_notm}} [ブログ投稿![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")](https://www.ibm.com/blogs/bluemix/2018/10/suspend-billing-1-minute-granularity-virtual-servers/){: new_window}を参照してください。

#### 将来の仮想サーバー・インスタンス用のリソースの予約
{{site.data.keyword.BluVirtServers_full}} の予約済みインスタンス・オファリングが利用可能になりました。 これは、将来のデプロイメントおよびコスト削減のために保証されたリソースが必要な場合に適しています。 予約済み容量の 1 年または 3 年の契約条件のいずれかを選択します。 その予約済み容量内で、特定のサイズの最大 20 個の仮想サーバー・インスタンスのセットを予約し、必要に応じてそれらのインスタンスをプロビジョンすることができます。 この容量は、契約条件の有効期間中、選択した POD およびデータ・センター内で保証されます。 詳しくは、『[予約済み仮想サーバー](/docs/vsi/vsi_about_reserved.html)』を参照してください。

#### {{site.data.keyword.cos_full_notm}} サービス・インスタンスから {{site.data.keyword.cloud_notm}} インフラストラクチャーへのイメージのインポート
{{site.data.keyword.cloud_notm}} インフラストラクチャーは、{{site.data.keyword.cloud_notm}} コンソールでプロビジョンされた {{site.data.keyword.cos_full_notm}} サービスと対話するようになりました。 {{site.data.keyword.cos_full_notm}} は、大容量のイメージのアップロードに必要な時間を大幅に短縮する Aspera 高速転送プラグインを提供します。 イメージが {{site.data.keyword.cos_full_notm}} にアップロードされたら、{{site.data.keyword.cos_full_notm}} から {{site.data.keyword.cloud_notm}} インフラストラクチャーに[イメージをインポート](/docs/infrastructure/image-templates/import-image.html)できます。 {{site.data.keyword.cloud_notm}} インフラストラクチャーから {{site.data.keyword.cos_full_notm}} に[イメージをエクスポート](/docs/infrastructure/image-templates/export-image-ibm-cos.html)することもできます。

#### 仮想サーバー・インスタンスの配置グループ
{{site.data.keyword.BluVirtServers_full}} で配置グループが使用可能になりました。 配置グループがあれば、パブリック・インスタンスを使用してデータ・センター内で高可用性を構築したり、より大規模なデプロイメント内で追加レベルのフォールト・トレランスを提供したりできます。 詳しくは、『[配置グループ](/docs/vsi/vsi_placegroup.html)』を参照してください。 

### ビルドパックの最新の更新

最新の更新の累積リストについては、以下のページにアクセスしてください。

* [SDK for Node.js ビルドパックに対する最新の更新](/docs/runtimes/nodejs/updates.html#latest_updates)
* [Liberty ビルドパックに対する最新の更新](/docs/runtimes/liberty/updates.html#latest_updates)
* [ASP.NET Core ビルドパックに対する最新の更新](/docs/runtimes/dotnet/updates.html#latest_updates)
* [IBM XPages for {{site.data.keyword.Bluemix_notm}} ビルドパックに対する最新の更新 (Latest updates to the IBM XPages for {{site.data.keyword.Bluemix_notm}} buildpack)](/docs/starters/xpages/index.html#updates)

### {{site.data.keyword.containerlong_notm}} の最新の更新

{{site.data.keyword.containerlong_notm}} は、2017 年 5 月に Kubernetes アーキテクチャーを立ち上げました。 単一およびスケーラブルなコンテナー・グループの以前のアーキテクチャーは、[2017年 12 月 5 日の時点で完全に非推奨](https://www.ibm.com/blogs/bluemix/2017/07/deprecation-single-scalable-group-container-service-bluemix-public/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") になりました。  

[{{site.data.keyword.Bluemix_notm}}](/docs/containers/container_index.html) でのネイティブ Kubernetes 環境の使用開始については、資料を参照してください。 質問がある場合は、Slack (https://ibm-container-service.slack.com/) に投稿することができます。


### {{site.data.keyword.containerlong_notm}} に高可用性 Kubernetes マスターが付属するようになりました
最新情報: 2018 年 11 月 7 日

新しい高可用性 Kubernetes マスターのフィーチャーを使用して、クラスターの可用性をさらに高めることができます。 高可用性 Kubernetes マスターは、Kubernetes API サーバー、etcd、Kubernetes スケジューラー、およびコントローラーの複数のレプリカを使用してセットアップされ、すべて別々の物理ホストに分散されます。 Kubernetes バージョン 1.12、1.11、または 1.10 を実行するクラスターを作成すると、Kubernetes マスターはデフォルトで高可用性にセットアップされます。 これらの Kubernetes バージョンのいずれかを実行する既存のクラスターでこのフィーチャーを有効にするには、[準備ステップ](/docs/containers/cs_versions.html#110_ha-masters)を実行する必要があります。

### {{site.data.keyword.containerlong_notm}} でのマルチゾーン・クラスターの作成
最新情報: 2018 年 7 月 10 日

クラスターとアプリの可用性を改善したい場合、 選択したメトロ領域内の複数のゾーンにクラスターを広げることができるようになりました。 詳しくは、『[IBM Bluemix Container Service でのマルチゾーン・クラスターの作成 (Creating multizone clusters in {{site.data.keyword.containershort_notm}})](cs_clusters.html#multizone)』を参照してください。

### {{site.data.keyword.containerlong_notm}} での Kubernetes Dashboard アクセス
最新情報: 2018 年 4 月 18 日

{{site.data.keyword.Bluemix_notm}} コンソールを介した Kubernetes Dashboard への直接アクセスが {{site.data.keyword.containerlong_notm}} でサポートされるようになりました。 ダッシュボードへのパスがこのように単純になったことにより、クラスター管理およびリソース可視化についてのユーザー・エクスペリエンスが強化されます。 詳しくは、[{{site.data.keyword.Bluemix_notm}} ブログ ](https://www.ibm.com/blogs/bluemix/2018/04/kubernetes-dashboard-access/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。


### 新しい Liberty for Java ビルドパック v3.11
最新情報: 2017 年 7 月 17 日

Liberty ビルドパック v3.11 は、新規の月次の Liberty ランタイム・バージョンを提供し、その他の改善も含んでいます。 月次の Liberty ランタイム・バージョンは  [2017.7.0.0](https://developer.ibm.com/wasdev/blog/2017/07/07/beta-websphere-liberty-tools-july-2017/) リリースに更新されました。 IBM JDK は 8.0.4.7 バージョンおよび 7.1.4.5 バージョンに更新されました。 このビルドパックは、アプリ管理ユーティリティーおよび Auto-Scaling エージェントの更新されたバージョンも提供します。 デフォルトの Cloudant ライブラリーが公式の  [java-cloudant](https://github.com/cloudant/java-cloudant) になりました。[Ektorp ライブラリー](https://github.com/helun/Ektorp)は、オプションとして引き続き使用可能です。この変更について詳しくは、[ブログ投稿](https://www.ibm.com/blogs/bluemix/2017/05/default-library-change-cloudant-auto-wiring-liberty-buildpack/)を参照してください。 アプリケーションのメモリーが 512 MB 未満の場合、デフォルトのヒープ・サイズ率は 50 % となりました。512 MB よりも多い場合は引き続き 75 % です。新しいステージング・タスク・ログが生成されるようになり、これによりステージング・エラーのデバッグが容易になります。追加情報については、[最新の更新](https://console.ng.bluemix.net/docs/runtimes/liberty/updates.html)の資料を参照してください。

### 新しい Liberty for Java ビルドパック v3.10
最新情報: 2017 年 6 月 12 日

Liberty ビルドパック v3.10 は、新規の四半期ごとおよび月次の Liberty ランタイム・バージョンを提供し、その他の改善も含んでいます。 デフォルトの Liberty ランタイム・バージョンは 17.0.0.2 に更新されました。 月次の Liberty ランタイム・バージョンは  [2017.5.0.0](https://developer.ibm.com/wasdev/blog/2017/05/12/beta-websphere-liberty-tools-may-2017/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") リリースに更新されました。 このビルドパックは、アプリ管理ユーティリティーおよび Extreme Scale Client の更新されたバージョンも提供します。 追加情報については、[最新の更新](/docs/runtimes/liberty/updates.html)の資料を参照してください。

### 新しい SDK for Node.js ビルドパック v3.12
最新情報: 2017 年 5 月 16 日

SDK for Node.js ビルドパック v3.12 は、IBM SDK for Node.js バージョン 0.12.17、0.12.18、4.8.0、4.8.2、6.10.0、および 6.10.2 を提供します。 デフォルトは、最新の 4.x から最新の 6.x に変更されたため、現在は 6.10.2 です。 これはメジャー・バージョンの変更であるため、デフォルトに依存するアプリに影響する可能性があります。 問題がある場合にそれらを回避する方法について詳しくは、[Node.js version long-term support and the SDK for Node.js buildpack](https://www.ibm.com/blogs/bluemix/2016/11/node-version-support-and-sdk-buildpack/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

新規ランタイムに加えて、このリリースには、アプリ管理ヘルス・センター・ハンドラーおよび Node.js バージョン 6.9.5 および 6.10.0での問題のビルドパック・バグ修正が含まれています。

### 新しい Liberty for Java ビルドパック v3.9
最新情報: 2017 年 4 月 27 日

Liberty ビルドパック v3.9 は、新規の月次の Liberty ランタイム・バージョンを提供し、その他の改善も含んでいます。 デフォルトの Liberty ランタイム・バージョンは、PI77770、PI77605、IFPI77438、および IFPI79275 の iFix を含むように更新されました。 月次の Liberty ランタイム・バージョンは  [2017.3.0.0](https://developer.ibm.com/wasdev/blog/2017/03/14/beta-websphere-liberty-tools-march-2017/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") リリースに更新されました。 メモリー計算は、ステージングから開始プロセスに移動されました。これによりアプリケーションの再始動の際のヒープ・メモリー変更が容易になります。 このビルドパックは、Auto-Scaling サービス・エージェントおよび Extreme Scale Client の更新されたバージョンも提供します。 追加情報については、[最新の更新](/docs/runtimes/liberty/updates.html)の資料を参照してください。

## サービス
{: #services_category}

### Citrix NetScaler VPX バージョン 12.1
最新情報: 2018 年 11 月 21 日
{: #vpx121}

#### 複数の IP アドレスを持つ仮想サーバー
複数の連続しない/連続する VIP IPv4 アドレスと IPv6 アドレスを持つ単一のロード・バランシング仮想サーバーを作成できるようになりました。仮想サーバーにバインドされた各 VIP アドレスは、個別の仮想サーバーとして扱われます。

この機能について詳しくは、Citrix の記事『[Multiple IP virtual servers ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")](https://docs.citrix.com/en-us/netscaler/12-1/load-balancing/load-balancing-customizing/multi-ip-virtual-servers.html){: new_window}』を参照してください。

#### SSL
SSL 接続に以下の更新が適用されました。
 
* DEFAULT_BACKEND 暗号グループからの脆弱な暗号の削除。 
* Thales nShield® 外部 HSM のフロントエンドでの ECDHE 暗号のサポート
* SafeNet ネットワーク外部 HSM のフロントエンドでの ECDHE 暗号のサポート
* SSLv2 の削除: NetScaler VPX アプライアンスは、リリース 12.1 以降 SSLv2 をサポートしません。

12.1 SSL 更新について詳しくは、『[Citrix 12.1 Release Notes ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")](https://docs.citrix.com/en-us/netscaler/12-1/downloads/release-notes-12-1-48-13.html){: new_window}』を参照してください。

#### GSLB のサービス・グループ・サポート
GSLB の IP アドレス・ベースのサービス・グループ、ドメイン名ベースのサービス・グループ、またはドメイン名ベースの自動スケーリング・サービス・グループを構成できるようになりました。また、サービスのグループを 1 つのサービスと同等に簡単に管理したり、サービス・グループを仮想サーバーにバインドしたり、サービスをグループに追加したりすることもできます。

GSLB サービス・グループについて詳しくは、Citrix の記事『[Configuring a GSLB service group ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")](https://docs.citrix.com/en-us/netscaler/12/global-server-load-balancing/configure/configuring-a-gslb-service-group.html){: new_window}』を参照してください。


### {{site.data.keyword.conversationshort}} の主要な更新
最新情報: 2018 年 11 月 9 日

{{site.data.keyword.conversationshort}} の外観が新しくなり、フィーチャーが追加されました。 *ワークスペース*と呼ばれる成果物 (チャット・ボットを強化する機械学習モデルのトレーニング・データのコンテナー) は、*ダイアログ・スキル*に置き換えられました。 ダイアログ・スキルをアシスタントに追加することで、デプロイが容易になりました。 新しいアシスタント層は、ユーザーとスキルの間のメッセージのオーケストレーションを管理します。 組み込み統合をアシスタントに追加して、最小限の労力で一般的なメッセージング・チャネルにダイアログ・スキルを公開できます。 {{site.data.keyword.conversationshort}} の資料は、新しい場所に移動しました。 詳しくは、[製品資料](/docs/services/assistant/index.html)を参照してください。


### Terraform および Ansible を使用したインフラストラクチャーおよびアプリのデプロイメントの自動化
最新情報: 2018 年 11 月 2 日

Terraform および Ansible は、クラウド・ソリューションのデプロイメントを最初から最後まで自動化するために使用できるオープン・ソース・ソフトウェアです。 Terraform を使用すると、{{site.data.keyword.Bluemix_notm}} インフラストラクチャー・コンポーネントを指定することができ、層が複数ある複雑なクラウド環境を素早く構築して Infrastructure as Code (IaC) を使用可能にすることができます。 その後、Ansible を使用して、プライベート・ネットワークを介してコンピュート・ホストに接続し、アプリのデプロイ、サービスのビルド、スクリプトの実行、または構成の定義を行います。 

まず各オープン・ソース製品の基本について学習するために、以下のチュートリアルを参照してください。 
* [Deploying RedHat OpenShift Container Platform on {{site.data.keyword.Bluemix_notm}} with Terraform](/docs/terraform/tutorials/install_redhat_openshift.html#redhat){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")
* [Deploying WordPress on IBM Cloud infrastructure with Terraform and Ansible](/docs/terraform/tutorials/wordpress_with_terraform_and_ansible.html#deploy_wordpress){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") 

### {{site.data.keyword.cloudant_short_notm}} の最新の更新
最新情報: 2018 年 9 月 28 日

{{site.data.keyword.cloudant_short_notm}} に対する[最新の更新](/docs/services/Cloudant/release_info/release_notes.html#release-notes){:new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")の包括的なリストについては、以下のページにアクセスしてください。

### {{site.data.keyword.IBM_notm}} {{site.data.keyword.DRA_short}} 一般出荷可能日の紹介
最新情報: 2018 年 9 月 20 日

{{site.data.keyword.DRA_short}} サービスは、現在、米国南部、ドイツ、および英国地域で一般出荷可能です。

{{site.data.keyword.DRA_short}} は、チームの生産性、効率性、および製品化までの時間について改善し、DevOps ツールのデータを使用して、簡単に成果を測ったり、コードの品質を向上させたりするのに役立ちます。 このサービスは、すべてのコードベースおよびチーム全体にわたって企業の DevOps 活動を理解するための単一のツールを提供します。

* **スピード**: {{site.data.keyword.DRA_short}} では、すべてのアプリケーションにわたるすべての分析が 1 つのダッシュボードに表示されます。
* **品質**: ゲート・デプロイメント・ポリシーを実装することで、リリースのリスクを軽減します。 例えば、コード・カバレッジのポリシーがある場合、選択された許容範囲で、{{site.data.keyword.DRA_short}} は、定義された許容範囲を満たさないコードのリリースを常にゲートで阻止します。 これらのポリシーは、時間の経過とともに、デプロイメント・プロセスの全体的な品質を向上させるのに役立ちます。 
* **制御**: コード・カバレッジ、単体テスト、およびその他のツールを使用して、DevOps の慣例の傾向に対応しながら、チームは時間をかけて結果を測定します。 これらの傾向を観察して、チームは DevOps の慣例をより良く制御することができます。

### {{site.data.keyword.security-advisor_long_notm}} は、ベータ版になりました。
最新情報: 2018 年 9 月 5 日

{{site.data.keyword.security-advisor_short}} に新しい機能が追加され、ベータ版サービスとして使用できるようになりました。  {{site.data.keyword.security-advisor_short}} は、{{site.data.keyword.Bluemix_notm}} のセキュリティーを 1 つのダッシュボードに一元化します。 情報の一元化に加えて、サービスにより、セキュリティー問題が検出されたときに重要なセキュリティー情報をナビゲートしやすいタイルに要約して明確に表示されます。 タイルをクリックしてドリルダウンすると、優先順位付けの問題、履歴、および警告の背後にある詳細を調べることができます。 問題を修正するには、単にもう一度ドリルダウンして詳細を確認し、脅威を取り除くために推奨されるフィックスをすべて取得して、環境が安全に保たれるようにします。

{{site.data.keyword.security-advisor_short}} は即座に制御をコンソールに移し、セキュリティーを {{site.data.keyword.Bluemix_notm}} 環境で一元的に表示および管理できるようにします。

このリリースでは、以下が実装されています。
* 検索 API
* 独自のプロバイダーを持ち込む能力
* ダッシュボード・エクスペリエンスの更新

まだ他にもあります。

開始するには、[{{site.data.keyword.security-advisor_short}} 資料](/docs/services/security-advisor/index.html)を参照してください。

### {{site.data.keyword.iva_full_notm}} 一般出荷可能日の紹介
最新情報: 2018 年 6 月 26 日

[{{site.data.keyword.iva_full}}](https://console.bluemix.net/catalog/services/voice-agent-with-watson)![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") が一般出荷可能になりました。 顧客が電話で通話したり話しかけたりすることができる、Watson サービスをベースとするコグニティブ・ボイス・エージェントを作成できます。 バックボーンに Watson の人工知能があるため、ボイス・エージェントは会話のようにコミュニケーションすることができ、ボイス・エージェント内で複雑な対話を処理したり顧客の通話を解決したりすることができます。

このリリースでは、以下の新機能が導入されています。

* 災害復旧のために予備の Watson サービス・ロケーションを追加する。 
* ボイス・エージェントによる通話の転送、事前録音された発信者へのメッセージの再生、Watson サービスとの対話を行う方法をカスタマイズするために、拡張構成オプションを編集する。
* 標準サービス・プランで最大同時接続の数を構成する。
* NetFoundry、Twilio、AT&T などの SIP トランキング・プロバイダーやその他のサービス・プロバイダーにボイス・エージェントを接続したり、{{site.data.keyword.iva_short}} とのピアを行ったりする。

まず、『[{{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html)』の資料を参照してください。

### {{site.data.keyword.streaminganalyticsshort}} で、コンテナー・ベースのインフラストラクチャーを使用する新しいサービス・プランが導入されました
最新情報: 2018 年 4 月 20 日

{{site.data.keyword.streaminganalyticsshort}} は、Kubernetes コンテナー・ベースのインフラストラクチャーで稼働するようになり、これによって、このサービスのセキュリティーおよび可用性が高まります。
 
この新しいコンテナー・ベースのインフラストラクチャーには [v2 サービス・プラン](/docs/services/StreamingAnalytics/service_plans.html#service_plans)を使用してアクセスできます。 行う必要のある作業に最も適した {{site.data.keyword.streaminganalyticsshort}} プランを選択できます。 v2 サービス・プランに含まれる機能拡張を以下に示します。
 
* [IBM Streams QSE with Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi)![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン"): Docker 環境で稼働する新しい Streams QSE (RHEL 7 上) を使用して、新しい {{site.data.keyword.streaminganalyticsshort}} v2 プランでアプリケーションをコンパイルおよびデプロイする方法については、[ Development Guide](https://developer.ibm.com/streamsdev/docs/cloud-beta-devguide/)![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。 
* [{{site.data.keyword.streaminganalyticsshort}} v2 REST API](https://console.bluemix.net/apidocs/1939-streaming-analytics-v2#introduction)![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")
* [新しいスターターおよびサンプル・アプリケーション](https://developer.ibm.com/streamsdev/docs/cloud-beta-samples/) ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")
* [{{site.data.keyword.streaminganalyticsshort}} サービスへのハイ・アベイラビリティー機能拡張](/docs/services/StreamingAnalytics/c_ha.html#consistent-regions)
* [Problem determination features in the {{site.data.keyword.streaminganalyticsshort}} service](https://developer.ibm.com/streamsdev/2018/02/15/streaming-analytics-console-gives-ways-find-fix-errors-beta-plans/)![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")
* [Monitoring how operators behave and guaranteed tuple processing in the cloud](https://developer.ibm.com/streamsdev/2018/02/15/monitor-operators-behave-ensure-resource-optimization/)![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")

### {{site.data.keyword.iva_full_notm}} は、現在ベータになりました。
最新情報: 2018 年 3 月 16 日

[{{site.data.keyword.iva_full}}](https://console.bluemix.net/catalog/services/voice-agent-with-watson)![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を使用すると、顧客が電話で通話したり話しかけたりすることができる、Watson サービスをベースとするコグニティブ・ボイス・エージェントを作成できます。 バックボーンに Watson の人工知能があるため、ボイス・エージェントは会話のようにコミュニケーションすることができ、ボイス・エージェント内で複雑な対話を処理したり顧客の通話を解決したりすることができます。

このベータ版には、以下の主要機能が用意されています。

* ボイス・エージェントと必要なすべての Watson サービスを単一ステップで作成し、今まで以上に簡単に開始する。
* ボイス・エージェントから人間のコンタクト・センター・エージェントまたはその他の宛先にコールを転送する。
* 発着信詳細記録、転記、および {{site.data.keyword.conversationshort}} によって {{site.data.keyword.cloudant_short_notm}} データベースに変換されたイベントを転送するようにボイス・エージェントを構成し、コール・データを収集および分析する。
* 新しい「_使用量_」ページでサービス使用量をモニターし、コール・ログを表示する。 今月の簡単な統計の表示、コール・ログの検索とフィルター、個々のコールのシステム・メッセージの表示などを行うことができます。
* ポート 5061 上で SIP TLS (SIP URI)、および Secure Real-Time Transport Protocol (SRTP) を使用して、メディア暗号化でセキュアなコールを確立する。
* より高い柔軟性を得るために、他の {{site.data.keyword.cloud_notm}} スペース内の {{site.data.keyword.speechtotextfull}} サービス・インスタンスおよび {{site.data.keyword.texttospeechfull}} サービス・インスタンスに接続する。

まず、『[{{site.data.keyword.iva_short}}](/docs/services/voice-agent/getting-started.html)』の資料を参照してください。

### {{site.data.keyword.visualrecognitionshort}} に対する更新
最新情報: 2018 年 3 月 14 日

ディープラーニングのニューラル・ネット・ベースの種別として、新規の「カスタム種別」モデル・トレーニングが生成されるように、{{site.data.keyword.visualrecognitionfull}} サービスは更新されました。 これらのディープラーニング・モデルを生成するために必要な追加の計算では、新規モデルのトレーニングのために追加の時間が必要になることがあります。

現在、既存のカスタム種別を引き続き更新およびリトレーニングすることができ、このディープラーニングの新しいマシン・モデル・フォーマットに対しては更新されません。

### {{site.data.keyword.streaminganalyticsshort}} の更新
最新情報: 2018 年 2 月 14 日

[{{site.data.keyword.streaminganalyticsshort}} サービス](https://console.bluemix.net/catalog/services/streaming-analytics){: new_window}![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")内のコンソールの [ベータ - エントリー・プランおよびベータ - エンハンスト・プラン](/docs/services/StreamingAnalytics/beta_plans.html#beta_plans)には、いくつかの機能拡張が含まれています。

* [新しい IBM Streams QSE for Docker](https://www-01.ibm.com/marketing/iwm/iwm/web/preLogin.do?source=swg-ibmistvi){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン"): 新しい Streams QSE を、 Docker 環境で稼働する RHEL 7 と共に使用し、新しい {{site.data.keyword.streaminganalyticsshort}} ベータ・プランでアプリケーションをコンパイルおよびデプロイする方法については、『[Beta Development Guide](https://developer.ibm.com/streamsdev/docs/cloud-beta-devguide/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")』を確認してください。
* [{{site.data.keyword.streaminganalyticsshort}} v2 REST API](https://console.bluemix.net/apidocs/1939-streaming-analytics-v2#introduction){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")
* [新しいスターターおよびサンプル・アプリケーション](https://developer.ibm.com/streamsdev/docs/cloud-beta-samples/)
* [{{site.data.keyword.streaminganalyticsshort}} サービスへのハイ・アベイラビリティー機能拡張](/docs/services/StreamingAnalytics/consistentregions.html#consistentregions)
* [New problem determination features in the beta version of the {{site.data.keyword.streaminganalyticsshort}} service](https://developer.ibm.com/streamsdev/2018/02/15/streaming-analytics-console-gives-ways-find-fix-errors-beta-plans/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")
* [Monitoring how operators behave and guaranteed tuple processing in the cloud](https://developer.ibm.com/streamsdev/2018/02/15/monitor-operators-behave-ensure-resource-optimization/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")

### {{site.data.keyword.keymanagementservicelong_notm}} をシドニー地域に拡張
最新情報: 2018 年 1 月 31 日

本日付けで、{{site.data.keyword.keymanagementserviceshort}} 暗号鍵管理サービスは、シドニー地域で利用可能になります。 シドニーは、{{site.data.keyword.keymanagementserviceshort}} ユーザーに GA ステータスを提供する、米国南部 (ダラス) およびロンドンに次いで 3 つ目の地域です。

{{site.data.keyword.keymanagementserviceshort}} は、{{site.data.keyword.Bluemix_notm}} に保管されているデータの暗号化に使用される鍵を管理するためのシンプルで経済的な鍵管理ソリューションを提供する暗号鍵管理サービスです。 {{site.data.keyword.keymanagementserviceshort}} は、鍵の作成から、アプリケーションの使用、鍵のアーカイブ、および鍵の破壊に至るまでの鍵の全ライフサイクルを管理し、同時に、データ管理と鍵管理の職務の分離を実施します。

{{site.data.keyword.keymanagementserviceshort}} は、利用可能な IBM データ・サービスで、BYOK (Bring-Your-Own-Key – お客様が管理する暗号化) をサポートしています。 BYOK によって、内部で作成されたマスター・ルートオブトラスト暗号鍵をユーザーがインポートできるようにし、{{site.data.keyword.Bluemix_notm}} に保存されている Data at Rest のセキュリティーを管理しやすくします。


### {{site.data.keyword.containershort_notm}}: Kubernetes 1.8.x のサポート
最新情報: 2018 年 1 月 19 日

2017 年 11 月以降、{{site.data.keyword.containershort_notm}} は Kubernetes `1.8.x` をサポートしてきました。 Kubernetes のデフォルト・バージョンが `1.8.6` になったことをご案内します。  近い将来、`1.9.x` のサポートを提供する予定です。

### Watson Discovery Visual Insights
最新情報: 2017 年 11 月 30 日

エンティティー、関係、概念などの、テキスト内で検出された意味的要素を {{site.data.keyword.discoveryshort}} が理解することにより視覚的に接続を探索します。

すぐに使用可能な {{site.data.keyword.discoveryshort}} News コレクションによって、世界のニュースの探索を開始します。 あるいは、{{site.data.keyword.discoveryshort}} で自分自身の文書コレクションを探索します。 自分の {{site.data.keyword.Bluemix_notm}} 資格情報を使用して単にログインしてください。 詳しくは、[Visual insights experimental](https://visual-insights.bluemix.net){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

### 新しい IBM Cloud Managed Database Server ベータ版サービス
最新情報: 2017 年 11 月 30 日

新しい IBM Cloud Managed Database Server ベータ版サービスを使用して、{{site.data.keyword.Bluemix_notm}} 上で Microsoft SQL サーバーのインスタンスを作成できます。 この SQL サーバー・インスタンスは、任意のデータベース管理システムを使用するのとまったく同じように使用できますが、ハードウェアのセットアップおよびソフトウェアのインストールと保守の労力とコストが不要です。

このサービスには、以下の特徴があります。
* Microsoft SQL サーバー・バージョン 2012、2014、および 2016 の Enterprise Edition と Standard Edition から選択可能
* アプリケーション・ワークロード要件を満たすさまざまな事前定義構成またはサイズ
* モニタリング、パッチ適用、バックアップ、レポート作成を含め、IBM が完全に管理

使用を開始するには、『[IBM Cloud Managed Database Server の概説 (Getting started with IBM Cloud Managed Database Server)](/docs/services/managed-sql-server/getting-started.html)』を参照してください。

### {{site.data.keyword.mobilepushshort}} の新機能
最新情報: 2017 年 10 月 26 日

これまでの数カ月間に、{{site.data.keyword.mobilepushshort}} サービスに対していくつかの機能拡張を行いました。 このサービスは、ダラス、ロンドン、シドニーと共に、フランクフルト地域でも使用可能になりました。 機能拡張の詳細を以下に示します。

#### モニタリング
特定の期間のプッシュ通知のパフォーマンスを追跡したり、送信された通知の数や登録されたデバイスの総数を追跡したりすることができるようになりました。 Web フックを登録して、通知のライフサイクル内のすべてのイベントについて通知を受け取ることもできます。 詳細については、以下の資料のリンクとブログ投稿で参照できます。
* [通知のモニター](/docs/services/mobilepush/push_monitoring.html#push_monitoring)
* [Web フック・イベントに関するアラートの受信](/docs/services/mobilepush/push_webhook.html#webhook_event_based_notifications)
* [Monitoring in IBM Push Notifications](https://www.ibm.com/blogs/bluemix/2017/03/monitoring-ibm-push-notifications/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")

#### Web 通知
Web 通知用に、Firefox、Chrome、Chrome App and Extensions と共に Safari Web ブラウザーをサポートするようになりました。 Web SDK および関連情報については、[IBM Bluemix Push Notifications Web SDK](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-javascript-webpush/blob/Doc/README.md){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

#### 最新の Android 通知および iOS 通知
iOS 11 通知のサポートがあります。 また、iOS10 および Android N からのいくつかの新しい通知関連の機能拡張も取り込みました。

* iOS10 – リッチ・メディア通知、イメージ、対話式通知におけるボタンおよびマップ、ローカライズされたストリングのサポート
* Android N – 拡張可能な通知、対話式通知およびサイレント通知、LED ライト設定

追加の詳細については、『[リッチ・メディア通知](/docs/services/mobilepush/push_step_4_nf_rich.html#interactive-notifications)』、『[対話式通知とサイレント通知](/docs/services/mobilepush/push_step_4_nf_interactive.html#interactive-notifications)』、および『[拡張プッシュ通知の使用可能化](/docs/services/mobilepush/push_step_4_nf_adv.html#enabling-advanced-push-notifications)』を参照してください。

#### APNS HTTP/2 のサポート
Apple は、Apple 通知用に HTTP プロトコルのサポートを導入しました。 {{site.data.keyword.mobilepushshort}} サービスは、HTTP/2 プロトコルをサポートするようになりました。 このサポートにより、通知のペイロードを 4 KB とすることができ、スループットが向上します。また、即時フィードバック機能を提供します。 ユニバーサル証明書のサポートにより、アプリがサンドボックスと実稼働環境の両方に接続できます。

#### 新規ライト・プラン
{{site.data.keyword.mobilepushshort}} サービスのライト・プランでは、毎月 10 万件の通知を無料で送信できます。 詳しくは、[Lite Plan For Push Notifications Service on Bluemix](https://www.ibm.com/blogs/bluemix/2017/06/lite-plan-push-notifications-service-bluemix/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") というブログ投稿を参照してください。



### Mobile Analytics の新機能
最新情報: 2017 年 10 月 26 日

これまでの数カ月間に、{{site.data.keyword.mobileanalytics_short}} サービスに対して機能拡張を行いました。 このサービスは、ダラスおよびロンドンと共に、フランクフルトおよびシドニー地域でも使用可能になりました。 機能拡張の詳細を以下に示します。

#### Web SDK サポート
{{site.data.keyword.mobileanalytics_short}} は、Web アプリ分析のサポートを追加した Omni チャネル・サービスになりました。 詳細については、[https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/](https://github.com/ibm-bluemix-mobile-services/bms-clientsdk-web-analytics/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") で参照できます。

#### {{site.data.keyword.mobilefoundation_short}} サービスとの統合
{{site.data.keyword.mobilefoundation_short}} サービスは、アプリ、ユーザー、およびパフォーマンスの分析に {{site.data.keyword.mobileanalytics_short}} サービスを活用するようになりました。 ユーザーは、DB2 ウェアハウスへのエクスポート・オプションを利用して、アダプター分析およびカスタム図表を作成できます。 追加の詳細が以下のブログ投稿に記載されています。

* [Mobile Foundation Service integration with Mobile Analytics Service](https://www.ibm.com/blogs/bluemix/2017/08/mobile-foundation-service-integration-mobile-analytics-service-2/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")
* [Building custom charts using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/custom-charts-using-analytics-and-dashdb-analytics-service/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")
* [Building charts for Adapter analytics using IBM Bluemix Mobile Analytics service and IBM Mobile Foundation Service](https://mobilefirstplatform.ibmcloud.com/blog/2017/04/26/adapter-analytics-using-analytics-and-dashdb-analytics-service/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")

#### {{site.data.keyword.mobilefirst_notm}} ボイラープレートには、{{site.data.keyword.mobileanalytics_short}} が含まれるようになりました。
モバイル・サービス・ボイラープレートは、ユーザーが素早く使用を開始できるように一連のモバイル・サービスを提供するテンプレートです。 {{site.data.keyword.mobileanalytics_short}} サービスは、[カタログ](https://console.bluemix.net/catalog/starters/mobilefirst-services-starter){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") で提供されているボイラープレートの一部になりました。


### {{site.data.keyword.streaminganalyticsshort}} の更新
最新情報: 2017 年 10 月 20 日

* IBM Streams Runner for Apache Beam: Streams 開発環境内でローカルに Beam アプリケーションを開発してから、それらのアプリを {{site.data.keyword.Bluemix_notm}} 内の {{site.data.keyword.streaminganalyticsshort}} サービスに送信できるようになりました。 IBM Streams Runner for Apache Beam は、Streams 環境で Beam パイプラインを実行します。 Streams Runner を使用して起動された Beam アプリケーションは、Streams Application Bundle (SAB) ファイルに変換されます。その後そのファイルを {{site.data.keyword.streaminganalyticsshort}} にデプロイできます。 詳しくは、 『[Streaming Analytics での IBM Streams Runner for Apache Beam](/docs/services/StreamingAnalytics/gs_beamrunner.html)』を確認してください。
* さらに速くログ・ファイルから情報を見つけることができます。 コンソールは、Python または Java トポロジーのアプリケーション・グラフの表示を改善するように更新されました。 [Enhancements to the Console](https://developer.ibm.com/streamsdev/2017/10/13/enhancements-to-the-console/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

### IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services
最新情報: 2017 年 10 月 12 日

IBM App Launch for {{site.data.keyword.Bluemix_notm}} Services は、オーディエンスのさまざまな統計サンプルにわたって的を絞ったエンゲージメントを作成するためのプラットフォームを提供することにより、カスタマー・エクスペリエンスを測定できるようにする試験的なオファリングです。 App Launch サービスは、エンゲージメントの成果として顧客選好および課題に関する洞察を提供し、カスタマー・エクスペリエンスをより良くするようにアプリをパーソナライズするために役立ちます。

アプリ所有者は、リリース・サイクルの複雑さを避けることにより、モバイル・アプリへの革新的技術の導入を加速できるようになりました。 App Launch サービスを使用すると、アプリ所有者は、急速にモバイル・アプリの機能を立ち上げることができ、ターゲット・オーディエンスを制御することで影響を測定できます。 アプリ所有者は、アプリ開発者と連携してその機能の重要業績評価指標を定義し、影響を測定し、リアルタイムのフィードバックに基づいて機能のロールアウトとロールバックを決定することができます。 このサービスにより、アプリケーション機能、ユーザー・インターフェース・コンポーネント、およびメッセージの複数のバリアントをテストし、フィードバックに基づいて決定を下すこともできます。

詳しくは、『[入門チュートリアル](/docs/services/app-launch/index.html#gettingstartedtemplate)』を参照してください。

### {{site.data.keyword.ibmwatson_notm}} {{site.data.keyword.relationshipextractionshort}} に対する更新
最新情報: 2017 年 10 月 4 日

{{site.data.keyword.relationshipextractionshort}} により、新しいカスタマイズ機能および新しい言語モデルが使用可能です。 新しい言語は、WKS 用のオランダ語、韓国語、および中国語 (簡体字) のサポートです。

### {{site.data.keyword.containerlong_notm}} クラスターの更新
最新情報: 2017 年 9 月 20 日

ご使用のクラスターを、{{site.data.keyword.Bluemix_notm}} 内の Kubernetes の最新の使用可能なバージョンに更新できるようになりました。 GUI または CLI のいずれかを使用して、Kubernetes マスター・ノードおよびワーカー・ノードを Kubernetes 1.7 に更新し、新しい機能とパッチを活用してください。

詳しくは、[Kubernetes 1.7 available in {{site.data.keyword.containerlong_notm}}](https://www.ibm.com/blogs/bluemix/2017/09/kubernetes-1-7-available-ibm-bluemix-container-service/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を確認してください。

### IBM Voice Agent with Watson の新しい試験的サービス
最新情報: 2017 年 9 月 15 日

新しい {{site.data.keyword.iva_full}} の試験的サービスを使用すると、顧客が電話で通話したり話しかけたりすることができる、Watson サービスをベースとするコグニティブ・ボイス・エージェントを作成できます。 バックボーンに Watson の人工知能があるため、ボイス・エージェントは会話のようにコミュニケーションすることができ、ボイス・エージェント内で複雑な対話を処理したり顧客の通話を解決したりすることができます。

{{site.data.keyword.iva_short}} は、Watson {{site.data.keyword.speechtotextshort}}、{{site.data.keyword.conversationshort}}、および {{site.data.keyword.texttospeechshort}} サービスに接続し、それらのオーケストレーションを行って、自然言語の会話をシミュレートします。 各ボイス・エージェントは、同時に複数の通話を処理するように自動的にスケーリングします。 この試験的リリースでは、以下の主な機能を使用してボイス・エージェントをカスタマイズできます。

* 手始めとしてサンプル {{site.data.keyword.conversationshort}} ダイアログをインポートしてから、自社のニーズに適合する独自のダイアログを作成する。
* IBM の API を使用して、{{site.data.keyword.conversationshort}} サービス内からボイス・エージェントの振る舞いをプログラミングする。 バージイン動作から、ダイアログ内の任意のノードの通話の中止まで、あらゆるものを制御します。
* 異なるトピック用に専門化されたコグニティブ・エージェントごとに異なる電話番号を接続したい場合に、複数のボイス・エージェントを容易に作成して管理する。
* サード・パーティーの API を使用できるようにサービス・オーケストレーション・エンジン (SOE) を接続することによって、サービスの機能を拡張する。 例えば、SOE は {{site.data.keyword.conversationshort}} サービスからのトリガーを listen してから、用意された API を使用して既存のシステム内の情報を検索するか、他の分析を提供することができます。

使用を開始するには、『[{{site.data.keyword.iva_short}}の概説 (Getting started with {{site.data.keyword.iva_short}})](/docs/services/voice-agent/getting-started.html)』を参照してください。


### {{site.data.keyword.streaminganalyticsshort}} サービスの更新: コンソールには、アプリケーション内の問題を特定するための新しい方法が含まれています。
最新情報: 2017 年 8 月 14 日

Python および Java アプリケーションの場合、ソース・ファイルのロケーションは @spl_note アノテーションに基づいて表示されます。

詳細については、[Latest improvements to the {{site.data.keyword.streaminganalyticsshort}}](https://developer.ibm.com/streamsdev/2017/08/14/latest-improvements-streaming-analytics-console/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

### IBM Cloud Monitoring が英国地域でも使用可能になりました
最新情報: 2017 年 8 月 1 日

{{site.data.keyword.monitoringlong}} サービスを使用して、メトリックを処理する際の {{site.data.keyword.Bluemix_notm}} での収集、保存、および分析の各機能を拡張します。

* アラートの実行。 {{site.data.keyword.monitoringlong}} は、パフォーマンスしきい値を設定し、それらのしきい値を超えたら通知を送信するために使用できる API を提供しています。 単一のサービス・インスタンスまたはアプリ・インスタンスのアラート・ルール、および一連のインスタンスについて報告するアラート・ルールを定義します。 アラートがトリガーされると、E メール、PagerDuty イベント、Web フック通知、またはそれら 3 つの任意の組み合わせで通知を受け取ります。

* カスタム・メトリックの追加。 {{site.data.keyword.monitoringlong}} プレミアム・プランは、関連するアプリケーションおよびビジネスのメトリックを Cloud Monitoring データに追加するために使用できる API を提供しています。 また、それらの API を使用して、{{site.data.keyword.IBM_notm}} Cloud の外部から {{site.data.keyword.monitoringlong}} サービスにメトリック・データを送信することもできます。

* 再使用可能なダッシュボードを構築し、それらを対話式にする。 {{site.data.keyword.monitoringlong}} でホストされている Grafana は、多数の視覚化オプションによりカスタム・ダッシュボードの構築をサポートします。  変数を含むメトリック照会を使用したテンプレート作成により、ダッシュボードを動的にします。

* {{site.data.keyword.Bluemix_notm}} カタログを介してサービスにアクセスする。 {{site.data.keyword.monitoringlong}} は、{{site.data.keyword.Bluemix_notm}} カタログの DevOps セクション内のサービス・タイルとして使用可能です。  単一コンテナーおよびグループ・コンテナーを持つ {{site.data.keyword.containershort}} サービスの場合、{{site.data.keyword.Bluemix_notm}} UI からサービスにアクセスできます。

* ニーズに応じたサービス・プランの選択。 使用ニーズに適合するように、ライト・サービス・プランまたはプレミアム・サービス・プランを選択できます。 ライト・プランでは、毎分 1 回のメトリック収集、15 日間の保存、および補助的アラートが提供されます。  代わりにプレミアム・プランを選択すると、より多くの消費量とより長いメトリック保存が可能になり、さらに、サービス API にアクセスして {{site.data.keyword.monitoringlong}} サービスからメトリックを送信したり検索したりできるようになります。 {{site.data.keyword.monitoringlong}} は、毎分 1 回のメトリック収集を提供します。  ライト・プランは、メトリックを完全な分解能で 15 日間保存します。 プレミアム・プランは、メトリックを完全な分解能で 45 日間保持します。

従来の {{site.data.keyword.monitoringshort}} サービスによるメトリック収集頻度は、サービスで定義された30 秒から始まり、時間が経過すると 1 時間の頻度にまとめていました。 {{site.data.keyword.monitoringlong}} は、完全な分解能の収集を 1 分単位とするようになりました。  ライト・プランは、メトリックを 15 日間保存します。  プレミアム・プランは、メトリックを 45 日間保持します。

{{site.data.keyword.monitoringlong}} サービスについて詳しくは、[Monitoring の概説の資料](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring)または [the IBM Cloud Monitoring – Service Refresh with New Features![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/) を参照してください。


### IBM Cloud Log Analysis が米国南部地域で使用可能になりました
最新情報: 2017 年 7 月 31 日

{{site.data.keyword.loganalysisfull}} サービスは、{{site.data.keyword.Bluemix_notm}} プラットフォーム用のログ収集サービスとログ検索サービスを提供し、アプリケーションおよび {{site.data.keyword.Bluemix_notm}} サービスのデータを、選択した {{site.data.keyword.Bluemix_notm}} サービスから自動的に収集します。 {{site.data.keyword.loganalysisshort}} サービスを使用して、以下のようにすることができます。

* 必要とする限りログを保持する。  

    ログは IBM Cloud ストレージに保管されます。  ログは、必要に応じてダウンロードできます。

* 新規 API を使用して、保持されたログを管理し、{{site.data.keyword.IBM_notm}} Cloud の外部からログ・データを送信する。

* 1 日当たりに検索可能なログの量を選択する。  

    1 日当たり最大 500MB、2GB、5GB、および 10GB のログ検索に使用できるさまざまなプランがあります。

* 再使用可能なダッシュボードを構築し、それらを対話式にする。

    {{site.data.keyword.loganalysisshort}} がホストする Kibana は、カスタム・ダッシュボード作成のサポートを提供します。

* {{site.data.keyword.Bluemix_notm}} カタログを介してサービスにアクセスする。  

    単一コンテナーおよびグループ・コンテナーを持つ {{site.data.keyword.loganalysisshort}} サービスと、{{site.data.keyword.IBM_notm}} Cloud Foundry サービスの場合、{{site.data.keyword.Bluemix_notm}} UI からサービスにアクセスできます。

{{site.data.keyword.loganalysisshort}} サービスについて詳しくは、『[{{site.data.keyword.loganalysisfull}} の概説 (Getting started with {{site.data.keyword.loganalysisfull}})](/docs/services/CloudLogAnalysis/index.html#getting-started-with-ibm-cloud-log-analysis)』および 『[{{site.data.keyword.loganalysisshort}}の概要 ({{site.data.keyword.loganalysisshort}} overview)](/docs/services/CloudLogAnalysis/log_analysis_ov.html#log_analysis_ov)』を参照してください。

### Virtual Router Appliance 用の Brocade オペレーティング・システムのバージョン 18.x
最新情報: 2018 年 7 月 25 日

Brocade OS のバージョン 18.x が Virtual Router Appliance で使用可能になりました。 数ある新しいフィーチャーの中で、このバージョンは Spectre セキュリティー・ブリーチの修復を提供します。 

18.x VRA の新しいフィーチャーは、以下のトピックで説明されています。

* [ゾーン・ファイアウォールと連動する IPsec トンネルのセットアップ方法 (How to Set up an IPsec Tunnel that Works with Zone Firewalls)](/docs/infrastructure/virtual-router-appliance/vra-ipsec.html)
* [IPsec およびゾーン・ファイアウォールを使用した VFP インターフェースの構成 (Configuring a VFP interface with IPsec and Zone Firewalls)](/docs/infrastructure/virtual-router-appliance/vra-vfp.html)
* [接頭部ベースの IPsec での NAT の使用 (Using NAT with prefix based IPsec)](/docs/infrastructure/virtual-router-appliance/vra-nat.html)
* [VFP インターフェースのトラブルシューティング (Troubleshooting Your VFP Interface)](/docs/infrastructure/virtual-router-appliance/vra-vfp-troubleshooting.html)

Vyatta 5400 からマイグレーションする場合、18.x にアップグレードする最良の方法は、完全な OS 再ロードの[通常の手順](/docs/infrastructure/virtual-router-appliance/upgrade-os.html)を実行することです。

Vyatta 5400 と Virtual Router Appliance の間には、機能の単純な 1 対 1 のマッピングがないため、VRA 用のベースライン構成を作成すると役立ちます。 IBM のパートナーである WanClouds から、このプロセスに関する支援を受けることができ、VRA での Vyatta 5400 に類似した機能の作成についての案内も受けられます。

このアップグレード・プロセス中に発生する一般的な問題について詳しくは、[追加資料](/docs/infrastructure/virtual-router-appliance/migration-issues.html#vyatta-5400-common-migration-issues)を参照してください。

### IBM dashDB for Analytics の名前が変更されました
最新情報: 2017 年 7 月 18 日

以下の表に、新しい名前をまとめています。

| 以前の名前               | 新しい名前                   | 発効日 |
|-----------------------------|----------------------------|----------------|
| IBM dashDB for Analytics    | IBM Db2 Warehouse on Cloud | 2017 年 7 月 18 日  |
{: caption="表 1. サービス名の変更" caption-side="top"}

Db2 Warehouse on Cloud および Db2 on Cloud の更新の累積リストについては、 [What's New in Db2 Warehouse on Cloud and Db2 on Cloud](http://www.ibm.com/support/docview.wss?uid=swg21961758){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

### IBM Cloud Monitoring が米国南部地域で使用可能になりました
最新情報: 2017 年 7 月 17 日

{{site.data.keyword.monitoringlong}} サービスを使用して、メトリックを処理する際の {{site.data.keyword.Bluemix_notm}} での収集、保存、および分析の各機能を拡張します。

* アラートの実行。 {{site.data.keyword.monitoringlong}} は、パフォーマンスしきい値を設定し、それらのしきい値を超えたら通知を送信するために使用できる API を提供しています。 単一のサービス・インスタンスまたはアプリ・インスタンスのアラート・ルール、および一連のインスタンスについて報告するアラート・ルールを定義します。 アラートがトリガーされると、E メール、PagerDuty イベント、Web フック通知、またはそれら 3 つの任意の組み合わせで通知を受け取ります。

* カスタム・メトリックの追加。 {{site.data.keyword.monitoringlong}} プレミアム・プランは、関連するアプリケーションおよびビジネスのメトリックを Cloud Monitoring データに追加するために使用できる API を提供しています。 また、それらの API を使用して、{{site.data.keyword.IBM_notm}} Cloud の外部から {{site.data.keyword.monitoringlong}} サービスにメトリック・データを送信することもできます。

* 再使用可能なダッシュボードを構築し、それらを対話式にする。 {{site.data.keyword.monitoringlong}} でホストされている Grafana は、多数の視覚化オプションによりカスタム・ダッシュボードの構築をサポートします。  変数を含むメトリック照会を使用したテンプレート作成により、ダッシュボードを動的にします。

* {{site.data.keyword.Bluemix_notm}} カタログを介してサービスにアクセスする。 {{site.data.keyword.monitoringlong}} は、{{site.data.keyword.Bluemix_notm}} カタログの DevOps セクション内のサービス・タイルとして使用可能です。  単一コンテナーおよびグループ・コンテナーを持つ {{site.data.keyword.containershort}} サービスの場合、{{site.data.keyword.Bluemix_notm}} UI からサービスにアクセスできます。

* ニーズに応じたサービス・プランの選択。 使用ニーズに適合するように、ライト・サービス・プランまたはプレミアム・サービス・プランを選択できます。 ライト・プランでは、毎分 1 回のメトリック収集、15 日間の保存、および補助的アラートが提供されます。  代わりにプレミアム・プランを選択すると、より多くの消費量とより長いメトリック保存が可能になり、さらに、サービス API にアクセスして {{site.data.keyword.monitoringlong}} サービスからメトリックを送信したり検索したりできるようになります。 {{site.data.keyword.monitoringlong}} は、毎分 1 回のメトリック収集を提供します。  ライト・プランは、メトリックを完全な分解能で 15 日間保存します。 プレミアム・プランは、メトリックを完全な分解能で 45 日間保持します。

従来の {{site.data.keyword.monitoringshort}} サービスによるメトリック収集頻度は、サービスで定義された30 秒から始まり、時間が経過すると 1 時間の頻度にまとめていました。 {{site.data.keyword.monitoringlong}} は、完全な分解能の収集を 1 分単位とするようになりました。  ライト・プランは、メトリックを 15 日間保存します。  プレミアム・プランは、メトリックを 45 日間保持します。

{{site.data.keyword.monitoringlong}} サービスについて詳しくは、[Monitoring の概説の資料](/docs/services/cloud-monitoring/index.html#getting-started-with-ibm-cloud-monitoring)または [the IBM Cloud Monitoring – Service Refresh with New Features![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")](https://www.ibm.com/blogs/bluemix/2017/07/ibm-cloud-monitoring-service-refresh-new-features/) を参照してください。

### {{site.data.keyword.contdelivery_short}} のアップグレード
最新情報: 2017 年 7 月 11 日

アップグレードのメリットには、バグ修正、パフォーマンスの向上、ユーザー・エクスペリエンスの改良が含まれます。 特筆すべき機能拡張としては、以下のものが挙げられます (ご使用の環境にまだ存在しない場合)。
<ul>
<li>国際化対応およびアクセシビリティーに対するフィックスおよび改善。</li>
<li>ツールチェーンの「管理」タブから使用可能なツールチェーン・アクセス制御。</li>
<li>Continuous Delivery ツール・カタログ内の新規ツール統合。</li>
<li>Orion Web IDE 内の複数ワークスペースのグループ化の改善。</li>
<li>Orion Web IDE 内の複数エディター・タブのサポート。</li>
<li>Orion Web IDE 内の UI テーマのサポート。</li>
</ul>

### {{site.data.keyword.uccr_short}} ベータ
最新情報: 2017 年 6 月 23 日

{{site.data.keyword.uccr_short}} は、クラウド・ネイティブおよびオンプレミスの両方のデプロイメント・ツールをサポートするエンタープライズ規模のリリース管理ソリューションです。

{{site.data.keyword.uccr_short}} のベータ版には以下の主要機能が用意されています。
* リリースを使用して、複数のデプロイメント・プランおよびイベントを管理し、複数チームのリリース作業でコラボレーションする。
* リリース関連アクティビティーのイベントを作成し、カレンダーでそれらを管理する。
* 独自のイベントおよびリリースをインポートする。
* 組織に適合するようにカレンダー・イベントをカスタマイズする。
* リリース通知に E メールおよび Slack タイプのタスクを使用する。

### dashDB for Transactions から {{site.data.keyword.Db2Hosted_notm}} に名前を変更しました
最新情報: 2017 年 6 月 14 日

IBM {{site.data.keyword.DB2OnCloud_short}} は、dashDB for Transactions の新しい名前です。 この名前変更の一環として、以前の自己管理型 IBM {{site.data.keyword.DB2OnCloud_short}} サービスも、名前が IBM Db2 Hosted に変更されました。 現時点では表示名のみが更新されているため、API やコマンド・ライン・インターフェースはすべて変わっていません。

### {{site.data.keyword.sparks}} の更新: Stocator-S3 コネクターに IBM Cloud Object Storage Cross Region サービスのサポートが含まれる (ベータ)
最新情報: 2017 年 6 月 5 日

{{site.data.keyword.sparks}} ユーザーは、IBM Cloud Object Storage Cross Region サービスで保管されたデータにアクセスし、それに対する分析を実行できるようになりました。 この機能はベータとして提供されます。 IBM Cloud Object Storage は、分析やその他のアプリケーション用に、スケーラブルかつ柔軟で、シンプルで使いやすく費用効率の高い大容量ストレージを提供します。

Apache Spark は、Stocator テクノロジーに基づいたストレージ・コネクターを通じて IBM Cloud Object Storage データにアクセスします。このコネクターは、暗黙的にオブジェクト・ストレージ向けに設計されているため、従来型のオブジェクト・ストレージ・コネクターよりも高速です。 ユーザーが、Apache Spark コードを変更したり再コンパイルしたりする必要はありません。

[Access and Analyze data in IBM Cross Region Cloud Object Storage](https://www.ibm.com/blogs/bluemix/2017/06/access-analyze-data-ibm-cross-region-cloud-object-storage/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") というブログ投稿で、{{site.data.keyword.Bluemix_notm}} および IBM Data Science Experience (DSx) 上での {{site.data.keyword.sparks}} を用いた IBM Cloud Object Storage データの使用法について説明しています。

ご質問またはご意見がある場合は、[sparksrv@us.ibm.com](sparksrv@us.ibm.com) にご連絡ください。 ご遠慮なくフィードバックをお寄せください。

### {{site.data.keyword.dashdbshort_notm}} for Transactions で新しいスケーラブル・プランが使用可能になりました
最新情報: 2017 年 5 月 31 日

データベースのニーズに応じて拡大できる新規プランを、{{site.data.keyword.dashdbshort}} for Transactions で使用できます。 新しい Flex プランでは、小規模なシステムから始めて、そのシステムの能力とストレージ容量を容易に素早く拡張することができます。 {{site.data.keyword.dashdbshort}} for Transactions は、DB2 と 100% の互換性があり、高可用性プランでは 99.95% の SLA を提供します。

### {{site.data.keyword.Bluemix_notm}} 上の {{site.data.keyword.mobilepush}} サービスに対する新規の更新
最新情報: 2017 年 5 月 24 日

{{site.data.keyword.Bluemix_notm}} 上の {{site.data.keyword.mobilepush}} サービスに使用可能な新規の更新を以下に示します。

**ライト・プラン**: {{site.data.keyword.mobilepush}}サービス用に、既存のベーシック・プランに加えて、新たにライト・プランを導入しました。 この新しいプランでは、ユーザーが 1 カ月当たり最大 10 万件のデジタル・メッセージを無料で送信できます。 ライト・プランからベーシック・プランにアップグレードした場合、ユーザーは、100 万件のデジタル・メッセージを送ると料金を請求されます。 100 万件のメッセージのカウントは、ライト・プランがベーシック・プランにアップグレードされたときに開始されます。

**モニタリング**: 送信された通知と {{site.data.keyword.mobilepush}} サービス・コンソールで登録されたデバイスに関する洞察を得ることができるようになりました。 メッセージ・レベルのトラッキングに REST API を使用することもできます。 メッセージ配信から、メッセージのディスパッチングおよびメッセージ受信まで、Web フックを構成することによって詳細を取得できます。  『[{{site.data.keyword.mobilepush}}のモニタリング (Monitoring for {{site.data.keyword.mobilepush}})](/docs/services/mobilepush/t_push_monitoring.html#monitor-notifications)』を参照してください。

**Web 通知**: Safari Web ブラウザーに通知を送信できるようになりました。

### Secure Gateway の更新
最新情報: 2017 年 5 月 24 日

最新の Secure Gateway 保守更新には、UI および API マネージャーの小規模なバグ修正および更新された資料が含まれており、クライアントがバージョン 1.7.1 に更新されました。 Secure Gateway クライアントが AIX 7.1 以上で使用可能になり、squid プロキシーを通じたアウトバウンド接続をサポートするようになりました。

### {{site.data.keyword.streaminganalyticsshort}} サービスの更新: Python 開発環境での Streams アプリケーションの開発
最新情報: 2017 年 4 月 13 日

これまでは、Python アプリケーションを開発するには IBM Streams のローカル・バージョンをインストールする必要がありました。 もうその必要はありません。 任意の開発環境または Jupyter 対話式ノートブックで、Python によってアプリケーションを開発できるようになりました。

STREAMING_ANALYTICS_SERVICE コンテキストを使用して、Python アプリケーションを {{site.data.keyword.streaminganalyticsshort}} サービスに送信できます。 {{site.data.keyword.streaminganalyticsshort}} サービスでは、Python 3.5 が必要です。

IBM Data Science Experience (DSX) 内で Jupyter ノートブックを使用してサンプル Python アプリケーションを作成し、それらのアプリケーションを DSX から直接 {{site.data.keyword.streaminganalyticsshort}} インスタンスに送信できます。 [DSX コミュニティー・ページ](https://datascience.ibm.com/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") で、ノートブック内のサンプル・ストリーム処理 Python アプリケーションを確認してください。

{{site.data.keyword.streaminganalyticsshort}} サービスの更新について詳しくは、[{{site.data.keyword.streaminganalyticsshort}} updates: DSX integration and easier Python development](https://www.ibm.com/blogs/bluemix/2017/05/streaming-analytics-updates-dsx-integration-easier-python-development/){: new_window} ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン") を参照してください。

### {{site.data.keyword.sparks}} の更新: Apache Spark 2.1 がサポートされるようになりました
最新情報: 2017 年 4 月 21 日

{{site.data.keyword.sparkl}} は、複雑なデータからの洞察を利用するアルゴリズムを作成するための Apache Spark 2.1 のサポートを導入しています。 Apache Spark 2.1 は、イベント時間ウォーターマークおよび Kafka 0.10 のサポートが追加されたため、構造化ストリーミングに大いに役立ちます。 Apache Spark 2.1 はまた、Spark SQL、SparkR、および MLlib モジュールでの安定度と使いやすさを向上させることにも重点を置いています。 Spark 2.1 について詳しくは、[Spark Release 2.1.0](http://spark.apache.org/releases/spark-release-2-1-0.html) を参照してください。

{{site.data.keyword.sparkl}} または新しいバージョンの Apache Spark 2.1 に関連したどのようなご質問にも回答いたします。sparksrv@us.ibm.com にお問い合わせください。

### {{site.data.keyword.macm_short}} は非推奨となります
最新情報: 2017 年 4 月 18 日

2017 年 3 月 30 日時点で、{{site.data.keyword.macm_long}} サービス・タイルは {{site.data.keyword.Bluemix_notm}} カタログから削除され、新規 MACM インスタンスをプロビジョンすることはできなくなります。 ただし、既存のインスタンスは引き続きサポートされます。 サポート終了日は 2018 年 3 月 30 日です。 サポート終了日の前に {{site.data.keyword.macm_short}} (MACM) サービス・インスタンスを削除してください。 IBM Watson Content Hub にマイグレーションすることをお勧めします。 Watson Content Hub は、IBM Marketplace で入手可能であり、30 日間の無料トライアルが提供されています。 IBM Watson Content Hub は、MACM と同様の機能を提供し、資産管理、IBM Watson サービスを使用したコグニティブなタグ付けなどの新機能が追加されています。また、お客様に最良のエクスペリエンスを保証するためにコンテンツ配信ネットワーク (CDN) を組み込みました。 IBM は、コンテンツを MACM から Watson Content Hub にマイグレーションするためのサービス・エンゲージメントを提供します。


### {{site.data.keyword.sparks}} の更新: Data Science Experience でノートブックがサポートされるようになりました
最新情報: 2017 年 4 月 11 日

ノートブックおよび Spark で作業するための新しいプラットフォームは Data Science Experience です。 [Data Science Experience](http://datascience.ibm.com/) に登録し、ノートブックの作成と、他のデータ・サイエンティストとの専門知識の共有を開始してください。

{{site.data.keyword.sparks}} でノートブックを操作していた場合、ノートブックを Data Science Experience にマイグレーションできます。 詳しくは、[ノートブックのマイグレーションの資料](/docs/services/AnalyticsforApacheSpark/index-gentopic2.html#migration_to_dsx)を参照してください。
