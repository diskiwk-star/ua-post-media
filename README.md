# ua-post-media

UaFloors のInstagram投稿画像の配信用リポジトリです（公開。InstagramのAPIが画像URLとして参照するため）。
キュー登録は `🌲UA/instagram/prepare_post.py` が行い、GitHub Actions が投稿します。
投稿済みの素材は自動で削除されます。正本は手元の `instagram/投稿素材/` です。
