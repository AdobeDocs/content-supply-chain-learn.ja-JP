---
title: アセット管理チュートリアル
description: 計画プロセスを通じてコンテンツの作成と完了に至るまで、コンテンツ要件を結び付けて追跡することに苦労している企業の場合。 プロジェクト全体にわたって効果的なプロセス、計画、承認、データの整合性が欠如しているため、この企業のコンテンツ・サプライ・チェーンでは、生産性と効率性の両方が損なわれています。
solution: Experience Cloud, Experience Manager Assets
feature-set: Experience Manager, Experience Manager Assets
feature: Asset Management, Asset Processing
topic: Content Management, Collaboration, Artificial Intelligence
role: Admin, User, Leader, Developer
level: Beginner
last-substantial-update: 2024-03-06T00:00:00Z
jira: KT-15076
exl-id: 61a02beb-7869-408b-8024-31e8b46f9f7a
source-git-commit: 32c8aba7f65e8eb72f52c532a623df52d1473ffd
workflow-type: tm+mt
source-wordcount: '1075'
ht-degree: 17%

---

# アセット管理チュートリアル

ブランドの一貫性を確保しながら、1 つのクラウドベースのソリューションから数百万のアセットに簡単にアクセスして再利用できます。  これらのチュートリアルでは、Adobe Experience Manager Assetsの使用に重点を置いています。


