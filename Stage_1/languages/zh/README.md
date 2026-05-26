# 🧪 Python Core & Scripting 互动式实验 — 中文 🇨🇳

[![Livebook](https://img.shields.io/badge/Livebook-FF6B6B?logo=livebook&logoColor=white)](https://livebook.dev)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **通过编写代码来学习 Python，而不仅仅是阅读它。**
> 这是 **Coding5s** 互动式课程的中文版，旨在利用 Livebook 的互动环境，带你从核心脚本编写走向技术精通。

---

## 🚀 如何开始？

若要以互动方式体验此实验，你需要在电脑上安装 **Livebook**，并配置好 Python 运行环境（runtime）集成。

1. **安装 Livebook：** 前往 [livebook.dev](https://livebook.dev) 下载。
2. **打开实验：** 浏览下方文件夹，点击每个文件内部的 **"Run in Livebook"** 按钮，或者直接将 URL 导入到你的 Livebook 会话中。

---

## 📚 Coding5s 教学法（5 个阶段）

我们的核心方法基于 **可控认知摩擦（Controlled Cognitive Friction）**。每个实验都将引导你完成以下阶段：

| 阶段 | 名称 | 目标 |
|-------|------|-----------|
| **1** | 实践 (Practice) | 从零开始编写代码 |
| **2** | 调试 (Debug) | 找出刻意设置的语法和逻辑错误 |
| **3** | 补全 (Complete) | 填补架构和算法上的空白 |
| **4** | 重构 (Refactor) | 优化现有脚本（扁平化结构 vs. 模块化结构） |
| **5** | 扩展 (Extend) | 添加全新的生产级可用功能 |

*本仓库包含 **阶段 1（实践）**。*

---

## 🛠️ 如何使用每个 Livebook？

在每个 `.livemd` 文件内部，请遵循以下简单的工作流：

1. 在 **Livebook**（桌面版或网页版）中打开该文件。
2. 复制 **阶段 1 提示词（Prompt）**，并将其粘贴到你首选的 AI 聊天工具（ChatGPT、Gemini、Claude 等）中。
3. AI 将针对该主题生成 **3 到 5 个可执行的微型示例（micro-examples）**。
4. 将这些示例复制到 Livebook 的 **执行单元格（execution cell）** 中并运行。
5. 修改代码、进行实验，并实时观察输出的变化。

---

## 🧠 苏格拉底式导师（AI）

每个 Livebook 还包含一个 **导师提示词（Mentor prompt）**。你可以将其与你的代码以及对逻辑 brief 的简短说明一起粘贴到同一个 AI 聊天中。导师将会：

- **不会直接给你答案**（起初）
- 向你提出苏格拉底式的提问，让你自己发现错误
- 使用现实世界中的类比来解释 **编程概念**
- 帮助你消除“凭感觉编码（Vibe Coding）”，建立真正的工程直觉
- 当你提出具体问题时，提供资深（Senior）级别的解答

---

## 🛠️ 互动式课程 — 阶段 1：实践实验室

点击 **Run in Livebook** 徽章，直接在你的环境中打开各个实验。

| # |  Level |  Type |Topic Name | Interactive Lab |
| :--- | :--- | :--- | :--- | :--- |
| 001 | 🟢Beginner | Topic | 基础语法与输出 (print(), Comments, Indentation) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/001_topic_print_comments_indentation.livemd) |
| 002 | 🟢Beginner | Topic | 变量与动态类型 (Assignment, Naming Conventions) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/002_topic_assignment_naming_conventions.livemd) |
| 003 | 🟢Beginner | Topic | 原生数据类型 (int, float, str, bool) 与 type() | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/003_topic_int_float_str_bool_type.livemd) |
| 004 | 🟢Beginner | Topic | 算术运算 (+, -, *, /, //, %, **) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/004_topic.livemd) |
| 005 | 🟢Beginner | Topic | 比较与身份运算符 (==, !=, >, <, is, is not) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/005_topic_is_is_not.livemd) |
| 006 | 🟢Beginner | PROJECT | 小费与分摊计算器 (结合数学运算与 variables) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/006_project_variables.livemd) |
| 007 | 🟢Beginner | Topic | 用户输入与类型转换 (input(), int(), float(), str()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/007_topic_input_int_float_str.livemd) |
| 008 | 🟢Beginner | Topic | 逻辑运算符 (and, or, not) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/008_topic_and_or_not.livemd) |
| 009 | 🟢Beginner | Topic | 基础字符串操作 (Concatenation, Repetition, Indexing []) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/009_topic_concatenation_repetition_indexing.livemd) |
| 010 | 🟢Beginner | Topic | 字符串格式化 (f-strings, .format()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/010_topic_f_strings_format.livemd) |
| 011 | 🟢Beginner | Topic | 常用字符串方法 (lower(), upper(), strip(), replace(), split()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/011_topic_lower_upper_strip_replace_split.livemd) |
| 012 | 🟢Beginner | PROJECT | 交互式用户资料生成器 (I/O, formatting, string methods) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/012_project_i_o_formatting_string_methods.livemd) |
| 013 | 🟢Beginner | Topic | 控制流：基础条件语句 (if, else) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/013_topic_if_else.livemd) |
| 014 | 🟢Beginner | Topic | 控制流：链式与嵌套条件语句 (elif, nested if) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/014_topic_elif_nested_if.livemd) |
| 015 | 🟢Beginner | Topic | 控制流：结构化模式匹配 (match/case) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/015_topic_match_case.livemd) |
| 016 | 🟢Beginner | Topic | Lists 简介 (Creation, Indexing, Mutability concept) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/016_topic_lists_creation_indexing_mutability_concept.livemd) |
| 017 | 🟢Beginner | Topic | List 修改方法 (append(), insert(), extend(), remove(), pop()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/017_topic_list_append_insert_extend_remove_pop.livemd) |
| 018 | 🟢Beginner | Topic | 序列切片与步长 ([start:stop:step]) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/018_topic_start_stop_step.livemd) |
| 019 | 🟢Beginner | PROJECT | 基础待办事项管理器 (条件语句与 List 操作) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/019_project_list.livemd) |
| 020 | 🟢Beginner | Topic | Tuples 简介 (Creation, Immutability, Unpacking) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/020_topic_tuples_creation_immutability_unpacking.livemd) |
| 021 | 🟢Beginner | Topic | Dictionaries 简介 (Key-Value pairs, Creation, Direct Access) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/021_topic_dictionaries_key_value_pairs_creation_direct_access.livemd) |
| 022 | 🟢Beginner | Topic | Dictionary 方法 (keys(), values(), items(), get(), update()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/022_topic_dictionary_keys_values_items_get_update.livemd) |
| 023 | 🟢Beginner | Topic | Sets 简介 (Creation, Uniqueness, add(), remove()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/023_topic_sets_creation_uniqueness_add_remove.livemd) |
| 024 | 🟢Beginner | Topic | Set 运算 (union(), intersection(), difference(), symmetric_difference()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/024_topic_set_union_intersection_difference_symmetric_difference.livemd) |
| 025 | 🟢Beginner | PROJECT | 联系人与数据去重器 (Dicts, Tuples, Sets) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/025_project_dicts_tuples_sets.livemd) |
| 026 | 🟢Beginner | Topic | 迭代：for 循环 (迭代 strings, lists, tuples) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/026_topic_for_strings_lists_tuples.livemd) |
| 027 | 🟢Beginner | Topic | 迭代：while 循环与控制语句 (break, continue, pass) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/027_topic_while_break_continue_pass.livemd) |
| 028 | 🟢Beginner | Topic | 使用 Walrus Operator 的赋值表达式 (:=) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/beginner/028_topic_walrus_operator.livemd) |
| 029 | 🟡Intermediate | Topic | 高级迭代工具 (range(), enumerate(), zip()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/029_topic_range_enumerate_zip.livemd) |
| 030 | 🟡Intermediate | Topic | 成员运算符 (跨所有数据结构的 in, not in) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/030_topic_in_not_in.livemd) |
| 031 | 🟡Intermediate | Topic | List Comprehensions (基础语法与条件过滤) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/031_topic_list_comprehensions.livemd) |
| 032 | 🟡Intermediate | PROJECT | 自动化文本与数据清理器 (Loops, Comprehensions, Conditionals) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/032_project_loops_comprehensions_conditionals.livemd) |
| 033 | 🟡Intermediate | Topic | Dictionary 与 Set Comprehensions (语法与过滤) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/033_topic_dictionary_set_comprehensions.livemd) |
| 034 | 🟡Intermediate | Topic | Functions 简介 (def, 基础 return 语句) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/034_topic_functions_def_return.livemd) |
| 035 | 🟡Intermediate | Topic | Function 参数：Positional, Keyword, 与 Default Values | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/035_topic_function_positional_keyword_default_values.livemd) |
| 036 | 🟡Intermediate | Topic | 可变参数 (*args, **kwargs) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/036_topic_args_kwargs.livemd) |
| 037 | 🟡Intermediate | Topic | 变量作用域 - Variable Scope (local, global, nonlocal 概念) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/037_topic_variable_scope_local_global_nonlocal.livemd) |
| 038 | 🟡Intermediate | PROJECT | 命令行数学工具 (Functions, Scope, Flexible args) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/038_project_functions_scope_flexible_args.livemd) |
| 039 | 🟡Intermediate | Topic | Lambda Functions (匿名单表达式函数) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/039_topic_lambda_functions.livemd) |
| 040 | 🟡Intermediate | Topic | Higher-Order Functions (map(), filter()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/040_topic_higher_order_functions_map_filter.livemd) |
| 041 | 🟡Intermediate | Topic | reduce() 函数 (从 functools 导入) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/041_topic_reduce_functools.livemd) |
| 042 | 🟡Intermediate | Topic | Modules 与 import 语句简介 (import, from ... import ...) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/042_topic_modules_import_import_from_import.livemd) |
| 043 | 🟡Intermediate | Topic | 标准 Math 与 Random 模块 (math 工具, random 选择与生成) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/043_topic_math_random_math_random.livemd) |
| 044 | 🟡Intermediate | Topic | 标准 Datetime 模块 (datetime, timedelta, 字符串格式化 %Y-%m-%d) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/044_topic_datetime_datetime_timedelta_y_m_d.livemd) |
| 045 | 🟡Intermediate | PROJECT | 带时间追踪的密码生成器 (Functions, Datetime, Random) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/045_project_functions_datetime_random.livemd) |
| 046 | 🟡Intermediate | Topic | 错误处理基础 (try, except 模块) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/046_topic_try_except.livemd) |
| 047 | 🟡Intermediate | Topic | 高级错误处理 (finally, else, 捕获特定 exception 类型) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/047_topic_finally_else_exception.livemd) |
| 048 | 🟡Intermediate | Topic | 抛出自定义异常 (raise, assert 语句) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/048_topic_raise_assert.livemd) |
| 049 | 🟡Intermediate | Topic | 现代路径处理 (pathlib.Path 函数式操作与遍历) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/049_topic_pathlib_path.livemd) |
| 050 | 🟡Intermediate | Topic | 基础文件 I/O (打开、读取和关闭文本文件) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/050_topic_i_o.livemd) |
| 051 | 🟡Intermediate | Topic | 向文本文件写入与追加数据 ('w', 'a' 模式) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/051_topic_w_a.livemd) |
| 052 | 🟡Intermediate | Topic | Context Managers (用于安全文件处理的 with open() 语法) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/052_topic_context_managers_with_open.livemd) |
| 053 | 🟡Intermediate | PROJECT | 自动化日志文件分析器 (File I/O, 错误处理, String Parsing) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/053_project_file_i_o_string_parsing.livemd) |
| 054 | 🟡Intermediate | Topic | 处理 JSON 数据 (json.load(), json.loads(), json.dump(), json.dumps()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/054_topic_json_json_load_json_loads_json_dump_json_dumps.livemd) |
| 055 | 🟡Intermediate | Topic | 使用 CSV 文件 (csv.reader(), csv.DictReader(), csv.writer()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/intermediate/055_topic_csv_csv_reader_csv_dictreader_csv_writer.livemd) |
| 056 | 🔴Advanced | Topic | 环境变量与配置 (os.environ, os.getenv()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/056_topic_os_environ_os_getenv.livemd) |
| 057 | 🔴Advanced | Topic | 使用 python-dotenv 管理秘钥 (安全加载 .env 文件) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/057_topic_python_dotenv_env.livemd) |
| 058 | 🔴Advanced | Topic | HTTP 协议基础与 requests 模块 (requests.get(), Status Codes) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/058_topic_http_requests_requests_get_status_codes.livemd) |
| 059 | 🔴Advanced | Topic | 处理 API 响应 (使用 response.json() 进行 JSON 解析) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/059_topic_api_response_json_json.livemd) |
| 060 | 🔴Advanced | Topic | 高级 API 处理：导航分页与 Cursors | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/060_topic_api_cursors.livemd) |
| 061 | 🔴Advanced | PROJECT | 安全 API 数据获取器 (Requests, JSON, dotenv, File I/O) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/061_project_api_requests_json_dotenv_file_i_o.livemd) |
| 062 | 🔴Advanced | Topic | 高级 requests：URL 查询参数与自定义 Headers | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/062_topic_requests_url_headers.livemd) |
| 063 | 🔴Advanced | Topic | 高级 requests：发送 POST 请求与 JSON Payloads | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/063_topic_requests_post_json_payloads.livemd) |
| 064 | 🔴Advanced | Topic | API 中的错误处理 (response.raise_for_status(), Request Timeouts) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/064_topic_api_response_raise_for_status_request_timeouts.livemd) |
| 065 | 🔴Advanced | Topic | collections 模块 (用于优化计数/分组的 Counter, defaultdict) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/065_topic_collections_counter_defaultdict.livemd) |
| 066 | 🔴Advanced | Topic | 使用 collections.deque 实现高效双端队列 (快速 append/pop 操作) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/066_topic_collections_deque_append_pop.livemd) |
| 067 | 🔴Advanced | Topic | 使用 collections.namedtuple 实现轻量级结构化记录 | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/067_topic_collections_namedtuple.livemd) |
| 068 | 🔴Advanced | PROJECT | API 响应分析器 (Requests, 错误处理, Collections, Namedtuples) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/068_project_api_requests_collections_namedtuples.livemd) |
| 069 | 🔴Advanced | Topic | 使用 contextlib 自定义 Context Managers (@contextmanager 装饰器) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/069_topic_contextlib_context_managers_contextmanager.livemd) |
| 070 | 🔴Advanced | Topic | Generators 与 yield 关键字 (惰性求值概念) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/070_topic_generators_yield.livemd) |
| 071 | 🔴Advanced | Topic | Generator Expressions (内存高效的迭代器生成) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/071_topic_generator_expressions.livemd) |
| 072 | 🔴Advanced | Topic | 高级函数：Closures 与 Nested Functions (在不使用对象的情况下保持状态) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/072_topic_closures_nested_functions.livemd) |
| 073 | 🔴Advanced | Topic | 使用 dataclasses 构建结构化数据容器 | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/073_topic_dataclasses.livemd) |
| 074 | 🔴Advanced | Topic | Decorators：创建与应用函数包装器 (@wrapper 语法) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/074_topic_decorators_wrapper.livemd) |
| 075 | 🔴Advanced | PROJECT | API 速率限制器与缓存装饰器 | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/075_project_api.livemd) |
| 076 | 🔴Advanced | Topic | 文件系统导航与操作 (os.listdir(), os.mkdir(), os.remove()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/076_topic_os_listdir_os_mkdir_os_remove.livemd) |
| 077 | 🔴Advanced | Topic | 使用 tempfile 处理临时文件 (安全的临时文件与目录) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/077_topic_tempfile.livemd) |
| 078 | 🔴Advanced | Topic | 高级文件操作 (shutil.copy(), shutil.move(), shutil.rmtree()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/078_topic_shutil_copy_shutil_move_shutil_rmtree.livemd) |
| 079 | 🔴Advanced | Topic | 使用 bisect 进行二分查找与排序插入 (高效维护有序列表) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/079_topic_bisect.livemd) |
| 080 | 🔴Advanced | Topic | Subprocesses：执行系统命令 (subprocess.run(), 捕获输出) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/080_topic_subprocesses_subprocess_run.livemd) |
| 081 | 🔴Advanced | Topic | 正则表达式：匹配与搜索 (re.search(), re.match(), 基础模式) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/081_topic_re_search_re_match.livemd) |
| 082 | 🔴Advanced | Topic | 正则表达式：提取与替换 (re.findall(), re.sub(), 捕获组) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/082_topic_re_findall_re_sub.livemd) |
| 083 | 🔴Advanced | PROJECT | 系统日志解析器与正则提取器 (Regex, os, pathlib) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/083_project_regex_os_pathlib.livemd) |
| 084 | 🔴Advanced | Topic | logging 模块：配置与日志级别 (DEBUG, INFO, WARNING, ERROR) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/084_topic_logging_debug_info_warning_error.livemd) |
| 085 | 🔴Advanced | Topic | 高级 logging：Handlers 与 Formatters (同时将日志路由到控制台和文件) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/085_topic_logging_handlers_formatters.livemd) |
| 086 | 🔴Advanced | Topic | Itertools：无限与组合迭代器 (count, cycle, combinations) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/086_topic_itertools_count_cycle_combinations.livemd) |
| 087 | 🔴Advanced | Topic | Itertools：数据分组与链接 (groupby, chain) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/087_topic_itertools_groupby_chain.livemd) |
| 088 | 🔴Advanced | Topic | 类型提示简介 (标量类型：int, str, bool) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/088_topic_int_str_bool.livemd) |
| 089 | 🔴Advanced | Topic | 高级类型提示 (List, Dict, Optional, Union, Callable) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/089_topic_list_dict_optional_union_callable.livemd) |
| 090 | 🔴Advanced | PROJECT | 类型安全的 Webhook 有效负载处理器 (Type Hints, Logging, Itertools) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/090_project_webhook_type_hints_logging_itertools.livemd) |
| 091 | 🔴Advanced | Topic | 脚本调试训练营：使用 pdb (设置跟踪点, 逐步执行逻辑) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/091_topic_pdb.livemd) |
| 092 | 🔴Advanced | Topic | 脚本重构挑战：DRY 与单一职责 (拆分庞大的函数) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/092_topic_dry.livemd) |
| 093 | 🔴Advanced | Topic | 异步编程基础 (async def, await, Event Loop 概念) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/093_topic_async_def_await_event_loop.livemd) |
| 094 | 🔴Advanced | Topic | 管理异步任务 (asyncio.gather(), asyncio.create_task()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/094_topic_asyncio_gather_asyncio_create_task.livemd) |
| 095 | 🔴Advanced | Topic | 超时与异步异常 (asyncio.wait_for(), 处理异步错误) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/095_topic_asyncio_wait_for.livemd) |
| 096 | 🔴Advanced | Topic | Threading 对比 Asyncio (概念差异与 GIL 下的函数线程限制) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/096_topic_threading_asyncio_gil.livemd) |
| 097 | 🔴Advanced | PROJECT | 并发多 API 数据聚合器 (Asyncio, 错误处理, Logging) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/097_project_api_asyncio_logging.livemd) |
| 098 | 🔴Advanced | Topic | 功能测试 (使用原生 assert 编写独立的测试函数) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/098_topic_assert.livemd) |
| 099 | 🔴Advanced | Topic | Mocking 原生函数 (使用 unittest.mock.patch 作为装饰器/Context Manager) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/099_topic_mocking_unittest_mock_patch_context_manager.livemd) |
| 100 | 🔴Advanced | Topic | 管理项目依赖 (创建 venv, pip freeze > requirements.txt) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/100_topic_venv_pip_freeze_requirements_txt.livemd) |
| 101 | 🔴Advanced | Topic | 构建健壮的 CLIs (argparse, 位置参数与 Flags) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/101_topic_clis_argparse_flags.livemd) |
| 102 | 🔴Advanced | Topic | 性能测量与性能分析 (timeit 模块) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/102_topic_timeit.livemd) |
| 103 | 🔴Advanced | Topic | 使用 functools.singledispatch 按类型分发 Function | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/103_topic_functools_singledispatch_function.livemd) |
| 104 | 🔴Advanced | PROJECT | 生产级 CLI 工具 | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/104_project_cli.livemd) |
| 105 | 🔴Advanced | Topic | 数据哈希与完整性校验 (用于 SHA256 的 hashlib) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/105_topic_sha256_hashlib.livemd) |
| 106 | 🔴Advanced | Topic | 使用 weakref 实现弱引用 (内存安全的对象引用) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/106_topic_weakref.livemd) |
| 107 | 🔴Advanced | Topic | 高级函数式工具 (functools.partial, 用于记忆化的 @lru_cache) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/107_topic_functools_partial_lru_cache.livemd) |
| 108 | 🔴Advanced | Topic | 使用 atexit 实现脚本关闭钩子 (清理程序) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/108_topic_atexit.livemd) |
| 109 | 🔴Advanced | Topic | 使用 signal 处理系统信号 (优雅地终止脚本) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/109_topic_signal.livemd) |
| 110 | 🔴Advanced | Topic | 使用 importlib 实现动态导入 (运行时模块加载) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/110_topic_importlib.livemd) |
| 111 | 🔴Advanced | Topic | 使用 uuid 生成唯一 ID (用于分布式系统的 uuid4) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/111_topic_uuid_id_uuid4.livemd) |
| 112 | 🔴Advanced | PROJECT | 可扩展的自动化框架 | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/zh/advanced/112_project.livemd) |

