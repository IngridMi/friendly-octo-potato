{% ifversion fpt or ghec %}GitHub ActionsでOAuthアプリケーションを使っていて、ワークフローファイルを変更したいなら、OAuthトークンは`workflow`スコープを持っていなければならず、ユーザはワークフローファイルを含むリポジトリへのオーナーもしくは書き込み権限を持っていなければなりません。 詳しい情報については「[OAuthアプリケーションのスコープを理解する](/apps/building-oauth-apps/understanding-scopes-for-oauth-apps/#available-scopes)」を参照してください。{% endif %}