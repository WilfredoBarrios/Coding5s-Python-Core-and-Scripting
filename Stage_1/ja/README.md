# 🧪 Python Core & Scripting インタラクティブ・ラボ — 日本語 🇯🇵

[![Livebook](https://img.shields.io/badge/Livebook-FF6B6B?logo=livebook&logoColor=white)](https://livebook.dev)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **ただ読むだけでなく、コードを書きながら Python を学ぶ。**
> 本教材は、Livebook のインタラクティブな環境を活用し、コアなスクリプト作成から技術的なマスター（習得）へとあなたを導くために設計された **Coding5s** インタラクティブ・カリキュラムの日本語版です。

---

## 🚀 始め方

このラボをインタラクティブに体験するには、お使いのコンピューターに **Livebook** がインストールされ、Python ランタイム（環境）が統合されている必要があります。

1. **Livebook をインストールする:** [livebook.dev](https://livebook.dev) からダウンロードしてください。
2. **ラボを開く:** 以下のフォルダをブラウズし、各ファイル内にある **"Run in Livebook"** ボタンをクリックするか、Livebook セッションに URL を直接インポートしてください。

---

## 📚 Coding5s メソドロジー（5つのステージ）

私たちの手法は、**「制御された認知の摩擦（Controlled Cognitive Friction）」**に基づいています。各ラボでは、以下のステップに沿って学習を進めます：

| ステージ | 名称 | 目的 |
|-------|------|-----------|
| **1** | 基礎実践 (Practice) | ゼロからコードを書く |
| **2** | デバッグ (Debug) | 意図的に配置された構文エラーや論理エラーを見つける |
| **3** | 穴埋め補全 (Complete) | アーキテクチャやアルゴリズムの空白を埋める |
| **4** | リファクタリング (Refactor) | 既存のスクリプトを最適化する（フラット構造 vs モジュール構造） |
| **5** | 機能拡張 (Extend) | プロダクション環境に対応できる新しい機能を追加する |

*本リポジトリには **ステージ 1（基礎実践）** が含まれています。*

---

## 🛠️ 各 Livebook の使い方

各 `.livemd` ファイルを開いたら、以下のシンプルなワークフローに従ってください：

1. **Livebook**（デスクトップ版またはブラウザ版）でファイルを開きます。
2. **ステージ 1 のプロンプト**をコピーし、お好みの AI チャット（ChatGPT、Gemini、Claude など）に貼り付けます。
3. AI がそのテーマに沿った、**実行可能な 3〜5 つのマイクロ・サンプル**を生成します。
4. それらのサンプルを Livebook の**実行セル（execution cell）**にコピーして実行します。
5. コードを変更して実験し、出力がリアルタイムでどのように変わるかを確認します。

---

## 🧠 ソクラテス式メンター（AI）

各 Livebook には、**メンター（Mentor）プロンプト**も含まれています。あなたのコードとロジックの簡単な説明と一緒に、同じ AI チャットに貼り付けてください。メンターは以下のように振る舞います：

- （最初は）答えを直接**教えません**
- あなたが自分でエラーを発見できるように、ソクラテス式の質問を投げかけます
- **プログラミングの概念**を説明するために、現実世界の例え（アナロジー）を使います
- 「なんとなく雰囲気で書くコード（Vibe Coding）」を卒業し、本物のエンジニアリングの直感を養う手助けをします
- 具体的な質問に対しては、シニアレベルの専門的な回答を提供します

---

## 🛠️ インタラクティブ・カリキュラム — ステージ 1：実践ラボ

**Run in Livebook** バッジをクリックすると、各ラボを環境内で直接開くことができます。

| # |  Level |  Type |Topic Name | Interactive Lab |
| :--- | :--- | :--- | :--- | :--- |
| 001 | 🟢Beginner | Topic | 基本構文と出力 (print(), Comments, Indentation) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/001_topic_print_comments_indentation.livemd) |
| 002 | 🟢Beginner | Topic | 変数と Dynamic Typing (Assignment, Naming Conventions) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/002_topic_dynamic_typing_assignment_naming_conventions.livemd) |
| 003 | 🟢Beginner | Topic | プリミティブデータ型 (int, float, str, bool) と type() | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/003_topic_int_float_str_bool_type.livemd) |
| 004 | 🟢Beginner | Topic | 算術演算 (+, -, *, /, //, %, **) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/004_topic.livemd) |
| 005 | 🟢Beginner | Topic | 比較演算子と恒等演算子 (==, !=, >, <, is, is not) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/005_topic_is_is_not.livemd) |
| 006 | 🟢Beginner | PROJECT | チップと割り勘計算機 (数学演算と variables の組み合わせ) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/006_project_variables.livemd) |
| 007 | 🟢Beginner | Topic | ユーザー入力と Type Casting (input(), int(), float(), str()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/007_topic_type_casting_input_int_float_str.livemd) |
| 008 | 🟢Beginner | Topic | 論理演算子 (and, or, not) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/008_topic_and_or_not.livemd) |
| 009 | 🟢Beginner | Topic | 基本的な String 操作 (Concatenation, Repetition, Indexing []) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/009_topic_string_concatenation_repetition_indexing.livemd) |
| 010 | 🟢Beginner | Topic | String のフォーマット (f-strings, .format()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/010_topic_string_f_strings_format.livemd) |
| 011 | 🟢Beginner | Topic | 一般的な String メソッド (lower(), upper(), strip(), replace(), split()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/011_topic_string_lower_upper_strip_replace_split.livemd) |
| 012 | 🟢Beginner | PROJECT | インタラクティブなユーザープロファイル生成器 (I/O, formatting, string methods) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/012_project_i_o_formatting_string_methods.livemd) |
| 013 | 🟢Beginner | Topic | 制御フロー：基本的な条件分岐 (if, else) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/013_topic_if_else.livemd) |
| 014 | 🟢Beginner | Topic | 制御フロー：連鎖および入れ子の条件分岐 (elif, nested if) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/014_topic_elif_nested_if.livemd) |
| 015 | 🟢Beginner | Topic | 制御フロー：Structural Pattern Matching (match/case) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/015_topic_structural_pattern_matching_match_case.livemd) |
| 016 | 🟢Beginner | Topic | Lists 入門 (Creation, Indexing, Mutability concept) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/016_topic_lists_creation_indexing_mutability_concept.livemd) |
| 017 | 🟢Beginner | Topic | List の変更メソッド (append(), insert(), extend(), remove(), pop()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/017_topic_list_append_insert_extend_remove_pop.livemd) |
| 018 | 🟢Beginner | Topic | シーケンスのスライスとストライド ([start:stop:step]) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/018_topic_start_stop_step.livemd) |
| 019 | 🟢Beginner | PROJECT | 基本的な To-Do マネージャー (条件分岐と List 操作) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/019_project_to_do_list.livemd) |
| 020 | 🟢Beginner | Topic | Tuples 入門 (Creation, Immutability, Unpacking) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/020_topic_tuples_creation_immutability_unpacking.livemd) |
| 021 | 🟢Beginner | Topic | Dictionaries 入門 (Key-Value pairs, Creation, Direct Access) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/021_topic_dictionaries_key_value_pairs_creation_direct_access.livemd) |
| 022 | 🟢Beginner | Topic | Dictionary メソッド (keys(), values(), items(), get(), update()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/022_topic_dictionary_keys_values_items_get_update.livemd) |
| 023 | 🟢Beginner | Topic | Sets 入門 (Creation, Uniqueness, add(), remove()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/023_topic_sets_creation_uniqueness_add_remove.livemd) |
| 024 | 🟢Beginner | Topic | Set 演算 (union(), intersection(), difference(), symmetric_difference()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/024_topic_set_union_intersection_difference_symmetric_difference.livemd) |
| 025 | 🟢Beginner | PROJECT | 連絡先とデータの重複排除 (Dicts, Tuples, Sets) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/025_project_dicts_tuples_sets.livemd) |
| 026 | 🟢Beginner | Topic | 反復：for ループ (strings, lists, tuples の反復処理) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/026_topic_for_strings_lists_tuples.livemd) |
| 027 | 🟢Beginner | Topic | 反復：while ループと制御文 (break, continue, pass) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/027_topic_while_break_continue_pass.livemd) |
| 028 | 🟢Beginner | Topic | セイウチ演算子による代入式 (:=) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/beginner/028_topic.livemd) |
| 029 | 🟡Intermediate | Topic | 高度な反復ツール (range(), enumerate(), zip()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/029_topic_range_enumerate_zip.livemd) |
| 030 | 🟡Intermediate | Topic | メンバーシップ演算子 (すべてのデータ構造における in, not in) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/030_topic_in_not_in.livemd) |
| 031 | 🟡Intermediate | Topic | List Comprehensions (基本構文と条件付きフィルタリング) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/031_topic_list_comprehensions.livemd) |
| 032 | 🟡Intermediate | PROJECT | テキストとデータの自動クリーナー (Loops, Comprehensions, Conditionals) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/032_project_loops_comprehensions_conditionals.livemd) |
| 033 | 🟡Intermediate | Topic | Dictionary と Set の Comprehensions (構文とフィルタリング) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/033_topic_dictionary_set_comprehensions.livemd) |
| 034 | 🟡Intermediate | Topic | Functions 入門 (def, 基本的な return 文) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/034_topic_functions_def_return.livemd) |
| 035 | 🟡Intermediate | Topic | Function の引数：Positional, Keyword, および Default Values | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/035_topic_function_positional_keyword_default_values.livemd) |
| 036 | 🟡Intermediate | Topic | 柔軟な引数 (*args, **kwargs) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/036_topic_args_kwargs.livemd) |
| 037 | 🟡Intermediate | Topic | 変数のスコープ - Variable Scope (local, global, nonlocal の概念) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/037_topic_variable_scope_local_global_nonlocal.livemd) |
| 038 | 🟡Intermediate | PROJECT | コマンドライン数学ユーティリティ (Functions, Scope, Flexible args) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/038_project_functions_scope_flexible_args.livemd) |
| 039 | 🟡Intermediate | Topic | Lambda Functions (無名単一式関数) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/039_topic_lambda_functions.livemd) |
| 040 | 🟡Intermediate | Topic | Higher-Order Functions (map(), filter()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/040_topic_higher_order_functions_map_filter.livemd) |
| 041 | 🟡Intermediate | Topic | reduce() 関数 (functools からのインポート) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/041_topic_reduce_functools.livemd) |
| 042 | 🟡Intermediate | Topic | Modules と import 文の入門 (import, from ... import ...) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/042_topic_modules_import_import_from_import.livemd) |
| 043 | 🟡Intermediate | Topic | 標準 Math および Random モジュール (math ユーティリティ, random の選択と生成) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/043_topic_math_random_math_random.livemd) |
| 044 | 🟡Intermediate | Topic | 標準 Datetime モジュール (datetime, timedelta, 文字列フォーマット %Y-%m-%d) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/044_topic_datetime_datetime_timedelta_y_m_d.livemd) |
| 045 | 🟡Intermediate | PROJECT | 時間追跡付きパスワード生成器 (Functions, Datetime, Random) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/045_project_functions_datetime_random.livemd) |
| 046 | 🟡Intermediate | Topic | エラーハンドリングの基礎 (try, except ブロック) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/046_topic_try_except.livemd) |
| 047 | 🟡Intermediate | Topic | 高度なエラーハンドリング (finally, else, 特定の exception 型のキャッチ) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/047_topic_finally_else_exception.livemd) |
| 048 | 🟡Intermediate | Topic | カスタム例外の送出 (raise, assert 文) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/048_topic_raise_assert.livemd) |
| 049 | 🟡Intermediate | Topic | モダンなパス操作 (pathlib.Path による関数操作と走査) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/049_topic_pathlib_path.livemd) |
| 050 | 🟡Intermediate | Topic | 基本的なファイル I/O (テキストファイルのオープン、読み取り、クローズ) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/050_topic_i_o.livemd) |
| 051 | 🟡Intermediate | Topic | テキストファイルへのデータの書き込みと追記 ('w', 'a' モード) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/051_topic_w_a.livemd) |
| 052 | 🟡Intermediate | Topic | Context Managers (安全なファイル操作のための with open() 構文) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/052_topic_context_managers_with_open.livemd) |
| 053 | 🟡Intermediate | PROJECT | 自動ログファイル分析器 (File I/O, エラーハンドリング, String Parsing) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/053_project_file_i_o_string_parsing.livemd) |
| 054 | 🟡Intermediate | Topic | JSON データの取り扱い (json.load(), json.loads(), json.dump(), json.dumps()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/054_topic_json_json_load_json_loads_json_dump_json_dumps.livemd) |
| 055 | 🟡Intermediate | Topic | CSV ファイルの操作 (csv.reader(), csv.DictReader(), csv.writer()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/intermediate/055_topic_csv_csv_reader_csv_dictreader_csv_writer.livemd) |
| 056 | 🔴Advanced | Topic | 環境変数と設定 (os.environ, os.getenv()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/056_topic_os_environ_os_getenv.livemd) |
| 057 | 🔴Advanced | Topic | python-dotenv によるシークレット管理 (.env ファイルの安全な読み込み) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/057_topic_python_dotenv_env.livemd) |
| 058 | 🔴Advanced | Topic | HTTP プロトコルの基礎と requests モジュール (requests.get(), Status Codes) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/058_topic_http_requests_requests_get_status_codes.livemd) |
| 059 | 🔴Advanced | Topic | API レスポンスの処理 (response.json() による JSON パース) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/059_topic_api_response_json_json.livemd) |
| 060 | 🔴Advanced | Topic | 高度な API 処理：ページネーションと Cursors のナビゲーション | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/060_topic_api_cursors.livemd) |
| 061 | 🔴Advanced | PROJECT | セキュアな API データフェッチャー (Requests, JSON, dotenv, File I/O) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/061_project_api_requests_json_dotenv_file_i_o.livemd) |
| 062 | 🔴Advanced | Topic | 高度な requests：URL クエリパラメータとカスタム Headers | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/062_topic_requests_url_headers.livemd) |
| 063 | 🔴Advanced | Topic | 高度な requests：POST リクエストと JSON Payloads の送信 | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/063_topic_requests_post_json_payloads.livemd) |
| 064 | 🔴Advanced | Topic | API におけるエラーハンドリング (response.raise_for_status(), Request Timeouts) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/064_topic_api_response_raise_for_status_request_timeouts.livemd) |
| 065 | 🔴Advanced | Topic | collections モジュール (最適化されたカウント/グループ化のための Counter, defaultdict) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/065_topic_collections_counter_defaultdict.livemd) |
| 066 | 🔴Advanced | Topic | collections.deque による効率的な両端キュー (高速な append/pop 操作) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/066_topic_collections_deque_append_pop.livemd) |
| 067 | 🔴Advanced | Topic | collections.namedtuple による軽量な構造化レコード | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/067_topic_collections_namedtuple.livemd) |
| 068 | 🔴Advanced | PROJECT | API レスポンス分析器 (Requests, エラーハンドリング, Collections, Namedtuples) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/068_project_api_requests_collections_namedtuples.livemd) |
| 069 | 🔴Advanced | Topic | contextlib によるカスタム Context Managers (@contextmanager デコレータ) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/069_topic_contextlib_context_managers_contextmanager.livemd) |
| 070 | 🔴Advanced | Topic | Generators と yield キーワード (遅延評価の概念) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/070_topic_generators_yield.livemd) |
| 071 | 🔴Advanced | Topic | Generator Expressions (メモリ効率の良い反復可能オブジェクトの生成) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/071_topic_generator_expressions.livemd) |
| 072 | 🔴Advanced | Topic | 高度な関数：Closures と Nested Functions (オブジェクトなしでの状態保持) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/072_topic_closures_nested_functions.livemd) |
| 073 | 🔴Advanced | Topic | dataclasses による構造化データコンテナ | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/073_topic_dataclasses.livemd) |
| 074 | 🔴Advanced | Topic | Decorators：Function ラッパーの作成と適用 (@wrapper 構文) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/074_topic_decorators_function_wrapper.livemd) |
| 075 | 🔴Advanced | PROJECT | API レートリミッターとキャッシュデコレータ | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/075_project_api.livemd) |
| 076 | 🔴Advanced | Topic | ファイルシステムのナビゲーションと操作 (os.listdir(), os.mkdir(), os.remove()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/076_topic_os_listdir_os_mkdir_os_remove.livemd) |
| 077 | 🔴Advanced | Topic | tempfile による一時ファイル操作 (安全な一時ファイルとディレクトリ) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/077_topic_tempfile.livemd) |
| 078 | 🔴Advanced | Topic | ハイレベルなファイル操作 (shutil.copy(), shutil.move(), shutil.rmtree()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/078_topic_shutil_copy_shutil_move_shutil_rmtree.livemd) |
| 079 | 🔴Advanced | Topic | bisect による二分探索とソート済み挿入 (順序付きリストの効率的な維持) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/079_topic_bisect.livemd) |
| 080 | 🔴Advanced | Topic | Subprocesses：システムコマンドの実行 (subprocess.run(), 出力のキャプチャ) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/080_topic_subprocesses_subprocess_run.livemd) |
| 081 | 🔴Advanced | Topic | 正規表現：マッチングと検索 (re.search(), re.match(), 基本パターン) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/081_topic_re_search_re_match.livemd) |
| 082 | 🔴Advanced | Topic | 正規表現：抽出と置換 (re.findall(), re.sub(), キャプチャグループ) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/082_topic_re_findall_re_sub.livemd) |
| 083 | 🔴Advanced | PROJECT | システムログパーサーと正規表現抽出器 (Regex, os, pathlib) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/083_project_regex_os_pathlib.livemd) |
| 084 | 🔴Advanced | Topic | logging モジュール：設定とログレベル (DEBUG, INFO, WARNING, ERROR) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/084_topic_logging_debug_info_warning_error.livemd) |
| 085 | 🔴Advanced | Topic | 高度な logging：Handlers と Formatters (コンソールとファイルへの同時ログ出力) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/085_topic_logging_handlers_formatters.livemd) |
| 086 | 🔴Advanced | Topic | Itertools：無限および組合せ反復子 (count, cycle, combinations) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/086_topic_itertools_count_cycle_combinations.livemd) |
| 087 | 🔴Advanced | Topic | Itertools：データのグループ化と連結 (groupby, chain) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/087_topic_itertools_groupby_chain.livemd) |
| 088 | 🔴Advanced | Topic | Type Hinting 入門 (スカラー型：int, str, bool) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/088_topic_type_hinting_int_str_bool.livemd) |
| 089 | 🔴Advanced | Topic | 高度な Type Hinting (List, Dict, Optional, Union, Callable) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/089_topic_type_hinting_list_dict_optional_union_callable.livemd) |
| 090 | 🔴Advanced | PROJECT | 型安全な Webhook ペイロードプロセッサ (Type Hints, Logging, Itertools) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/090_project_webhook_type_hints_logging_itertools.livemd) |
| 091 | 🔴Advanced | Topic | スクリプトデバッグブートキャンプ：pdb の使用 (トレースポイントの設定、ロジックのステップ実行) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/091_topic_pdb.livemd) |
| 092 | 🔴Advanced | Topic | スクリプトリファクタリングの課題：DRY と単一責任 (巨大な関数の分割) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/092_topic_dry.livemd) |
| 093 | 🔴Advanced | Topic | 非同期プログラミングの基礎 (async def, await, Event Loop の概念) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/093_topic_async_def_await_event_loop.livemd) |
| 094 | 🔴Advanced | Topic | 非同期タスクの管理 (asyncio.gather(), asyncio.create_task()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/094_topic_asyncio_gather_asyncio_create_task.livemd) |
| 095 | 🔴Advanced | Topic | タイムアウトと非同期例外 (asyncio.wait_for(), 非同期エラーハンドリング) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/095_topic_asyncio_wait_for.livemd) |
| 096 | 🔴Advanced | Topic | Threading vs. Asyncio (概念的な違いと GIL による関数スレッドの制限) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/096_topic_threading_vs_asyncio_gil.livemd) |
| 097 | 🔴Advanced | PROJECT | 並行マルチ API データアグリゲーター (Asyncio, エラーハンドリング, Logging) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/097_project_api_asyncio_logging.livemd) |
| 098 | 🔴Advanced | Topic | 関数テスト (ネイティブな assert を使用した独立したテスト関数の作成) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/098_topic_assert.livemd) |
| 099 | 🔴Advanced | Topic | ネイティブ関数の Mocking (unittest.mock.patch をデコレータ/Context Manager として使用) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/099_topic_mocking_unittest_mock_patch_context_manager.livemd) |
| 100 | 🔴Advanced | Topic | プロジェクトの依存関係管理 (venv の作成, pip freeze > requirements.txt) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/100_topic_venv_pip_freeze_requirements_txt.livemd) |
| 101 | 🔴Advanced | Topic | 堅牢な CLIs の構築 (argparse, 位置引数とフラグ) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/101_topic_clis_argparse.livemd) |
| 102 | 🔴Advanced | Topic | パフォーマンス測定とプロファイリング (timeit モジュール) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/102_topic_timeit.livemd) |
| 103 | 🔴Advanced | Topic | functools.singledispatch による型による Function ディスパッチ | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/103_topic_functools_singledispatch_function.livemd) |
| 104 | 🔴Advanced | PROJECT | プロダクション級の CLI ユーティリティ | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/104_project_cli.livemd) |
| 105 | 🔴Advanced | Topic | データのハッシュ化と整合性検証 (SHA256 用の hashlib) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/105_topic_sha256_hashlib.livemd) |
| 106 | 🔴Advanced | Topic | weakref による弱参照 (メモリ安全なオブジェクト参照) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/106_topic_weakref.livemd) |
| 107 | 🔴Advanced | Topic | 高度な関数型ユーティリティ (functools.partial, メモ化のための @lru_cache) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/107_topic_functools_partial_lru_cache.livemd) |
| 108 | 🔴Advanced | Topic | atexit によるスクリプト終了フック (クリーンアップハンドラ) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/108_topic_atexit.livemd) |
| 109 | 🔴Advanced | Topic | signal によるシステム信号の処理 (スクリプトの正常終了) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/109_topic_signal.livemd) |
| 110 | 🔴Advanced | Topic | importlib による動的インポート (実行時のモジュールロード) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/110_topic_importlib.livemd) |
| 111 | 🔴Advanced | Topic | uuid による一意な ID 生成 (分散システム用 uuid4) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/111_topic_uuid_id_uuid4.livemd) |
| 112 | 🔴Advanced | PROJECT | 拡張可能な自動化フレームワーク | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ja/advanced/112_project.livemd) |

