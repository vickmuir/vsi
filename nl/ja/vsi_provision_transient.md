---



copyright:
  years: 2017, 2018
lastupdated: "2018-02-28"


---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:tip: .tip}
{:table: .aria-labeledby="caption"}

# 一時インスタンスのプロビジョニング
{: #ordering-vs-transient}
一時仮想サーバー・インスタンスは、{{site.data.keyword.slportal_full}}からプロビジョンできます。
{:shortdesc}

## 始めに
始めに、以下の前提条件を確認してください。

  1. {{site.data.keyword.slportal}}の資格情報がセットアップ済みであることを確認します。

  2. 仮想サーバー・インスタンスの容量に関する考慮事項を確認します。詳しくは、[容量に関する考慮事項](ts_capacity_bp.html)を参照してください。

## ログイン
必ず{{site.data.keyword.slportal}}にログインしてください。

  1. ユーザー固有の資格情報を使用して、[{{site.data.keyword.slportal}} ![「外部リンク」アイコン](../icons/launch-glyph.svg "「外部リンク」アイコン")](https://control.softlayer.com/){: new_window} にアクセスします。

{{site.data.keyword.slportal}}のメインページが開きます。

## 一時仮想サーバー・インスタンスのプロビジョニング
{: #ordering-transient-instance}
前提条件を満たしたら、一時仮想サーバー・インスタンスをプロビジョンします。一時インスタンスのプロビジョニングは、**「デバイス」**メニューを使用するか、**「デバイス」**アイコンを使用するかの 2 つの方法で実行できます。

### 「デバイス」アイコンを使用した一時仮想サーバー・インスタンスのプロビジョニング
*「デバイス」*アイコンを使用して一時仮想サーバー・インスタンスをプロビジョンするには、以下のステップを実行します。

1.  {{site.data.keyword.slportal}}から、**「オーダー」**セクションを見つけ、**「デバイス」**をクリックします。
2.  *「デバイス」*ページの*「パブリック仮想サーバー」*で、仮想サーバー・オファリングの**「一時 (Transient)」**をクリックします。
3.  *「クラウド・サーバーの構成」*ページで、すべての関連情報を入力します。
4.  **「注文に追加」**をクリックして続行します。
5.  サーバーのドメイン情報を確認または編集します。
5.  **「クラウド・サービスのご利用条件」**チェック・ボックスと**「サード・パーティー・サービスのご使用条件」**チェック・ボックスをクリックします。
6.  支払情報を確認または入力し、**「注文の送信」**をクリックします。プロビジョニングのオーダー番号を含む画面にリダイレクトされます。 この画面は、プロビジョニングの注文の受信を示すものでもあるため、印刷できます。

 一連の E メール (プロビジョニング・オーダーの確認応答、プロビジョニング・オーダーの承認と処理、およびプロビジョニング完了) が管理者に送信されます。 プロビジョニング完了の E メールには、*「デバイスの詳細」*ページへのリンクが含まれています。

### 「デバイス」メニューを使用した一時仮想サーバー・インスタンスのプロビジョニング
{: #ordering-transient-devices-menu}

{{site.data.keyword.slportal}}のメインページの*「デバイス」*メニューを使用して一時仮想サーバー・インスタンスをプロビジョンすることもできます。

1. **「デバイス」>「デバイス・リスト」**をクリックします。

   「デバイス」ページに、ユーザーのアカウント内のすべてのデバイス・タイプ (専用ホスト、仮想サーバー、ベア・メタル・サーバー、および NetScaler アプリケーション・デリバリー・コントローラー) が表示されます。
2. 右上隅の**「デバイスの注文」**リンクをクリックします。
3. *「デバイス」*ページの*「パブリック仮想サーバー」*で、仮想サーバー・オファリングの**「一時 (Transient)」**をクリックします。
4. *「クラウド・サーバーの構成」*ページで、すべての関連情報を入力します。
5. **「注文に追加」**をクリックして続行します。
6. サーバーのドメイン情報を確認または編集します。
7. **「クラウド・サービスのご利用条件」**チェック・ボックスと**「サード・パーティー・サービスのご使用条件」**チェック・ボックスをクリックします。
8. 支払情報を確認または入力し、**「注文の送信」**をクリックします。プロビジョニングのオーダー番号を含む画面にリダイレクトされます。 この画面は、プロビジョニングの注文の受信を示すものでもあるため、印刷できます。

一連の E メール (プロビジョニング・オーダーの確認応答、プロビジョニング・オーダーの承認と処理、およびプロビジョニング完了) が管理者に送信されます。 プロビジョニング完了の E メールには、*「デバイスの詳細」*ページへのリンクが含まれています。

{{site.data.keyword.slapi_short}} を使用して一時仮想サーバーをプロビジョンすることもできます。例については[Create Object を使用した一時インスタンスのプロビジョニング](../vsi/vsi_provision_api.html#api-rest-transient)を参照してください。
{:tip}

## 次のステップ
仮想サーバーがプロビジョンされたら、その管理を開始できます。 詳しくは、[仮想サーバーの管理](../vsi/vsi_managing.html)を参照してください。