# Azure 技術資料インデックス

- 本インデックスは、日本マイクロソフトの社員が作成してネット上に公開している日本語の Azure 技術情報へのポインタを、有志の社員が取りまとめてリスト化・公開しているものです。
- 想定している利用者は現場のアーキテクトやエンジニアの方で、実際の Azure 利用時に役立つような、しっかり学べる・理解できる技術情報をまとめています。

## 使い方

- 興味のある or 調べる必要があるトピックの資料をそのままご確認ください(=順不同です)。
- なるべく各技術・トピックに対して 1 つの資料となるようにしていますが、場合によって、異なるメンバーが作成した複数の資料が掲載されている場合もあります。この場合は各資料をご覧いただき、自分の目的などに合ったほうをご利用ください。
- 全般的に Azure を学習したい場合には、オススメ度マークを参考にしてください。
- (参考) Azure 初学者の方には、[mstep オンラインの Azure 学習コンテンツ](https://partner.microsoft.com/ja-jp/training/mstep-platform)がおすすめです。こちらもご参照ください。

## 免責事項

- 各コンテンツの内容に関するご質問やバグ F/B、サポートなどはこちらのページでは一切行っていません。これらは、コンテンツを作成している弊社の社員へ直接送るか、あるいは身近にいるマイクロソフト社員に聞いてみるなどしてください。
- 本インデックスは、アーキテクトやエンジニアの皆様に向けた技術情報のご提供のみを目的としています。各コンテンツの内容について何ら保証するものではなく、使用に関連してお客様、お客様の関連会社、または第三者に生ずる間接的、付随的、結果的な損害（営業機会や営業情報の損失などを含む）について一切責任を負いません。

## リンク

- [技術インデックス](#技術インデックス)
- [社員・チームBlog](#社員チームblog)

## 技術インデックス

|大分類|小分類|トピック|オーナー|オススメ度|コンテンツ|
|:----|:----|:----|:----|:----|:----|
|設計・アーキテクチャ論|Azure 概論|Azure 標準化ガイドライン|tkanbara||[GitHub](https://github.com/Azure/Azure-standardization-guideline)|
|||Azure L100（旧版）|nakama||[mp4(1)](https://download.microsoft.com/download/d/b/0/db00c64b-5d6f-4394-b44b-baee4ef52133/2019_03_04_AzureL100Part1(HD).zip) [mp4(2)](https://download.microsoft.com/download/4/8/8/488124d3-6519-484e-bf74-8db9fe7c9e39/2019_03_04_AzureL100Part2(HD).zip) [mp4(3)](https://download.microsoft.com/download/6/f/5/6f5a32f4-f1c6-4210-84a6-09f5f055e449/2019_03_04_AzureL100Part3(HD).zip) [mp4(4)](https://download.microsoft.com/download/c/e/0/ce0be5d2-2d5b-4d4c-a740-1ae5790e5526/2019_03_04_AzureL100Executive(HD).zip)|
||設計・開発方法論（一般）|Azure CAF (超訳版) (2022/12 版)|nakama||[ppt](https://aka.ms/AAj0ml9) [mp4 (前半)](https://aka.ms/AAj0ml8) [mp4 (後半)](https://aka.ms/AAj08w7)|
||セキュリティ|ゼロトラストセキュリティ|nakama|★★★|[ppt](https://download.microsoft.com/download/d/f/e/dfed7e7b-75e8-4939-823d-25a06b0abd68/FgCF_①_0_Zero_trust_type_multi_cloud_IT_environment_Introduction_Further_shortened_version_v0.40.pptx) [mp4](https://download.microsoft.com/download/b/5/0/b507ac40-280b-413a-be8a-56b29a6a765d/2020_03_10_FgCF_ZeroTrustMultiCloudITEnvironment_movie_v0.40a.zip) [YouTube](https://www.youtube.com/watch?v=T3bySEjhoQ8)|
|||OA 環境設計|nakama|★|[ppt](https://download.microsoft.com/download/e/6/2/e6254b95-f822-42a9-b68c-057a71a67dca/FgCF_102_Zero_Trust_Multi_Cloud_IT_Environment_OA_Environment_Design_v0.17.pptx) [mp4](https://download.microsoft.com/download/3/7/0/370c26c3-a785-462b-a484-b69500d28680/FgCF_Zero_Trust_IT_Infrastructure_Design_way_of_thinking_video_v0.17.mp4) [YouTube](https://www.youtube.com/watch?v=QUyfcHDJXyI)|
|||Azure W-AF : Security|nakama|★|[ppt](https://download.microsoft.com/download/1/3/8/13855030-7731-47a8-9759-ff28d9c32e3e/AzureW-AF_Security_section_Overview_documentation_v0.13.pptx) [mp4](https://download.microsoft.com/download/1/4/9/149d6525-9a7a-42a4-9302-87efce5f4d82/2020_06_12_AzureW_AF_Security_v0.13.zip) [YouTube](https://www.youtube.com/watch?v=w7-LVAWaGZU)|
||アプリ開発技術概論|Web アプリ開発入門|hihorika||[YouTube](https://www.youtube.com/watch?v=OogiYJ4ogtY)|
|||コンテナ技術入門|nakama|★|[ppt](https://download.microsoft.com/download/3/f/7/3f7ac344-01c4-4c7f-8509-85bcc7371d9f/FgCF_130_CaaS_Container_Super_introduction_v0.03.pptx) [mp4](https://download.microsoft.com/download/5/7/6/5763af79-e5c0-4a37-86a5-e875581a5393/FgCF_130_CaaS_Container_Super_introduction_v0.03.zip)|
|||k8s on Azure 入門|shiasa||[YouTube](https://aka.ms/ocpjptbapp041)|
|||REST API 呼び出し 入門|hihorika||[YouTube](https://aka.ms/ocpjptbapp020)|
||アプリ開発技術選択|IaaS/CaaS/PaaS の使い分け|nakama|★|[ppt](https://aka.ms/AAj0yh3)|
|||最適な実行環境の選び方|yoterada||[YouTube](https://www.youtube.com/watch?v=0pmLbsj9sgQ)|
|||サーバレス技術の使い分け|osamum||[YouTube](https://aka.ms/ocpjptbapp021)|
|||マイクロサービス開発技術|inkyokut||[YouTube](https://www.youtube.com/watch?v=yNowq1VNPFs)|
|||Java on Microsoft|yoterada||[YouTube](https://www.youtube.com/watch?v=Zk-LbJkmIyg)|
|||Java on SpringCloud, ACA|yoterada||[YouTube](https://www.youtube.com/watch?v=iBP-PPTSDAU)|
|||DB サービスの使い分け|tfukuha||[YouTube](https://aka.ms/ocpjptbdat001)|
|||リアルタイム通信開発|osamum||[YouTube](https://www.youtube.com/watch?v=QLxkwlIy67c)|
|||GitHub & Azure DevOps 選択|tokawa||[YouTube](https://www.youtube.com/watch?v=MOY_swYqCMA)|
||データ & AI 技術選択|データサービス技術選択|enishimu||[YouTube](https://www.youtube.com/watch?v=FL4t1aFrtVY)|
|||分析プラットフォーム|tsmatsuz||[YouTube](https://www.youtube.com/watch?v=epo3Z_gU3wo)|
|||Azure Analytics 概要|tfukuha|★|[YouTube](https://aka.ms/ocpjptbdat031)|
|||Azure AI 概要|nohanaga||[YouTube](https://aka.ms/ocpjptbdat061)|
|||Azure ML 概要|tsmatsuz||[YouTube](https://www.youtube.com/watch?v=2nG54x-1eIw)|
|||Azure Cognitive Services 概要|nohanaga||[YouTube](https://www.youtube.com/watch?v=9GcjFofXdd0)|
||OLTP 開発ノウハウ|東西冗長構成|kodaisakabe||[YouTube](https://aka.ms/ocpjptbinf006)|
|||高負荷 Web サイト開発|ishiraok||[YouTube](https://aka.ms/ocpjptbapp003)|
|||k8s デザインパターン|shiasa||[YouTube](https://aka.ms/ocpjptbdat043)|
|||マルチテナント型 SaaS 設計|hihorika||[YouTube](https://www.youtube.com/watch?v=_BG68kbO-4k)|
|||Azure W-AF : Perf Excellcence|tokubo||[YouTube](https://www.youtube.com/watch?v=C9xWJYdc1AE)|
||AI/ML 開発ノウハウ|レコメンデーションシステム開発|nohanaga||[YouTube](https://aka.ms/ocpjptbdat067)|
||運用管理技術|Web サービス運用ガイド|kodaisakabe||[YouTube](https://www.youtube.com/watch?v=2633bXz4tTU)|
|||Azure W-AF : Reliability Design|tokubo||[YouTube](https://www.youtube.com/watch?v=pgSsGS6o230)|
|||Azure W-AF : Ops Excellence|kodaisakabe||[YouTube](https://www.youtube.com/watch?v=8Ye-NELynjc)|
||トレーニング|Microsoft Learn|odasho||[YouTube](https://aka.ms/ocpjptbetc002)|
|||Synapse Analytics & AI 自習方法|tfukuha||[YouTube](https://aka.ms/ocpjptbdat041)|
|Azure テクノロジ|セキュリティ|Azure AD 入門|tfukuha||[YouTube](https://aka.ms/ocpjptbinf001)|
|||Azure AD 基礎・Azure AD B2B|nakama|★★★|[ppt](https://download.microsoft.com/download/1/3/8/138c3005-82f4-41db-bf78-9ce6d46af2ab/FgCF_①_2_AzureAD_Overview_v0.70.pptx) [mp4](https://download.microsoft.com/download/f/6/0/f6093441-8ca4-4901-b74e-f87894fc9ad8/2020_01_08_FgCF_AzureADForAzureBasics_v0.22.zip) [YouTube](https://www.youtube.com/watch?v=H7TKjAGT7pA) [フルセット版](https://download.microsoft.com/download/4/4/2/442b4fb3-f47a-4d13-b67a-ab5c721dc4ac/AzureAuthorizationDesignAndManagement_v0.67.pptx)|
|||Azure AD テナント初期構築|nakama|★|[ppt](https://download.microsoft.com/download/a/0/3/a03cab45-1a89-4e53-b026-1b55a2ee91db/FgCF_112_VDC_construction_Authentication_infrastructure_Method_of_creating_Azure_AD_tenant_for_Azure_management_v0.01.pptx) [mp4](https://download.microsoft.com/download/3/b/f/3bfc7a3a-2560-4659-8eef-8af599c41320/FgCF_112_VDC_construction_Authentication_infrastructure_Method_of_creating_Azure_AD_tenant_for_Azure_management_v0.01.zip)|
|||Azure AD アプリ認証連携|tsmatsuz||[YouTube](https://aka.ms/ocpjptbinf002)|
|||MDfC/MDfS|nakama|★★|[→ IaaS VM 管理ガイドを参照](https://aka.ms/AAj08w4)|
|||セキュリティ機能概要|tokubo||[YouTube](https://www.youtube.com/watch?v=83LbnY1Rxjo)|
|||SQL DB, Synapse Workspace|tfukuha||[YouTube](https://aka.ms/ocpjptbdat004)|
|||Sentinel|hinakamu|★|[WebCast](https://japan.zdnet.com/paper/30001233/30005544/)|
||インフラ|Azure 物理インフラ|tokawa|★|[YouTube](https://aka.ms/ocpjptbinf007)|
|||インフラセキュリティ強化|tfukuha||[GitHub](https://github.com/Azure/jp-iaassecurity)|
||ネットワーク|Azure ネットワーク概要|minaito||[YouTube](https://aka.ms/ocpjptbinf003)|
|||仮想ネットワーク設計|nakama|★★★|[ppt](https://download.microsoft.com/download/4/d/e/4de15095-223c-4e82-b187-315ffa852ade/FgCF_111_VDC_construction_Network_infrastructure_Azure_network_infrastructure_Explanation_v0.35.pptx) [mp4](https://download.microsoft.com/download/2/7/2/272111c2-a418-4864-b9ac-aaf01268c5c6/FgCF_111_VDC_construction_Network_infrastructure_Azure_network_infrastructure_Explanation_v0.35.zip)|
|||延伸型 VNET 設計|nakama||[ppt](https://download.microsoft.com/download/d/f/f/dff93ba3-ab62-4a66-afc7-5d10da094c18/Web_DB_type_system_reference_architecture_and_main_points_of_construction(IaaS_VM_edition).pptx) [mp4](https://download.microsoft.com/download/d/a/8/da86811f-2aba-46da-ab2a-c42ed4e5a5c8/2019_11_07_FgCF_WebDB_ReferenceArchitecture(IaaSVM).zip) [YouTube](https://www.youtube.com/watch?v=iy4eGaUb-7U)|
|||隔離型 VNET 設計|nakama||[ppt](https://download.microsoft.com/download/4/5/d/45d6e951-4d42-4276-83ac-13b5632b2ab9/FgCF_121_IaaS_VNET_IaaSVM_Reference_Architecture(Isolated_VNET_version)_v0.01.pptx) [doc](https://download.microsoft.com/download/a/c/8/ac880230-c893-49f3-b32d-3e70e8ac6f22/2021_05_31_FgCF_IaaS_IsolatedVNET_ReferenceArchitecture_v0.11_docs.zip) [mp4](https://download.microsoft.com/download/d/2/a/d2a476af-136a-4846-853e-0d566f9f9b96/FgCF_121_IaaS_VNET_IaaSVM_Reference_Architecture(Isolated_VNET_version)_v0.01.zip)|
||IaaS|IaaS VM 入門|tfukuha|★★|[YouTube](https://aka.ms/ocpjptbdat009)|
|||VM シリーズ・サイズ選択|kakikuch||[YouTube](https://www.youtube.com/watch?v=U9AkACxNWuo)|
|||IaaS VM 解説 (旧)|nakama||[ppt](https://download.microsoft.com/download/9/a/2/9a258748-936b-4b43-b127-2adc616e70d7/FgCF_①_3_SecurityBaseline(IaaS)_v1.00.pptx) [mp4](https://download.microsoft.com/download/d/6/0/d60816c1-47d8-4e7f-9a3a-ef404b441104/2020_01_17_FgCF_SecurityBaseline(IaaS)_v1.00_SplitVersion.zip) [YouTube](https://www.youtube.com/watch?v=S3A4Q9qRcCs)|
|||IaaS VM 管理ガイド|nakama|★★|[ppt](https://aka.ms/AAj08w4) [doc](https://aka.ms/AAj0ggu) [mp4 (前半)](https://aka.ms/AAj08w6) [mp4 (後半)](https://aka.ms/AAj0ggw)|
|||Confidential Computing|nakama||[ppt](https://aka.ms/AAj1dsr) [mp4](https://aka.ms/AAj1op4)|
|||Azure Migrate|kosetoguchi||[YouTube](https://www.youtube.com/watch?v=9F-ZKtQcVAo)|
||CaaS|AKS|nakama||[ppt](https://download.microsoft.com/download/6/4/c/64c7f727-7712-49e7-a95e-7aa19e412e68/2020_04_25_AKS_TechnicalReference_v0.14(ppt).zip) [mp4(1)](https://download.microsoft.com/download/6/6/c/66c3ab0e-3d15-4e79-8377-a2880f1569b2/2020_04_25_AKS_TechnicalReference_v0.14(video1).zip) [mp4(2)](https://download.microsoft.com/download/9/7/8/97858185-ba75-48a3-a931-72092b5c1279/2020_04_25_AKS_TechnicalReference_v0.14(video2).zip) [doc](https://download.microsoft.com/download/d/e/1/de1f3cf0-8589-4e21-a4e0-4d9bd7de8291/FgCF_132_CaaS_AKS_TechnicalReference_Buildingsample_app_v0.13.zip) [mp4(3)](https://download.microsoft.com/download/b/a/8/ba8a9c96-4fc8-43ed-8309-9624d1a45779/2020_04_25_AKS_TechnicalReference_v0.14(video3).zip) [YouTube(1)](https://www.youtube.com/watch?v=t-qqjCLwcQo) [YouTube(2)](https://www.youtube.com/watch?v=qSyhyO6QRcY) [YouTube(3)](https://www.youtube.com/watch?v=-X1QHzsOhBo)|
|||ARO|tetsuyasodo||[ppt](https://download.microsoft.com/download/8/d/1/8d130c64-7aaa-4416-bec6-70c910c6d5df/FgCF_133_CaaS_ARO_TechnicalReference_v0.14.pptx) [doc](https://download.microsoft.com/download/a/8/5/a855ac44-bee0-4d1a-9f55-c8133d0814c7/FgCF_133_CaaS_ARO_TechnicalReference_v0.14_Construction_Script.md)|
|||AKS セキュア化|tfukuha||[GitHub](https://github.com/Azure/jp-akssecurity)|
||PaaS|App Service 入門|tokawa|★|[YouTube](https://aka.ms/ocpjptbapp001)|
|||App Service|nakama||[ppt](https://download.microsoft.com/download/6/9/3/6934d11e-78dc-4c00-ae61-316067193dc1/AppService_TechnicalReference_v0.06.pptx) [mp4(1)](https://download.microsoft.com/download/6/e/a/6ea96ebd-d9ff-4291-8976-a23698bf1282/2020_06_16_AppService_TechnicalReference_Part1.zip) [mp4(2)](https://download.microsoft.com/download/e/1/3/e130959e-7e85-48a0-a583-6ac49eed7303/2020_06_16_AppService_TechnicalReference_Part2.zip) [mp4(3)](https://download.microsoft.com/download/1/2/4/124c009d-2783-447f-8dad-124499c1523b/2020_06_16_AppService_TechnicalReference_Part3.zip) [YouTube(1)](https://www.youtube.com/watch?v=pfFEtl6hK1w) [YouTube(2)](https://www.youtube.com/watch?v=tP8uQ6WgFAM) [YouTube(3)](https://www.youtube.com/watch?v=L05eizD8ws4)|
|||App Service セキュア化|tfukuha||[GitHub](https://github.com/Azure/jp-appservicesecurity)|
|||Azure Batch|nakama||[ppt(1)](https://download.microsoft.com/download/1/a/7/1a7fb7e9-1602-46de-9ff0-e8548d146a5b/2019_05_21_AzureBatchSample_Materials.zip) [mp4(1)](https://download.microsoft.com/download/4/8/b/48baeee0-921c-4ecd-afa1-c57b2dcdc935/2019_05_21_AzureBatchSample_Video.zip) [YouTube(1)](https://www.youtube.com/watch?v=Z8d4zq8Skh4) [ppt(2)](https://download.microsoft.com/download/4/5/4/454c783b-372f-48c1-aed8-e7b7b112599a/AzureBatch_Technical_reference_v0.20.pptx) [mp4(2)](https://download.microsoft.com/download/2/1/6/2160a96c-deca-43fd-a557-72a9d29b58e1/2020_08_14_AzureBatch_TechnicalReference_v0.20.zip) [YouTube(3)](https://www.youtube.com/watch?v=VvmK7wRBU5Y)|
|||Azure Spring Cloud|yoterada||[YouTube](https://aka.ms/ocpjptbapp061)|
|||Java on App Service|yoterada||[YouTube](https://www.youtube.com/watch?v=ymN68MtMwT0)|
|||JBoss EAP on App Service|yoterada||[YouTube](https://www.youtube.com/watch?v=pLUevbSglk8)|
||ローコード開発|Logic Apps|tfukuha|★|[YouTube](https://aka.ms/ocpjptbapp022)|
||ストレージ (DB)|SQL Database|nakama||→ App Service 資料を参照|
|||DB 高可用構成|enishimu||[YouTube](https://aka.ms/ocpjptbdat007)|
|||Azure Database for PostgreSQL|enishimu||[YouTube](https://aka.ms/ocpjptbdat002)|
|||Oracle to PostgreSQL 移行ガイド|enishimu||[YouTube](https://aka.ms/ocpjptbdat006)|
|||IaaS SQL Server|tfukuha|★|[YouTube](https://aka.ms/ocpjptbdat008)|
|||SQL DB vs SQL MI|tfukuha||[YouTube](https://aka.ms/ocpjptbdat010)|
|||SQL DB セキュア化|tfukuha||[GitHub](https://github.com/Azure/jp-sqlsecurity)|
||ストレージ (NoSQL)|Cosmos DB|enishimu||[YouTube](https://aka.ms/ocpjptbdat003)|
|||Blob Storage|tfukuha||[YouTube](https://aka.ms/ocpjptbinf005)|
||データ分析|Synapse Analytics|tfukuha||[YouTube](https://aka.ms/ocpjptbdat032)|
|||Synapse Dedicated SQL Pool|tsmatsuz||[YouTube](https://aka.ms/ocpjptbdat034)|
|||Synapse Pipeline, Spark|tfukuha||[YouTube](https://aka.ms/ocpjptbdat033)|
|||Power BI + Synapse Analytics|enishimu||[YouTube](https://aka.ms/ocpjptbdat037)|
|||Synapse Studio ソースコード管理|ishiraok||[YouTube](https://aka.ms/ocpjptbdat039)|
|||Synapse Link for Cosmos DB|tfukuha||[YouTube](https://aka.ms/ocpjptbdat035)|
|||Azure Data Explorer|taishimiyata||[blog1](https://qiita.com/tmiyata25/items/61608bb4a63dca55dcaf) [blog2](https://qiita.com/tmiyata25/items/d8606bad9a64015aed92)|
||データ移行・連携|Database Migration Service|kunisato||[YouTube](https://aka.ms/ocpjptbdat005)|
|||Qlik データ統合製品 + Synapse|naigaras||[YouTube](https://aka.ms/ocpjptbdat040)|
||AI/ML (Azure ML)|Azure ML : AutoML, Designer|tsmatsuz|★|[YouTube](https://aka.ms/ocpjptbdat068)|
|||Azure ML : Synapse 連携|tsmatsuz||[YouTube](https://aka.ms/ocpjptbdat069)|
|||Azure ML 基盤構築|nohanaga|★|[YouTube](https://www.youtube.com/watch?v=FyhSPMpnDuU)|
|||Azure ML : ML Ops|nohanaga|★|[YouTube](https://www.youtube.com/watch?v=KdbuWpRGwNk)|
|||Anatomy Detector (異常検知) API|nohanaga|★|[YouTube](https://aka.ms/ocpjptbdat066)|
||AI/ML (Cognitive)|LUIS, QnA Maker|nohanaga||[YouTube](https://aka.ms/ocpjptbdat073)|
|||Speech Service|tokawa||[YouTube](https://aka.ms/ocpjptbdat076)|
|||Computer Vision|shiasa||[YouTube](https://aka.ms/ocpjptbdat070)|
|||Cognitive Search Custom Skill|nohanaga||[YouTube](https://aka.ms/ocpjptbdat078)|
|||Video Indexer|tokawa||[YouTube](https://aka.ms/ocpjptbdat072)|
|||Text Analytics, Translator, Immersive Reader|tsmatsuz||[YouTube](https://aka.ms/ocpjptbdat074)|
|||Content Moderator|tfukuha||[YouTube](https://aka.ms/ocpjptbdat075)|
|||Form Recognizer|tsmatsuz||[YouTube](https://aka.ms/ocpjptbdat071)|
|||Custom Speech, Speech Translation, Speaker Recognition|tsmatsuz||[YouTube](https://aka.ms/ocpjptbdat077)|
||データ管理・ガバナンス|Purview|kunisato||[YouTube](https://www.youtube.com/watch?v=ZEAMM9qIn9k)|
||IoT / Edge|大量データストリーミング処理|tsmatsuz|★★|[YouTube](https://aka.ms/ocpjptbdat036)|
|||IoT Hub, IoT Central|tfukuha|★★|[YouTube(1)](https://aka.ms/ocpjptbiot001) [YouTube(2)](https://aka.ms/ocpjptbiot002)|
|||Ditigal Twins|tahirai|★|[YouTube](https://aka.ms/ocpjptbiot006)|
|||IoT Plug and Play, DTDL|tahirai||[YouTube](https://aka.ms/ocpjptbiot005)|
|||IoT Security|tahirai||[YouTube](https://aka.ms/ocpjptbiot004)|
|||IoT Edge (SQL Edge, Live Video Analytics)|tfukuha|★|[YouTube](https://aka.ms/ocpjptbiot003)|
|||Cognitive Services on Edge|tsmatsuz||[YouTube](https://aka.ms/ocpjptbdat065)|
|||Azure Percept|tfukuha||[YouTube](https://aka.ms/ocpjptbiot007)|
||CI/CD, DevOps|Azure DevOps|nakama|★|[ppt](https://download.microsoft.com/download/a/f/f/affd5a6d-342f-4c19-a250-040d1ab3ce86/AzureDevOps_OverviewAndDemo_v0.02.pptx) [mp4](https://download.microsoft.com/download/2/0/b/20b0d275-0256-43b2-ac39-d22c9d5a47a6/2020_02_26_AzureDevOps_OverviewAndDemo_v0.02.zip) [YouTube](https://www.youtube.com/watch?v=bQ5qG7Avfws)|
|||GitHub DevOps|ishiraok||[YouTube](https://aka.ms/ocpjptbapp051)|
|||GitHub Actions|ishiraok||[YouTube](https://aka.ms/ocpjptbapp052)|
|||GitHub DevSecOps|yodekig||[YouTube](https://www.youtube.com/watch?v=scB-pO1StDw)|
|||Github & Visual Studio Code|ishiraok|★|[YouTube](https://aka.ms/ocpjptbapp050)|
||開発技術|Blazor, Static Web Apps|osamum||[YouTube](https://aka.ms/ocpjptbapp002)|
|||ASP.NET Core Blazor|nakama||[ppt](https://download.microsoft.com/download/7/0/5/705c8f4d-293e-4baa-9cc2-8db3ac9cc5dd/ASP.NETBlazor_v0.30.pptx) [zip](https://download.microsoft.com/download/0/1/f/01f96048-4250-4d8a-aa5d-d52a7c94a219/2021_11_25_AspNetCoreBlazorサンプルプログラム.zip)|
|||Microsoft OpenJDK|yoterada||[YouTube](https://www.youtube.com/watch?v=pcJGdtaFV-U)|
|||VS Code による Java 開発|yoterada||[YouTube](https://www.youtube.com/watch?v=YWzlCWSrKJ8)|
|||Bot Framework|osamum||[YouTube](https://aka.ms/ocpjptbapp004)|
||DaaS|AVD|nakama||[ppt](https://download.microsoft.com/download/7/0/4/7044dce5-224d-48ae-ab78-e25935e59b6f/WVD_Commentary_material_v0.19.pptx)|
||Multi/Hybrid|Azure Stack HCI|osamut||[YouTube](https://www.youtube.com/watch?v=VT2gJnMntTM)|
|||Azure Arc enabled Kubernetes|shiasa||[YouTube](https://aka.ms/ocpjptbapp042)|
|||Azure Arc enabled SQL MI|tfukuha||[YouTube](https://aka.ms/ocpjptbdat011)|
||運用管理|Azure 運用管理サービス全体像|tfukuha|★|[YouTube](https://aka.ms/ocpjptbinf008)|
|||Azure Monitor 入門|tfukuha||[YouTube](https://aka.ms/ocpjptbinf009)|
|||Azure Monitor 監視|makuroda||[YouTube](https://aka.ms/ocpjptbinf004)|
|||仮想マシンの運用管理 詳細|nakama||→ IaaS VM 管理ガイドを参照|
||その他|IaC (ARM テンプレート)|nakama||[ppt](https://download.microsoft.com/download/e/e/9/ee906254-0816-41f4-98eb-612bcbf1455a/ARM_template_development_v0.33.pptx) [mp4](https://download.microsoft.com/download/1/f/0/1f063580-4ba6-41f1-913f-2ba81425185c/2019_01_03_PracticalARMTemplate.zip) [YouTube1](https://www.youtube.com/watch?v=NGrnP8OdF7U) [YouTube2](https://www.youtube.com/watch?v=BQy7WCYBFCU)|
|||Chaos Studio|yojijo||[YouTube](https://www.youtube.com/watch?v=lPrg9bpzthQ)|
|||D365 Customer Insights|keiji||[YouTube](https://aka.ms/ocpjptbdat038)|


## 社員・チームBlog

### MSKK 社員
|社員またはチーム|タグ|YouTube|Blog|GitHub|Qiita|その他|
|:----|:----|:----|:----|:----|:----|:----|
|Qiita MS 社員ページ|||||[Qiita](https://qiita.com/organizations/microsoft)||
|Annoske|DevOps||||[Qiita](https://qiita.com/Annoske)||
|aomachi|AppService, Functions||||[Qiita](https://qiita.com/Atsushi_Omachi)||
|asuzuki|Azure Network||||[Qiita](https://qiita.com/achu0628)|[その他](https://hutene.com/)|
|dahatake|Data/AI||||[Qiita](https://qiita.com/dahatake)||
|daisami|Azure, ASP.NET, Java||[Blog](https://normalian.hatenablog.com/)||||
|dmaki|AppService||||[Qiita](https://qiita.com/dismakeu)||
|ftokumitsu|||||[Qiita](https://qiita.com/toku345)||
|haoqiangyou|Azure IaaS, k8s, Terraform||[Blog](https://hyoublog.com/)||||
|hihigash|Azure DevOps||||[Qiita](https://qiita.com/hihigash)||
|hihorika|AppService, Functions||[Blog](https://uncaughtexception.hatenablog.com/)|[GitHub](https://github.com/horihiro)|[Qiita](https://qiita.com/horihiro)||
|hisnakad|MDfC, Sentinel||||[Qiita](https://qiita.com/hisnakad)||
|hkashiwagi|D365|||[GitHub](https://github.com/hide6974)|[Qiita](https://qiita.com/hide6974)||
|hyatsu|AppService||||[Qiita](https://qiita.com/hyatsu)||
|ishiyam|Azure Infra||||[Qiita](https://qiita.com/Isato-Hiyama)||
|ishiyam|Azure Infra||||[Qiita](https://qiita.com/Isato-Hiyama)||
|jtsuchida|C#, Azure||||[Qiita](https://qiita.com/07JP27)||
|junkitayama|AppDev|||[GitHub](https://github.com/jun110)|[Qiita](https://qiita.com/jun110)||
|juyamagu|Azure Infra||[Blog](https://zenn.dev/openjny)||||
|kahiro|Azure, .NET|||[GitHub](https://github.com/kazumihirose)|[Qiita](https://qiita.com/kazumihirose)||
|kakusaya|Azure Infra||[Blog](https://www.michikusayan.com/)|[GitHub](https://github.com/kzk839)|[Qiita](https://qiita.com/KazukiKusaya)||
|kaota|.NET|[YouTube](https://www.youtube.com/channel/UCi-IqYqwxd_NgTydJVCIQLg)|[Blog](https://blog.okazuki.jp)|[GitHub](https://github.com/runceel)|[Qiita](https://qiita.com/okazuki)|[その他](https://zenn.dev/okazuki)|
|kasakemi|Azure Infra||||[Qiita](https://qiita.com/shakemi)|[その他](https://zenn.dev/skmkzyk)|
|kenakamu|Azure|||[GitHub](https://github.com/kenakamu)|[Qiita](https://qiita.com/kenakamu)||
|kenakay|Azure||[Blog](https://www.kentsu.website/)||[Qiita](https://qiita.com/KentoNaka)||
|khigashi|AppService||||[Qiita](https://qiita.com/khigashi)||
|koheisaito|Java||||[Qiita](https://qiita.com/kk31108424)||
|koishizu|Azure Infra|||||[その他](https://zenn.dev/zukako)|
|koishizu|Azure Infra|||[GitHub](https://github.com/zukakosan)|[Qiita](https://qiita.com/zukakosan)||
|kokecross|DevOps||||[Qiita](https://qiita.com/KoKeCross)||
|komayama|AppService, Functions||[Blog](https://mym.works/)||[Qiita](https://qiita.com/mym)||
|komiyasa|Azure, AppDev|||[GitHub](https://github.com/komiyasa)|[Qiita](https://qiita.com/komiyasa)||
|ktakahashi|Data/AI|||[GitHub](https://k14i.github.io/)|||
|kumukai|D365, PowerPlatform||||[Qiita](https://qiita.com/kumukai)||
|machiy|AI, Bot||||[Qiita](https://qiita.com/chomado)||
|mahiyama|Azure AD||||[Qiita](https://qiita.com/mahiya)||
|maikoshima|AppService||||[Qiita](https://qiita.com/MaikoShima)||
|makokui|AppService||||[Qiita](https://qiita.com/makokui)||
|manabuoda|Azure, EA Portal||||[Qiita](https://qiita.com/manabuoda)||
|manamitaira|AVD||||[Qiita](https://qiita.com/mana_cat)||
|masatoueda|Azure Infra||||[Qiita](https://qiita.com/ueda_it)||
|mikono|AppService||||[Qiita](https://qiita.com/superriver)||
|mimochiz|Data/AI||||[Qiita](https://qiita.com/mimocihz)||
|mnanri|Azure||||[Qiita](https://qiita.com/mnanri)||
|nakama|.NET|||[GitHub](https://github.com/nakamacchi/)|||
|naoshima|AppDev||[Blog](https://nt-blogs-nt-7.vercel.app/blog)||[Qiita](https://qiita.com/nt-7)||
|nobukoyamada|LogicApp||||[Qiita](https://qiita.com/e99h2121)||
|oliva|AppDev||||[Qiita](https://qiita.com/oliva)||
|shnagata|Data/AI|||[GitHub](https://github.com/shohei1029)|[Qiita](https://qiita.com/aical)|[その他](https://zenn.dev/shohei_aio)|
|shohe|AppService, Functons, Azure Stack||||[Qiita](https://qiita.com/shogo-ohe)||
|shuda|Azure Infra|[YouTube](https://www.youtube.com/playlist?list=PLW6S2_dcoOggAeezwp1o7uSrsXSYUd0zZ)|[Blog](https://www.syuheiuda.com/)|[GitHub](https://github.com/ShuheiUda)|||
|shuit|Data/AI||||[Qiita](https://qiita.com/ShuntaIto)||
|shyamag|Azure AD||||[Qiita](https://qiita.com/Shinya-Yamaguchi)||
|skuramoto|D365||||[Qiita](https://qiita.com/skuramoto)||
|So Nkbys|AppDev||||[Qiita](https://qiita.com/so_nkbys)||
|taishimiyata|Data/AI||||[Qiita](https://qiita.com/tmiyata25)||
|takeoka|AVD|||[GitHub](https://github.com/takeokams)|[Qiita](https://qiita.com/takeokams)||
|takmas|PowerApps, PowerAutomate||||[Qiita](https://qiita.com/Takashi_Masumori)||
|tanagaya|||||[Qiita](https://qiita.com/takmnagaya)||
|tatsumiy|Azure Infra||||[Qiita](https://qiita.com/aktsmm)||
|taushiga|Azure Infra||[Blog](https://www.cloudou.net/)||||
|tetsuyasodo|k8s|||[GitHub](https://github.com/tetsuyasodo)|[Qiita](https://qiita.com/tetsuyasodo)||
|tkamiya|||||[Qiita](https://qiita.com/t3kot3ko)||
|tkawabuchi|k8s||||[Qiita](https://qiita.com/tbuchi888)||
|tokawa|Azure, AppDev|||[GitHub](https://github.com/tokawa-ms)|[Qiita](https://qiita.com/tokawa-ms)||
|tomakabe|k8s||[Blog](https://torumakabe.github.io/)||||
|toshida|AppService||[Blog](https://blog.toshida.org/)|[GitHub](https://github.com/georgeOsdDev)|[Qiita](https://qiita.com/georgeOsdDev@github)||
|tsunomur|Azure Infra||||[Qiita](https://qiita.com/tsubasaxZZZ)||
|tsushi|Functions|||[GitHub](https://github.com/TsuyoshiUshio)|[Qiita](https://qiita.com/TsuyoshiUshio@github)||
|tsushi|DevOps, Functions||[Blog](https://simplearchitect.hatenablog.com/)|||[その他](https://note.com/simplearchitect/)|
|tuesaka|Azure AppDev||||[Qiita](https://qiita.com/takashiuesaka)||
|wahaniya|AppDev|||[GitHub](https://github.com/watahani)|[Qiita](https://qiita.com/watahani)||
|ymatsumoto|Azure Infra||[Blog](https://blog.aimless.jp/)|[GitHub](https://github.com/kongou-ae)|||
|yoichiozaki|Algorithm||[Blog](https://zakimal.github.io/ja/post/)|[GitHub](https://github.com/zakimal)|[Qiita](https://qiita.com/zak74702675)||
|yoo|MDfC, Sentinel||||[Qiita](https://qiita.com/YoshiakiOi)||
|yoterada|Java|[YouTube](https://www.youtube.com/c/YoshioTerada/videos)||[GitHub](https://github.com/yoshioterada)|[Qiita](https://qiita.com/yoshioterada)||
|yukirii|k8s||[Blog](https://blog.yukirii.dev/)||[Qiita](https://qiita.com/yukirii)||
|yukurash|AppService||||[Qiita](https://qiita.com/yukurash)||
|yunasugimoto|AppService, Functions||||[Qiita](https://qiita.com/yuna-s)||
|yusukekodama|Azure AD|||[GitHub](https://github.com/yusukekodama/PMActivities/blob/master/Webinar/Schedule.md)|||
|yutobo|AppService||||[Qiita](https://qiita.com/YusukeTobo)||
|yuyon|AppDev||[Blog](https://yonehub.y10e.com/)||[Qiita](https://qiita.com/y10exxx)||
### MSKK チーム
|社員またはチーム|タグ|YouTube|Blog|GitHub|Qiita|その他|
|:----|:----|:----|:----|:----|:----|:----|
|MSKK 主催・協賛の Azure 関連セミナー・Webinar ①||||||[その他](https://www.microsoft.com/ja-jp/events/search/result.aspx?pg=azure)|
|MSKK 主催・協賛の Azure 関連セミナー・Webinar ②||||||[その他](https://events.microsoft.com/ja-jp/Azure)|
|mstep オンライントレーニング||||||[その他](https://partner.microsoft.com/ja-jp/training/mstep-platform)|
|Power Platform オンラインセミナー情報||||||[その他](https://aka.ms/PPPath)|
|Japan CSS blog 一覧 (日本マイクロソフトサポート情報)|||[Blog](https://cssjpn.github.io/)||||
|Exchange & Outlook サポート|Exchange||[Blog](https://jpmessaging.github.io/blog/)||||
|SharePoint サポート チーム|SharePoint||[Blog](https://jpspsupport.github.io/blog/)||||
|Office サポート チーム フォーラム|Office||[Blog](https://officesupportjp.github.io/blog/)||||
|Microsoft Japan Unified Communication Support Team|Teams||[Blog](https://jpucsupport.github.io/blog/)||||
|Japan Microsoft Intune Support Team|Intune||[Blog](https://jpmem.github.io/blog/)||||
|Japan Azure IaaS and Networking Support Team|Azure IaaS, Networking||[Blog](https://jpaztech.github.io/blog/)||||
|Azure Subscription Management Support Team|Azure Subscription||[Blog](https://jpazasms.github.io/blog/)||||
|Japan CSS ABRS|Azure Backup, ASR, Migrate||[Blog](https://jpabrs-scem.github.io/blog/)||||
|Japan Azure Monitoring Support Blog|Azure Monitor||[Blog](https://jpazmon-integ.github.io/blog/)||||
|Japan Integration Support team|Logic Apps||[Blog](https://jpazinteg.github.io/blog/)||||
|Japan Azure PaaS サポート チーム|Azure PaaS||[Blog](https://aka.ms/jpazpaasblog)||||
|Azure Bot Service サポート チーム|Bot Service||[Blog](https://jpdsi.github.io/blog/)||||
|Japan Azure Identity Support Blog|Azure AD||[Blog](https://jpazureid.github.io/blog/)|[GitHub](https://github.com/jpazureid/blog)|||
|Japan Azure Machine Learning サポート チーム|Azure ML||[Blog](https://jpmlblog.github.io/blog/)||||
|Japan Azure Cognitive Services サポートチーム|Cognitive Services||[Blog](https://jpaiblog.github.io/blog/)||||
|Japan IoT サポートチーム|IoT||[Blog](https://jpiotblog.github.io/blog/)||||
|Microsoft Japan Windows Technology Support Blog|Windows||[Blog](https://jpwinsup.github.io/blog/)||||
|Japan CSS Security Support Blog|Security||[Blog](https://jp-sec.github.io/blog/)||||
|日本のセキュリティ チーム (Japan Security Team)|Security||[Blog](https://aka.ms/jpsecurity/)||||
|Visual Studio サポート チーム|Visual Studio||[Blog](https://jpdscore.github.io/blog/)||||
|Windows SDK サポート チーム|Windows||[Blog](https://jpdscore.github.io/blog/)||||
|ASP.NET サポート チーム|ASP.NET||[Blog](https://jpdsi.github.io/blog/)||||
|Windows Driver Kit サポートチーム|Windows||[Blog](https://jpwdkblog.github.io/blog/)||||
|Edge/Internet Explorer (IE) サポート チーム|Edge||[Blog](https://jpdsi.github.io/blog/)||||
|Internet Information Services (IIS) サポート チーム|IIS||[Blog](https://jpdsi.github.io/blog/)||||
|Microsoft Japan BI Data Platform(SQL) Support Team|Power BI, SQL||[Blog](https://social.technet.microsoft.com/Forums/ja-JP/home?forum=jpbidp)||||
|Power BI サポート チーム|Power BI||[Blog](https://jpbap-sqlbi.github.io/blog/)||||
|Dynamics 365 CRM & Power Platform サポート|D365, PowerPlatform||[Blog](https://jpdynamicscrm.github.io/blog/)||||
|Dynamics 365 Finance and Operations/AX サポート チーム|D365||[Blog](https://jpdynamicserp.github.io/blog/)||||
|Japan FTA (FastTrack for Azure)|FTA|||[GitHub](https://github.com/Azure/fta-japan)|||
|Kusto 100+ knocks (FTA)|FTA|||[GitHub](https://azure.github.io/fta-kusto100knocks/)|||
|MPNJ (Microsoft Partner Network Japan)|Partner|[YouTube](https://www.youtube.com/@MicrosoftPartnerNetworkJapan)|||||
|日本マイクロソフト株式会社 公式チャンネル||[YouTube](https://www.youtube.com/user/microsoftjapanvideos)|||||
|Microsoft Base Blog|||[Blog](https://www.microsoft.com/ja-jp/events/azurebase/blog/)||||
|Industry Blog|||[Blog](https://cloudblogs.microsoft.com/industry-blog/ja-jp/)||||
### 米国本社
|社員またはチーム|タグ|YouTube|Blog|GitHub|Qiita|その他|
|:----|:----|:----|:----|:----|:----|:----|
|Access Blog|||[Blog](https://techcommunity.microsoft.com/t5/access-blog/bg-p/AccessBlog)||||
|AI - Applied AI Blog|||[Blog](https://techcommunity.microsoft.com/t5/ai-applied-ai-blog/bg-p/AppliedAIBlog)||||
|AI - Cognitive Services Blog|||[Blog](https://techcommunity.microsoft.com/t5/ai-cognitive-services-blog/bg-p/CognitiveServicesBlog)||||
|AI - Customer Engineering Team Blog|||[Blog](https://techcommunity.microsoft.com/t5/ai-customer-engineering-team/bg-p/AICustomerEngineeringTeam)||||
|AI - Machine Learning Blog|||[Blog](https://techcommunity.microsoft.com/t5/ai-machine-learning-blog/bg-p/MachineLearningBlog)||||
|Analytics on Azure Blog|||[Blog](https://techcommunity.microsoft.com/t5/analytics-on-azure-blog/bg-p/AnalyticsonAzure)||||
|Apps on Azure Blog|||[Blog](https://techcommunity.microsoft.com/t5/apps-on-azure-blog/bg-p/AppsonAzureBlog)||||
|Ask the Directory Services Team|||[Blog](https://techcommunity.microsoft.com/t5/ask-the-directory-services-team/bg-p/AskDS)||||
|Ask The Performance Team|||[Blog](https://techcommunity.microsoft.com/t5/ask-the-performance-team/bg-p/AskPerf)||||
|Autonomous Systems Blog|||[Blog](https://techcommunity.microsoft.com/t5/autonomous-systems-blog/bg-p/AutonomousSystemsBlog)||||
|Azure App Service Team Blog|||[Blog](https://azure.github.io/AppService/)||||
|Azure Arc Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-arc-blog/bg-p/AzureArcBlog)||||
|Azure Architecture Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-architecture-blog/bg-p/AzureArchitectureBlog)||||
|Azure Communication Services Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-communication-services/bg-p/AzureCommunicationServicesBlog)||||
|Azure Compute Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-compute-blog/bg-p/AzureCompute)||||
|Azure Confidential Computing Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-confidential-computing/bg-p/AzureConfidentialComputingBlog)||||
|Azure Database for MySQL Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-database-for-mysql-blog/bg-p/ADforMySQL)||||
|Azure Database for PostgreSQL Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-database-for-postgresql/bg-p/ADforPostgreSQL)||||
|Azure Database Support Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-database-support-blog/bg-p/AzureDBSupport)||||
|Azure Data Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-data-blog/bg-p/AzureDataBlog)||||
|Azure Data Explorer Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-data-explorer-blog/bg-p/AzureDataExplorer)||||
|Azure Data Factory Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-data-factory-blog/bg-p/AzureDataFactoryBlog)||||
|Azure Developer Community Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-developer-community-blog/bg-p/AzureDevCommunityBlog)||||
|Azure DevOps Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-devops-blog/bg-p/AzureDevOps)||||
|Azure for Operators Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-for-operators-blog/bg-p/AzureforOperatorsBlog)||||
|Azure Global|||[Blog](https://techcommunity.microsoft.com/t5/azure-global/bg-p/AzureCAT)||||
|Azure Governance and Management Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-governance-and-management/bg-p/AzureGovernanceandManagementBlog)||||
|Azure High Performance Computing (HPC) Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-high-performance-computing/bg-p/AzureHighPerformanceComputingBlog)||||
|Azure Infrastructure Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-infrastructure-blog/bg-p/AzureInfrastructureBlog)||||
|Azure Lab Services Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-lab-services-blog/bg-p/AzureLabServicesBlog)||||
|Azure Maps Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-maps-blog/bg-p/AzureMapsBlog)||||
|Azure Marketplace Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-marketplace-blog/bg-p/AzureMarketplaceBlog)||||
|Azure Migration and Modernization Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-migration-and/bg-p/AzureMigrationBlog)||||
|Azure Networking Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-networking-blog/bg-p/AzureNetworkingBlog)||||
|Azure Network Security Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-network-security-blog/bg-p/AzureNetworkSecurityBlog)||||
|Azure Observability Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-observability-blog/bg-p/AzureObservabilityBlog)||||
|Azure PaaS Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-paas-blog/bg-p/AzurePaaSBlog)||||
|Azure Service Fabric Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-service-fabric-blog/bg-p/Service-Fabric)||||
|Azure Space Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-space-blog/bg-p/AzureSpaceBlog)||||
|Azure SQL Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-sql-blog/bg-p/AzureSQLBlog)||||
|Azure Stack Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-stack-blog/bg-p/AzureStackBlog)||||
|Azure Static Web Apps Blog|||[Blog](https://www.azurestaticwebapps.dev/blog)||||
|Azure Storage Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-storage-blog/bg-p/AzureStorageBlog)||||
|Azure Synapse Analytics Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-synapse-analytics-blog/bg-p/AzureSynapseAnalyticsBlog)||||
|Azure Tools Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-tools-blog/bg-p/AzureToolsBlog)||||
|Azure Virtual Desktop Blog|||[Blog](https://techcommunity.microsoft.com/t5/azure-virtual-desktop-blog/bg-p/AzureVirtualDesktopBlog)||||
|Bing Ads API Blog|||[Blog](https://techcommunity.microsoft.com/t5/bing-ads-api-blog/bg-p/AdsAPIBlog)||||
|BizTalk Server Team Blog|||[Blog](https://techcommunity.microsoft.com/t5/biztalk-server-team-blog/bg-p/BizTalkServerTeamBlog)||||
|Community Ninjas Blog|||[Blog](https://techcommunity.microsoft.com/t5/community-ninjas-blog/bg-p/CommunityNinjasBlog)||||
|Configuration Manager Archive|||[Blog](https://techcommunity.microsoft.com/t5/configuration-manager-archive/bg-p/ConfigurationManagerArchive)||||
|Configuration Manager Blog|||[Blog](https://techcommunity.microsoft.com/t5/configuration-manager-blog/bg-p/ConfigurationManagerBlog)||||
|Containers|||[Blog](https://techcommunity.microsoft.com/t5/containers/bg-p/Containers)||||
|Core Infrastructure and Security Blog|||[Blog](https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/bg-p/CoreInfrastructureandSecurityBlog)||||
|Data Architecture Blog|||[Blog](https://techcommunity.microsoft.com/t5/data-architecture-blog/bg-p/DataArchitectureBlog)||||
|Daylight Saving Time & Time Zone|||[Blog](https://techcommunity.microsoft.com/t5/daylight-saving-time-time-zone/bg-p/DSTBlog)||||
|Desenvolvedores BR|||[Blog](https://techcommunity.microsoft.com/t5/desenvolvedores-br/bg-p/DesenvolvedoresBR)||||
|Device Management in Microsoft|||[Blog](https://techcommunity.microsoft.com/t5/device-management-in-microsoft/bg-p/DeviceManagementMicrosoft)||||
|Driving Adoption Blog|||[Blog](https://techcommunity.microsoft.com/t5/driving-adoption-blog/bg-p/DrivingAdoptionBlog)||||
|Education Blog|||[Blog](https://techcommunity.microsoft.com/t5/education-blog/bg-p/EducationBlog)||||
|Educator Developer Blog|||[Blog](https://techcommunity.microsoft.com/t5/educator-developer-blog/bg-p/EducatorDeveloperBlog)||||
|Edutech|||[Blog](https://techcommunity.microsoft.com/t5/edutech/bg-p/Edutech)||||
|Excel Blog|||[Blog](https://techcommunity.microsoft.com/t5/excel-blog/bg-p/ExcelBlog)||||
|Exchange Team Blog|||[Blog](https://techcommunity.microsoft.com/t5/exchange-team-blog/bg-p/Exchange)||||
|Failover Clustering|||[Blog](https://techcommunity.microsoft.com/t5/failover-clustering/bg-p/FailoverClustering)||||
|FastTrack App Assure Blog|||[Blog](https://techcommunity.microsoft.com/t5/fasttrack-app-assure-blog/bg-p/FastTrackAppAssure)||||
|FastTrack Blog|||[Blog](https://techcommunity.microsoft.com/t5/fasttrack-blog/bg-p/FastTrackBlog)||||
|FastTrack for Azure|||[Blog](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/bg-p/FastTrackforAzureBlog)||||
|Financial Services Blog|||[Blog](https://techcommunity.microsoft.com/t5/financial-services-blog/bg-p/FinancialServicesBlog)||||
|FSLogix Blog|||[Blog](https://techcommunity.microsoft.com/t5/fslogix-blog/bg-p/FSLogix-Blog)||||
|Green Tech Blog|||[Blog](https://techcommunity.microsoft.com/t5/green-tech-blog/bg-p/GreenTechBlog)||||
|Hardware Dev Center|||[Blog](https://techcommunity.microsoft.com/t5/hardware-dev-center/bg-p/HardwareDevCenter)||||
|Healthcare and Life Sciences Blog|||[Blog](https://techcommunity.microsoft.com/t5/healthcare-and-life-sciences/bg-p/HealthcareAndLifeSciencesBlog)||||
|Host Integration Blog|||[Blog](https://techcommunity.microsoft.com/t5/host-integration-blog/bg-p/HostIntegrationBlog)||||
|Humans of IT Blog|||[Blog](https://techcommunity.microsoft.com/t5/humans-of-it-blog/bg-p/HoIT-Blog)||||
|Identity Standards Blog|||[Blog](https://techcommunity.microsoft.com/t5/identity-standards-blog/bg-p/IdentityStandards)||||
|IIS Support Blog|||[Blog](https://techcommunity.microsoft.com/t5/iis-support-blog/bg-p/IIS-Support-Blog)||||
|Integrations on Azure Blog|||[Blog](https://techcommunity.microsoft.com/t5/integrations-on-azure-blog/bg-p/IntegrationsonAzureBlog)||||
|Internet of Things Blog|||[Blog](https://techcommunity.microsoft.com/t5/internet-of-things-blog/bg-p/IoTBlog)||||
|Intune Customer Success|||[Blog](https://techcommunity.microsoft.com/t5/intune-customer-success/bg-p/IntuneCustomerSuccess)||||
|ITOps Talk Blog|||[Blog](https://techcommunity.microsoft.com/t5/itops-talk-blog/bg-p/ITOpsTalkBlog)||||
|IT Resources & Training Blog|||[Blog](https://techcommunity.microsoft.com/t5/it-resources-training-blog/bg-p/ITResourcesBlog)||||
|Manufacturing|||[Blog](https://techcommunity.microsoft.com/t5/manufacturing/bg-p/Manufacturing)||||
|Media at Microsoft Blog|||[Blog](https://techcommunity.microsoft.com/t5/media-at-microsoft-blog/bg-p/MediaatMicrosoftBlog)||||
|Messaging on Azure Blog|||[Blog](https://techcommunity.microsoft.com/t5/messaging-on-azure-blog/bg-p/MessagingonAzureBlog)||||
|Microsoft 365 Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-365-blog/bg-p/microsoft_365blog)||||
|Microsoft 365 Defender Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-365-defender-blog/bg-p/MicrosoftThreatProtectionBlog)||||
|Microsoft Bluetooth Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-bluetooth-blog/bg-p/MicrosoftBluetoothBlog)||||
|Microsoft Bookings Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-bookings-blog/bg-p/Office365BusinessAppsBlog)||||
|Microsoft Data Migration Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-data-migration-blog/bg-p/MicrosoftDataMigration)||||
|Microsoft Defender for Cloud Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/bg-p/MicrosoftDefenderCloudBlog)||||
|Microsoft Defender for Endpoint Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-defender-for-endpoint/bg-p/MicrosoftDefenderATPBlog)||||
|Microsoft Defender for IoT Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-defender-for-iot-blog/bg-p/MicrosoftDefenderIoTBlog)||||
|Microsoft Defender for Office 365 Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-defender-for-office/bg-p/MicrosoftDefenderforOffice365Blog)||||
|Microsoft Defender Threat Intelligence Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-defender-threat/bg-p/DefenderThreatIntelligence)||||
|Microsoft Defender Vulnerability Management Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-defender-vulnerability/bg-p/Vulnerability-Management)||||
|Microsoft  Edge Insider|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-edge-insider/bg-p/MicrosoftEdgeInsider)||||
|Microsoft Entra (Azure AD) Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/bg-p/Identity)||||
|Microsoft Forms Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-forms-blog/bg-p/MicrosoftFormsBlog)||||
|Microsoft Intune Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-intune-blog/bg-p/MicrosoftEndpointManagerBlog)||||
|Microsoft Learn Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-learn-blog/bg-p/MicrosoftLearnBlog)||||
|Microsoft Managed Desktop Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-managed-desktop-blog/bg-p/MicrosoftManagedDesktop)||||
|Microsoft Mechanics Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-mechanics-blog/bg-p/MicrosoftMechanicsBlog)||||
|Microsoft MVP Award Program Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-mvp-award-program-blog/bg-p/MVPAwardProgramBlog)||||
|Microsoft OneDrive Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-onedrive-blog/bg-p/OneDriveBlog)||||
|Microsoft Purview Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-purview-blog/bg-p/AzurePurviewBlog)||||
|Microsoft Search Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-search-blog/bg-p/IntelligentSearch_DiscoveryBlog)||||
|Microsoft Security Baselines Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-security-baselines/bg-p/Microsoft-Security-Baselines)||||
|Microsoft Security Experts|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-security-experts/bg-p/MicrosoftSecurityExperts)||||
|Microsoft Sensors Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-sensors-blog/bg-p/MicrosoftSensorsBlog)||||
|Microsoft Sentinel Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/bg-p/MicrosoftSentinelBlog)||||
|Microsoft SharePoint Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-sharepoint-blog/bg-p/SPBlog)||||
|Microsoft Stream Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-stream-blog/bg-p/StreamBlog)||||
|Microsoft Syntex|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-syntex/bg-p/MicrosoftSyntexBlog)||||
|Microsoft Teams Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-teams-blog/bg-p/MicrosoftTeamsBlog)||||
|Microsoft Teams Community Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-teams-community-blog/bg-p/MicrosoftTeamsCommunityBlog)||||
|Microsoft Teams Support|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-teams-support/bg-p/MicrosoftTeamsSupport)||||
|Microsoft Tech Talks|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-tech-talks/bg-p/TechTalksBlog)||||
|Microsoft To Do Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-to-do-blog/bg-p/To-DoBlog)||||
|Microsoft USB Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-usb-blog/bg-p/MicrosoftUSBBlog)||||
|Microsoft Viva Blog|||[Blog](https://techcommunity.microsoft.com/t5/microsoft-viva-blog/bg-p/MicrosoftVivaBlog)||||
|Mixed Reality Blog|||[Blog](https://techcommunity.microsoft.com/t5/mixed-reality-blog/bg-p/TheMixedRealityBlog)||||
|Mixed Reality Partners|||[Blog](https://techcommunity.microsoft.com/t5/mixed-reality-partners/bg-p/MixedRealityPartnersBlog)||||
|Modernization Best Practices and Reusable Assets Blog|||[Blog](https://techcommunity.microsoft.com/t5/modernization-best-practices-and/bg-p/ModernizationBestPracticesBlog)||||
|Networking Blog|||[Blog](https://techcommunity.microsoft.com/t5/networking-blog/bg-p/NetworkingBlog)||||
|NTA Techies|||[Blog](https://techcommunity.microsoft.com/t5/nta-techies/bg-p/NTATechiesblog-board)||||
|Office 365 Blog|||[Blog](https://techcommunity.microsoft.com/t5/office-365-blog/bg-p/Office365Blog)||||
|Office End Of Support Blog|||[Blog](https://techcommunity.microsoft.com/t5/office-end-of-support-blog/bg-p/OfficeEOS)||||
|Outlook Blog|||[Blog](https://techcommunity.microsoft.com/t5/outlook-blog/bg-p/Outlook)||||
|Outlook Global Customer Service & Support Team Blog|||[Blog](https://techcommunity.microsoft.com/t5/outlook-global-customer-service/bg-p/OutlookGlobalCustomerService)||||
|Planner Blog|||[Blog](https://techcommunity.microsoft.com/t5/planner-blog/bg-p/PlannerBlog)||||
|Project Blog|||[Blog](https://techcommunity.microsoft.com/t5/project-blog/bg-p/ProjectBlog)||||
|Project Support Blog|||[Blog](https://techcommunity.microsoft.com/t5/project-support-blog/bg-p/ProjectSupport)||||
|Public Sector Blog|||[Blog](https://techcommunity.microsoft.com/t5/public-sector-blog/bg-p/PublicSectorBlog)||||
|Running SAP Applications on the Microsoft Platform|||[Blog](https://techcommunity.microsoft.com/t5/running-sap-applications-on-the/bg-p/SAPApplications)||||
|Security, Compliance, and Identity Blog|||[Blog](https://techcommunity.microsoft.com/t5/security-compliance-and-identity/bg-p/MicrosoftSecurityandCompliance)||||
|SharePointDsc Blog|||[Blog](https://techcommunity.microsoft.com/t5/sharepointdsc-blog/bg-p/SharePointDsc)||||
|Skype for Business Blog|||[Blog](https://techcommunity.microsoft.com/t5/skype-for-business-blog/bg-p/Skype_for_Business_Blog)||||
|Skype for Business Ignite Blog|||[Blog](https://techcommunity.microsoft.com/t5/skype-for-business-ignite-blog/bg-p/SkypeforBusinessIgniteBlog)||||
|Small and Medium Business Blog|||[Blog](https://techcommunity.microsoft.com/t5/small-and-medium-business-blog/bg-p/Microsoft365BusinessBlog)||||
|Small Basic Blog|||[Blog](https://techcommunity.microsoft.com/t5/small-basic-blog/bg-p/SmallBasic)||||
|SQL Server Blog|||[Blog](https://techcommunity.microsoft.com/t5/sql-server-blog/bg-p/SQLServer)||||
|SQL Server Integration Services (SSIS) Blog|||[Blog](https://techcommunity.microsoft.com/t5/sql-server-integration-services/bg-p/SSIS)||||
|SQL Server Support Blog|||[Blog](https://techcommunity.microsoft.com/t5/sql-server-support-blog/bg-p/SQLServerSupport)||||
|Storage at Microsoft|||[Blog](https://techcommunity.microsoft.com/t5/storage-at-microsoft/bg-p/FileCAB)||||
|Student Developer Blog|||[Blog](https://techcommunity.microsoft.com/t5/student-developer-blog/bg-p/StudentDeveloperBlog)||||
|Surface IT Pro Blog|||[Blog](https://techcommunity.microsoft.com/t5/surface-it-pro-blog/bg-p/SurfaceITPro)||||
|Sysinternals Blog|||[Blog](https://techcommunity.microsoft.com/t5/sysinternals-blog/bg-p/Sysinternals-Blog)||||
|System Center Blog|||[Blog](https://techcommunity.microsoft.com/t5/system-center-blog/bg-p/SystemCenterBlog)||||
|Tech Community Blog|||[Blog](https://techcommunity.microsoft.com/t5/tech-community-blog/bg-p/WeeklyRoundupBlog)||||
|Test Base Blog|||[Blog](https://techcommunity.microsoft.com/t5/test-base-blog/bg-p/USL-Blog)||||
|TestingSpot Blog|||[Blog](https://techcommunity.microsoft.com/t5/testingspot-blog/bg-p/TestingSpotBlog)||||
|Universal Print Blog|||[Blog](https://techcommunity.microsoft.com/t5/universal-print-blog/bg-p/UniversalPrintBlog)||||
|Virtualization|||[Blog](https://techcommunity.microsoft.com/t5/virtualization/bg-p/Virtualization)||||
|Windows Admin Center Blog|||[Blog](https://techcommunity.microsoft.com/t5/windows-admin-center-blog/bg-p/Windows-Admin-Center-Blog)||||
|Windows Blog Archive|||[Blog](https://techcommunity.microsoft.com/t5/windows-blog-archive/bg-p/Windows-Blog-Archive)||||
|Windows Dev AppConsult|||[Blog](https://techcommunity.microsoft.com/t5/windows-dev-appconsult/bg-p/WindowsDevAppConsult)||||
|Windows Hardware Certification|||[Blog](https://techcommunity.microsoft.com/t5/windows-hardware-certification/bg-p/WindowsHardwareCertification)||||
|Windows IT Pro Blog|||[Blog](https://techcommunity.microsoft.com/t5/windows-it-pro-blog/bg-p/Windows10Blog)||||
|Windows Kernel Internals Blog|||[Blog](https://techcommunity.microsoft.com/t5/windows-kernel-internals-blog/bg-p/WindowsKernelInternals)||||
|Windows Server Essentials and Small Business Server|||[Blog](https://techcommunity.microsoft.com/t5/windows-server-essentials-and/bg-p/SBS)||||
|Windows Server News and Best Practices|||[Blog](https://techcommunity.microsoft.com/t5/windows-server-news-and-best/bg-p/WindowsServerNewsandBestPractices)||||
|WinHEC Online Blog|||[Blog](https://techcommunity.microsoft.com/t5/winhec-online-blog/bg-p/WinHECOnlineBlog)||||
|Yammer Blog|||[Blog](https://techcommunity.microsoft.com/t5/yammer-blog/bg-p/YammerBlog)||||
|MCP 試験対策サイト （※ 英語だが日本語字幕が可能）||||||[その他](https://learn.microsoft.com/ja-jp/shows/exam-readiness-zone/)|


## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.