*完整的目录（112 个主题 + 项目）可在每个语言文件夹内部查看。*

---

## 🏛️ 架构 & 导师

每个实验都包含一个 **知识卡口（Explanation Gate）**，由专门的 AI 导师引导你完成学习过程。每个阶段都有其独特的导师性格，旨在匹配该阶段的心理和教学需求：

| 阶段 | 导师 | 性格特征 | 传授核心 |
|-------|--------|-------------|------------------|
| **1** | 安全向导 | 温暖、耐心，像大哥哥/大姐姐 | 安全探索语法，消除“凭感觉编码” |
| **2** | 分析伙伴 | 好奇心强、靠咖啡续命的“日志侦探” | champion 阅读错误堆栈，理解系统崩溃原因 |
| **3** | 逻辑支架 | 循序渐进、充满鼓励的“资深建造者” | 可视化数据流（输入 → 转换 → 输出） |
| **4** | 优雅批判家 | 讽刺、完美主义、严厉的爱（tough love） | 编写地道代码（idiomatic code）、函数式模式、改掉坏习惯 |
| **5** | 战略伙伴 | 远见卓识、严谨专业的“系统架构师” | 边界情况（edge cases）、容错能力、对齐业务逻辑 |

*本仓库包含 **阶段 1（安全向导）**。*

---

## 🔗 常用链接

[Coding5s.com](https://coding5s.com) | [Udemy (Coding5s Premium)](https://www.udemy.com/user/wilbarrios/) | [GitHub](https://github.com/WilfredoBarrios)

---

## 🤝 贡献参与

你有任何反馈或功能建议吗？如果你想以任何方式支持这个项目，欢迎随时开一个 issue 或提交你的贡献！

---

## 📄 开源协议

MIT © [Wil Barrios](https://github.com/WilfredoBarrios)

---
⚡ *Coding5s 系统 — 专为精通技术而设计的学习法。*
