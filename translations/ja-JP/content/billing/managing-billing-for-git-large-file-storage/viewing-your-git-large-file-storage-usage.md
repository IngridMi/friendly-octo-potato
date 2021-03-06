---
title: Git Large File Storage の使用状況を表示する
intro: 'アカウントの毎月の帯域幅容量と {% data variables.large_files.product_name_short %} の残りの容量を監査できます。'
redirect_from:
  - /github/setting-up-and-managing-billing-and-payments-on-github/viewing-your-git-large-file-storage-usage
  - /articles/viewing-storage-and-bandwidth-usage-for-a-personal-account/
  - /articles/viewing-storage-and-bandwidth-usage-for-an-organization/
  - /articles/viewing-your-git-large-file-storage-usage
  - /github/setting-up-and-managing-billing-and-payments-on-github/managing-billing-for-git-large-file-storage/viewing-your-git-large-file-storage-usage
versions:
  fpt: '*'
  ghec: '*'
type: how_to
topics:
  - LFS
  - Organizations
  - User account
shortTitle: Git LFSの使用状況の表示
---

{% data reusables.large_files.owner_quota_only %} {% data reusables.large_files.does_not_carry %}

## 個人アカウントのストレージと帯域幅の使用状況を表示する

{% data reusables.user_settings.access_settings %}
{% data reusables.user_settings.billing_plans %}
{% data reusables.dotcom_billing.lfs-data %}

## Organization のストレージと帯域幅の使用状況を表示する

{% data reusables.dotcom_billing.org-billing-perms %}

{% data reusables.organizations.billing-settings %}
{% data reusables.dotcom_billing.lfs-data %}

## 参考リンク

- 「[ストレージと帯域の利用について](/articles/about-storage-and-bandwidth-usage)」
- 「[{% data variables.large_files.product_name_long %} をアップグレードする](/articles/upgrading-git-large-file-storage/)」
