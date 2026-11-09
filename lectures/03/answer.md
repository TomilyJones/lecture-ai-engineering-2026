# 第3回 解答

## 演習

- 第1回（素のLLM）とエージェントの回答の違い：具体的な回答がある。
- `--trace` で見えたツール呼び出し（ツール名と引数）：search_glossary、query
- 1つの質問での LLM 呼び出し回数（`requests`）：2
- 追加したツールと、docstring に書いた説明：make_quiz、いつ使って目的は何か。

## 宿題

- 取り組んだレベル：基礎
- やったこと：INSTRUCTIONSの関係する回の行を削除し、docstringsのqueryを2つ読み込むようにした。
- 結果：回の表示が消え、queryにLoRAとQLoRAが一度に送られた。
- 気づき・疑問：queryは一度に一つの方がいいのか。