>[!TIP]
>
>アドビのAdobe製品のエキスパートチームは、コンテンツサプライチェーンの主要なユースケースに関する統合チュートリアルのコレクションを作成しました。 複数のソリューションを使用している場合は、それらを統合する最適な方法を学びます。  [ コンテンツサプライチェーン統合チュートリアル ](https://experienceleague.adobe.com/docs/integrations-learn/experience-cloud/solution-categories/content-supply-chain.html?lang=en) をご覧ください。

## おすすめのコース

<div class="columns is-multiline">
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets - Assets View] Bulk Import - Feature Video" tabIndex="0">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html?lang=ja" title="[AEM Assets - Assets表示 ] 一括読み込み – 機能ビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3426857?format=jpeg" alt="[AEM Assets - Assets表示 ] 一括読み込み – 機能ビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html?lang=ja" title="[AEM Assets - Assets表示 ] 一括読み込み – 機能ビデオ">[AEM Assets - Assets表示 ] 一括読み込み – 機能ビデオ </a>
          </p>
          <p class="is-size-6">一括読み込み機能を使用して多数のファイルをAEM Assetsに読み込む方法を説明します。Dropboxは、明確でわかりやすい統合プロセスを実現するサンプルクラウドストレージプロバイダーとして機能します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/bulk-import.html?lang=ja" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細を表示 </span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Asset Essentials][Workfront] Assets Essentials and Workfront integration - Catalog" tabIndex="1">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/overview.html" title="[Asset Essentials][Workfront]Assets EssentialsとWorkfrontの統合 – カタログ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3422184?format=jpeg" alt="[Asset Essentials][Workfront]Assets EssentialsとWorkfrontの統合 – カタログ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/overview.html" title="[Asset Essentials][Workfront]Assets EssentialsとWorkfrontの統合 – カタログ">[Asset Essentials][Workfront] Assets EssentialsとWorkfrontの統合 – カタログ </a>
          </p>
          <p class="is-size-6">WorkfrontとAssets Essentialsを統合する方法について説明します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/overview.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細を表示 </span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets] Adobe Express integration - Feature Video" tabIndex="2">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-express-aem-assets-add-on.html" title="[AEM Assets] Adobe Expressの統合 – 機能ビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3425193?format=jpeg" alt="[AEM Assets] Adobe Expressの統合 – 機能ビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-express-aem-assets-add-on.html" title="[AEM Assets] Adobe Expressの統合 – 機能ビデオ">[AEM Assets] Adobe Expressの統合 – 機能ビデオ </a>
          </p>
          <p class="is-size-6">AEM Assets と Adobe Express を使用してコンテンツのサプライチェーンを最適化し、すべてのチームメンバーの生産性とアクセシビリティを向上させる方法について説明します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-express-aem-assets-add-on.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細を表示 </span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Adobe Express] Empower marketing teams to create multi-channel content - Feature video" tabIndex="3">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expressusecase/multi-channel-marketing-content.html" title="[Adobe Express] マーケティングチームがマルチチャネルコンテンツを作成できるようにする – 特集ビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/3424446?format=jpeg" alt="[Adobe Express] マーケティングチームがマルチチャネルコンテンツを作成できるようにする – 特集ビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expressusecase/multi-channel-marketing-content.html" title="[Adobe Express] マーケティングチームがマルチチャネルコンテンツを作成できるようにする – 特集ビデオ">[Adobe Express] マーケティングチームがマルチチャネルコンテンツを作成できるようにする – 機能ビデオ </a>
          </p>
          <p class="is-size-6">イベントマーケティングチームが一意のコンテンツを作成して、オンラインイベントの視聴者を引き付ける方法を説明します。 このワークフローでは、B2B マーケターは、ブランドキットとライブラリのテンプレートを使用して、Adobe Expressで新しいプロジェクトを開始します。 B2B マーケターは、様々なソーシャルチャネルと web チャネルのバリエーションを作成し、ソーシャルメディアとビデオホスティングプラットフォームでコンテンツを共有します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/expressoverview/expressusecase/multi-channel-marketing-content.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細を表示 </span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets] Workfront Enhanced Integration Basics - Feature Video" tabIndex="4">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html?lang=ja" title="[AEM Assets] Workfront拡張統合の基本 – 機能に関するビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/337575?format=jpeg" alt="[AEM Assets] Workfront拡張統合の基本 – 機能に関するビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html?lang=ja" title="[AEM Assets] Workfront拡張統合の基本 – 機能に関するビデオ">[AEM Assets] Workfront拡張統合の基本 – 機能に関するビデオ </a>
          </p>
          <p class="is-size-6">アセットとフォルダーのリンク、メタデータマッピングの定義、AEMへのアセットの送信、アセットのバージョン設定、アセットの自動公開の方法など、Adobe WorkfrontとExperience Manager Assetsの拡張統合の基本について説明します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/basics.html?lang=ja" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細を表示 </span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets] AEM and Adobe Asset Link Creative Workflow - Value Video" tabIndex="5">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-asset-link.html" title="[AEM Assets] AEMとAdobe Asset Link のクリエイティブワークフロー – 価値ビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/335927?format=jpeg" alt="[AEM Assets] AEMとAdobe Asset Link のクリエイティブワークフロー – 価値ビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-asset-link.html" title="[AEM Assets] AEMとAdobe Asset Link のクリエイティブワークフロー – 価値ビデオ">[AEM Assets] AEMおよびAdobe Asset Link クリエイティブワークフロー – 価値ビデオ </a>
          </p>
          <p class="is-size-6">AAL とAAMを使用したユーザーのクリエイティブワークフローを示すビデオ</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/adobe-asset-link.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細を表示 </span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AJO] Create content with the Email Designer - Feature Video" tabIndex="6">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/email-channel/create-content-with-the-email-designer.html" title="[AJO] メールDesignerでコンテンツを作成 – 機能ビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/334150?format=jpeg" alt="[AJO] メールDesignerでコンテンツを作成 – 機能ビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/email-channel/create-content-with-the-email-designer.html" title="[AJO] メールDesignerでコンテンツを作成 – 機能ビデオ">[AJO] メールDesignerでのコンテンツ作成 – 機能ビデオ </a>
          </p>
          <p class="is-size-6">メールを一から作成する方法を学習します。AEM Assets Essentials ライブラリのアセットの使用方法、レスポンシブメールデザインの編集方法、テンプレートからのメールの作成方法について説明します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/email-channel/create-content-with-the-email-designer.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細を表示 </span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Asset Essentials] Getting started with Assets Essentials - Feature Video" tabIndex="7">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/getting-started.html?lang=ja" title="[Asset Essentials] Assets Essentialsの概要 – 機能ビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/336005?format=jpeg" alt="[Asset Essentials] Assets Essentialsの概要 – 機能ビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/getting-started.html?lang=ja" title="[Asset Essentials] Assets Essentialsの概要 – 機能ビデオ">[Asset Essentials] Assets Essentialsの基本を学ぶ – 機能に関するビデオ </a>
          </p>
          <p class="is-size-6">Assets Essentialsが直感的で使いやすいユーザーインターフェイスを提供し、アセットや関連情報を見つけやすく、覚えやすくする仕組みを説明します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/getting-started.html?lang=ja" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細を表示 </span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[AEM Assets] Content Automation - Value video" tabIndex="8">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/content-automation/overview.html" title="[AEM Assets] コンテンツ自動処理 – 価値ビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/333197?format=jpeg" alt="[AEM Assets] コンテンツ自動処理 – 価値ビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/content-automation/overview.html" title="[AEM Assets] コンテンツ自動処理 – 価値ビデオ">[AEM Assets] コンテンツ自動処理 – 価値に関するビデオ </a>
          </p>
          <p class="is-size-6">概要は、Adobe Experience Manager Assets コンテンツ自動処理機能で Photoshop と Lightroom の機能を適用する場合のものです。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/content-automation/overview.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細を表示 </span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Metadata profiles - Feature Video" tabIndex="9">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/ja/docs/experience-manager-learn/assets/configuring/metadata-profiles" title="[Assets] メタデータプロファイル – 機能ビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/33974?format=jpeg" alt="[Assets] メタデータプロファイル – 機能ビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/ja/docs/experience-manager-learn/assets/configuring/metadata-profiles" title="[Assets] メタデータプロファイル – 機能ビデオ">[Assets] メタデータプロファイル – 機能ビデオ </a>
          </p>
          <p class="is-size-6">メタデータプロファイルを使用すると、デフォルトのメタデータをアセットフォルダー内のアセットに自動的に適用でき、AEM ユーザーに対するメタデータ管理の負担を軽減し、メタデータの一貫性を向上できます。</p>
        </div>
        <a href="https://experienceleague.adobe.com/ja/docs/experience-manager-learn/assets/configuring/metadata-profiles" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細を表示 </span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Navigation - Feature Video" tabIndex="10">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/navigation.html" title="[Assets] ナビゲーション – 特集ビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/32046?format=jpeg" alt="[Assets] ナビゲーション – 特集ビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/navigation.html" title="[Assets] ナビゲーション – 特集ビデオ">[Assets] ナビゲーション – 機能ビデオ </a>
          </p>
          <p class="is-size-6">AEM Assets内を移動するための基本を探索します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/navigation.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細を表示 </span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Comments and Annotations - Feature Video" tabIndex="11">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/collaboration/comments-and-annotations.html" title="[Assets] コメントと注釈 – 機能ビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/32049?format=jpeg" alt="[Assets] コメントと注釈 – 機能ビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/collaboration/comments-and-annotations.html" title="[Assets] コメントと注釈 – 機能ビデオ">[Assets] コメントと注釈 – 機能ビデオ </a>
          </p>
          <p class="is-size-6">AEM でコメントと注釈を使用して、アセットに関するコミュニケーションと共同作業を行う方法について説明します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/collaboration/comments-and-annotations.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細を表示 </span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Search - Feature Video" tabIndex="12">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://docs.adobe.com/content/help/en/experience-manager-learn/assets/search-and-discovery/search.html" title="[Assets] 検索 – 特集ビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/32054?format=jpeg" alt="[Assets] 検索 – 特集ビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://docs.adobe.com/content/help/en/experience-manager-learn/assets/search-and-discovery/search.html" title="[Assets] 検索 – 特集ビデオ">[Assets] 検索 – 特集ビデオ </a>
          </p>
          <p class="is-size-6">AEM のオムニサーチを使用してアセットをすばやく検出する方法を説明します。</p>
        </div>
        <a href="https://docs.adobe.com/content/help/en/experience-manager-learn/assets/search-and-discovery/search.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細を表示 </span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Download - Feature Video" tabIndex="13">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/download.html" title="[Assets] のダウンロード – 特集ビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/35090?format=jpeg" alt="[Assets] のダウンロード – 特集ビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/download.html" title="[Assets] のダウンロード – 特集ビデオ">[Assets] ダウンロード – 機能ビデオ </a>
          </p>
          <p class="is-size-6">アセットとそのレンディションをローカルマシンにダウンロードして、使用および共有する方法を説明します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/download.html" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細を表示 </span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] AEM Desktop App 2.0 - Feature Video" tabIndex="14">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/aem-desktop-app.html?lang=ja" title="[Assets] AEM デスクトップアプリ 2.0 – 機能に関するビデオ" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/28868?format=jpeg" alt="[Assets] AEM デスクトップアプリ 2.0 – 機能に関するビデオ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/aem-desktop-app.html?lang=ja" title="[Assets] AEM デスクトップアプリ 2.0 – 機能に関するビデオ">[Assets] AEM デスクトップアプリ 2.0 – 機能に関するビデオ </a>
          </p>
          <p class="is-size-6">AEM Desktop App を使用すると、デスクトップ上で管理されるあらゆるアセットに対し、あらゆるアプリケーションおよびファイル形式で簡単にアクセスできます。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/creative-workflows/aem-desktop-app.html?lang=ja" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細を表示 </span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] DM Smart Image Crop - Feature Video " tabIndex="15">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/dynamic-media/images/smart-crop-feature-video-use.html?lang=ja" title="[Assets] DM スマート画像切り抜き – 特集ビデオ " tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/21519?format=jpeg" alt="[Assets] DM スマート画像切り抜き – 特集ビデオ ">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/dynamic-media/images/smart-crop-feature-video-use.html?lang=ja" title="[Assets] DM スマート画像切り抜き – 特集ビデオ ">[Assets] DM スマート画像切り抜き – 機能ビデオ </a>
          </p>
          <p class="is-size-6">スマート切り抜きでは Adobe Sensei を使用して、レスポンシブデザインでのコンテンツの切り抜きにおける時間とコストのかかるタスクを排除します。</p>
        </div>
        <a href="https://experienceleague.adobe.com/docs/experience-manager-learn/assets/dynamic-media/images/smart-crop-feature-video-use.html?lang=ja" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細を表示 </span>
        </a>
      </div>
    </div>
  </div>
  <div class="column is-half-tablet is-half-desktop is-one-third-widescreen" aria-label="[Assets] Asset Source File Translation - Feature Video" tabIndex="16">
    <div class="card" style="height: 100%; display: flex; flex-direction: column; height: 100%;">
      <div class="card-image">
        <figure class="image x-is-16by9">
          <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/translation/source-file-translation-feature-video-use" title="[Assets] Asset Sourceのファイル翻訳機能の動画" tabindex="-1">
            <img class="is-bordered-r-small" src="https://video.tv.adobe.com/v/18331?format=jpeg" alt="[Assets] Asset Sourceのファイル翻訳機能の動画">
          </a>
        </figure>
      </div>
      <div class="card-content is-padded-small" style="display: flex; flex-direction: column; flex-grow: 1; justify-content: space-between;">
        <div class="top-card-content">
          <p class="headline is-size-6 has-text-weight-bold">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/translation/source-file-translation-feature-video-use" title="[Assets] Asset Sourceのファイル翻訳機能の動画">[Assets] Asset Source ファイル翻訳 – 機能に関するビデオ </a>
          </p>
          <p class="is-size-6">Adobe Experience Manager（AEM）Assetsでは、共通の属性を持つアセットを特定し、新しい関連Assets機能を使用して、それらのアセットを関連アセットとしてマークすることができます。</p>
        </div>
        <a href="https://experienceleague.adobe.com/en/docs/experience-manager-learn/assets/translation/source-file-translation-feature-video-use" class="spectrum-Button spectrum-Button--outline spectrum-Button--primary spectrum-Button--sizeM" style="align-self: flex-start; margin-top: 1rem;">
          <span class="spectrum-Button-label has-no-wrap has-text-weight-bold"> 詳細を表示 </span>
        </a>
      </div>
    </div>
  </div>
</div>

## その他のリソース

* [Experience League イベント ](https://experienceleague.adobe.com/events/)
* [ コンテンツのサプライチェーンに関するAdobe](https://business.adobe.com/resources/webinars/adobe-on-the-content-supply-chain.html)
