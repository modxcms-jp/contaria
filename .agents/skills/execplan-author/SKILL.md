# execplan-author

## 目的

`ROADMAP.md`、`PLANS.md`、関連要件を読み、着手可能な個別 ExecPlan を起こす。

## 使うタイミング

- 小さな修正ではない
- 対応対象が `ROADMAP.md` にある
- まだ個別 ExecPlan がない、または雛形のまま止まっている

## 手順

1. `ROADMAP.md` で対象 ID、依存、状態を確認する
2. `PLANS.md` を読み、必須項目を落とさない
3. `docs/requirements.md` と関連ファイルを読み、対象範囲と非対象を切り分ける
4. `docs/execplans/NNN-*.md` を作成または更新する
5. Progress を日本時間 `YYYY-MM-DD HH:MM JST` で記録する

## チェックポイント

- ExecPlan 単体で着手可能か
- 変更ファイル、検証手順、完了条件が具体的か
- 責務分割と非対象が明示されているか
