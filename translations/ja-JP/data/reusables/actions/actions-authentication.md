This API is available for authenticated users, {% data variables.product.prodname_oauth_apps %}, and {% data variables.product.prodname_github_apps %}. アクセストークンには、プライベートリポジトリなら[`repo`スコープ](/apps/building-oauth-apps/understanding-scopes-for-oauth-apps/#available-scopes)が、{% ifversion ghae %}Enterpriseの全員が利用できるインターナルリポジトリ{% else %}パブリックリポジトリ{% endif %}なら[`public_repo`スコープ](/apps/building-oauth-apps/understanding-scopes-for-oauth-apps/#available-scopes)が必要です。