*全カリキュラムの目次（112のテーマ ＋ プロジェクト）は、各言語のフォルダ内で確認できます。*

---

## 🏛️ アーキテクチャ ＆ メンター

各ラボには、専門の AI メンターが学習プロセスをガイドする**「解説のゲート（Explanation Gate）」**が用意されています。各ステージのメンターは、そのフェーズの心理的・教育的ニーズに合わせて設計された独自のパーソナリティを持っています：

| ステージ | メンター | パーソナリティ | 教える内容 |
|-------|--------|-------------|------------------|
| **1** | 安心のガイド | 温かく、忍耐強い、頼れる兄・姉のような存在 | 安全な構文の探索、「雰囲気コーディング（vibe coding）」の脱却 |
| **2** | 分析のパートナー | 好奇心旺盛でコーヒーを愛する「ログの探偵」 | エラートレースの読み解き、システムクラッシュの理解 |
| **3** | 論理の足場架け | 計画的で励まし上手な「シニア・ビルダー」 | データフローの可視化（入力 → 変換 → 出力） |
| **4** | 洗練された批評家 | 皮肉屋で純粋主義、厳しくも愛のある「タフ・ラブ」 | 慣用的（アイディオマティック）なコード、関数型パターン、悪癖の排除 |
| **5** | 戦略的パートナー | 先見の明がある、プロフェッショナルな「システム設計士」 | エッジケース、フォールトトレランス（耐障害性）、ビジネスロジックへの適合 |

*本リポジトリには **ステージ 1（安心のガイド）** が含まれています。*

---

## 🔗 便利なリンク

[Coding5s.com](https://coding5s.com) | [Udemy (Coding5s Premium)](https://www.udemy.com/user/wilbarrios/) | [GitHub](https://github.com/WilfredoBarrios)

---

## 🤝 コントリビューション（貢献）

フィードバックや機能の提案はありますか？ プロジェクトをサポートしたい場合は、お気軽に Issue を作成するか、コントリビューションをお願いします！

---

## 📄 ライセンス

MIT © [Wil Barrios](https://github.com/WilfredoBarrios)

---
⚡ *Coding5s システム — 技術的マスター（習得）のために設計された学習体験。*
