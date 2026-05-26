# 🧪 পাইথন কোর এবং স্ক্রিপ্টিং ইন্টারঅ্যাক্টিভ ল্যাব — বাংলা 🇧🇩

[![Livebook](https://img.shields.io/badge/Livebook-FF6B6B?logo=livebook&logoColor=white)](https://livebook.dev)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **পাইথন কেবল পড়ে নয়, কোড লিখে শিখুন।**
> এটি লাইভবুক (Livebook)-এর ইন্টারঅ্যাক্টিভ পরিবেশ ব্যবহার করে আপনাকে কোর স্ক্রিপ্টিং থেকে শুরু করে কারিগরি দক্ষতায় (technical mastery) পৌঁছে দেওয়ার জন্য ডিজাইন করা **Coding5s** ইন্টারঅ্যাক্টিভ পাঠ্যক্রমের বাংলা সংস্করণ।

---

## 🚀 কীভাবে শুরু করবেন?

এই ল্যাবের ইন্টারঅ্যাক্টিভ অভিজ্ঞতা নিতে হলে, আপনার কম্পিউটারে পাইথন রানটাইম (runtime) ইন্টিগ্রেশনসহ **Livebook** ইনস্টল করা থাকতে হবে।

1. **লাইভবুক ইনস্টল করুন:** এটি [livebook.dev](https://livebook.dev) থেকে ডাউনলোড করুন।
2. **ল্যাব খুলুন:** নিচের ফোল্ডারগুলো ব্রাউজ করুন এবং প্রতিটি ফাইলের ভেতরে থাকা **"Run in Livebook"** বাটনে ক্লিক করুন, অথবা সরাসরি আপনার লাইভবুক সেশনে URL-টি ইম্পোর্ট করুন।

---

## 📚 Coding5s কার্যপ্রণালী (৫টি ধাপ)

আমাদের পদ্ধতিটি **নিয়ন্ত্রিত জ্ঞানীয় ঘর্ষণ** (Controlled Cognitive Friction)-এর ওপর ভিত্তি করে তৈরি। প্রতিটি ল্যাব আপনাকে নিচের ধাপগুলোর মাধ্যমে গাইড করবে:

| ধাপ | নাম | উদ্দেশ্য |
|---|---|---|
| **১** | অনুশীলন (Practice) | একদম শুরু থেকে নিজে কোড লেখা |
| **২** | ডিবাগ (Debug) | ইচ্ছাকৃতভাবে রেখে দেওয়া সিনট্যাক্স এবং লজিক ভুলগুলো খুঁজে বের করা |
| **৩** | সম্পন্ন করা (Complete) | আর্কিটেকচারাল এবং অ্যালগরিদমিক ঘাটতিগুলো পূরণ করা |
| **৪** | রিফ্যাক্টর (Refactor) | বিদ্যমান স্ক্রিপ্টগুলোকে উন্নত করা (ফ্ল্যাট বনাম মডুলার স্ট্রাকচার) |
| **৫** | সম্প্রসারণ (Extend) | প্রোডাকশনের জন্য প্রস্তুত নতুন কার্যকারিতা বা ফিচার যুক্ত করা |

*এই রিপোজিটরিতে **ধাপ ১ (অনুশীলন)** অন্তর্ভুক্ত রয়েছে।*

---

## 🛠️ প্রতিটি লাইভবুক কীভাবে ব্যবহার করবেন?

প্রতিটি `.livemd` ফাইলের ভেতরে, এই সহজ কর্মপ্রবাহ (workflow) অনুসরণ করুন:

1. ফাইলটি **Livebook**-এ (ডেস্কটপ বা ব্রাউজার সংস্করণ) খুলুন।
2. **ধাপ ১-এর প্রম্পটটি** কপি করুন এবং আপনার পছন্দের AI চ্যাটে (ChatGPT, Gemini, Claude ইত্যাদি) পেস্ট করুন।
3. AI ওই টপিকের জন্য **৩ থেকে ৫টি এক্সিকিউটেবল মাইক্রো-এক্সাম্পল** (micro-examples) তৈরি করবে।
4. সেই উদাহরণগুলো লাইভবুকের **এক্সিকিউশন সেলে** (execution cell) কপি করুন এবং রান করুন।
5. কোড পরিবর্তন করুন, পরীক্ষা-নিরীক্ষা করুন এবং রিয়েল-টাইমে আউটপুট পরিবর্তন হতে দেখুন।

---

## 🧠 সক্রেটিক মেন্টর (AI)

প্রতিটি লাইভবুকে একটি **মেন্টর (Mentor) প্রম্পটও** অন্তর্ভুক্ত রয়েছে। আপনি এটি আপনার কোড এবং আপনার লজিকের একটি সংক্ষিপ্ত বিবরণসহ একই AI চ্যাটে পেস্ট করতে পারেন। মেন্টর:

- (শুরুতেই) আপনাকে সরাসরি উত্তর **দেবে না**
- আপনাকে সক্রেটিক (Socratic) প্রশ্ন করবে যাতে আপনি নিজেই নিজের ভুলটি আবিষ্কার করতে পারেন
- **প্রোগ্রামিংয়ের ধারণাগুলো** ব্যাখ্যা করার জন্য বাস্তব জীবনের অ্যানালজি বা উপমা ব্যবহার করবে
- আপনাকে "ভাইব কোডিং" (Vibe Coding) থেকে বের হয়ে আসতে এবং সত্যিকারের ইঞ্জিনিয়ারিং ইনটুইশন তৈরি করতে সাহায্য করবে
- আপনি সুনির্দিষ্ট প্রশ্ন জিজ্ঞাসা করলে সিনিয়র-স্তরের উত্তর প্রদান করবে

---

## 🛠️ ইন্টারঅ্যাক্টিভ পাঠ্যক্রম — ধাপ ১: অনুশীলন ল্যাব

প্রতিটি ল্যাব সরাসরি আপনার পরিবেশে খুলতে **Run in Livebook** ব্যাজে ক্লিক করুন।

| # |  Level |  Type |Topic Name | Interactive Lab |
| :--- | :--- | :--- | :--- | :--- |
| 001 | 🟢Beginner | Topic | মৌলিক Syntax এবং আউটপুট (print(), Comments, Indentation) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/001_topic_syntax_print_comments_indentation.livemd) |
| 002 | 🟢Beginner | Topic | Variables এবং Dynamic Typing (Assignment, Naming Conventions) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/002_topic_variables_dynamic_typing_assignment_naming_conventions.livemd) |
| 003 | 🟢Beginner | Topic | Primitive Data Types (int, float, str, bool) এবং type() | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/003_topic_primitive_data_types_int_float_str_bool_type.livemd) |
| 004 | 🟢Beginner | Topic | গাণিতিক অপারেশন (+, -, *, /, //, %, **) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/004_topic.livemd) |
| 005 | 🟢Beginner | Topic | Comparison এবং Identity Operators (==, !=, >, <, is, is not) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/005_topic_comparison_identity_operators_is_is_not.livemd) |
| 006 | 🟢Beginner | PROJECT | টিপ এবং স্প্লিট ক্যালকুলেটর (Math অপারেশন এবং variables এর সমন্বয়) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/006_project_math_variables.livemd) |
| 007 | 🟢Beginner | Topic | ইউজার ইনপুট এবং Type Casting (input(), int(), float(), str()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/007_topic_type_casting_input_int_float_str.livemd) |
| 008 | 🟢Beginner | Topic | লজিক্যাল Operators (and, or, not) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/008_topic_operators_and_or_not.livemd) |
| 009 | 🟢Beginner | Topic | বেসিক String অপারেশন (Concatenation, Repetition, Indexing []) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/009_topic_string_concatenation_repetition_indexing.livemd) |
| 010 | 🟢Beginner | Topic | String ফরম্যাটিং (f-strings, .format()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/010_topic_string_f_strings_format.livemd) |
| 011 | 🟢Beginner | Topic | সাধারণ String Methods (lower(), upper(), strip(), replace(), split()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/011_topic_string_methods_lower_upper_strip_replace_split.livemd) |
| 012 | 🟢Beginner | PROJECT | ইন্টারেক্টিভ ইউজার প্রোফাইল জেনারেটর (I/O, formatting, string methods) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/012_project_i_o_formatting_string_methods.livemd) |
| 013 | 🟢Beginner | Topic | কন্ট্রোল ফ্লো: বেসিক কন্ডিশনাল (if, else) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/013_topic_if_else.livemd) |
| 014 | 🟢Beginner | Topic | কন্ট্রোল ফ্লো: চেইনড এবং নেস্টেড কন্ডিশনাল (elif, nested if) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/014_topic_elif_nested_if.livemd) |
| 015 | 🟢Beginner | Topic | কন্ট্রোল ফ্লো: Structural Pattern Matching (match/case) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/015_topic_structural_pattern_matching_match_case.livemd) |
| 016 | 🟢Beginner | Topic | Lists এর পরিচিতি (Creation, Indexing, Mutability concept) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/016_topic_lists_creation_indexing_mutability_concept.livemd) |
| 017 | 🟢Beginner | Topic | List পরিবর্তনের Methods (append(), insert(), extend(), remove(), pop()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/017_topic_list_methods_append_insert_extend_remove_pop.livemd) |
| 018 | 🟢Beginner | Topic | Sequence Slicing এবং Strides ([start:stop:step]) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/018_topic_sequence_slicing_strides_start_stop_step.livemd) |
| 019 | 🟢Beginner | PROJECT | বেসিক টু-ডু ম্যানেজার (Conditionals এবং List ম্যানিপুলেশন) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/019_project_conditionals_list.livemd) |
| 020 | 🟢Beginner | Topic | Tuples এর পরিচিতি (Creation, Immutability, Unpacking) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/020_topic_tuples_creation_immutability_unpacking.livemd) |
| 021 | 🟢Beginner | Topic | Dictionaries এর পরিচিতি (Key-Value pairs, Creation, Direct Access) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/021_topic_dictionaries_key_value_pairs_creation_direct_access.livemd) |
| 022 | 🟢Beginner | Topic | Dictionary Methods (keys(), values(), items(), get(), update()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/022_topic_dictionary_methods_keys_values_items_get_update.livemd) |
| 023 | 🟢Beginner | Topic | Sets এর পরিচিতি (Creation, Uniqueness, add(), remove()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/023_topic_sets_creation_uniqueness_add_remove.livemd) |
| 024 | 🟢Beginner | Topic | Set অপারেশন (union(), intersection(), difference(), symmetric_difference()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/024_topic_set_union_intersection_difference_symmetric_difference.livemd) |
| 025 | 🟢Beginner | PROJECT | কন্টাক্ট এবং ডেটা ডিডুপ্লিকেটর (Dicts, Tuples, Sets) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/025_project_dicts_tuples_sets.livemd) |
| 026 | 🟢Beginner | Topic | ইটারেশন: for loop (strings, lists, tuples এর ওপর ইটারেশন) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/026_topic_for_loop_strings_lists_tuples.livemd) |
| 027 | 🟢Beginner | Topic | ইটারেশন: while loop এবং কন্ট্রোল স্টেটমেন্ট (break, continue, pass) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/027_topic_while_loop_break_continue_pass.livemd) |
| 028 | 🟢Beginner | Topic | Walrus Operator এর সাথে অ্যাসাইনমেন্ট এক্সপ্রেশন (:=) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/beginner/028_topic_walrus_operator.livemd) |
| 029 | 🟡Intermediate | Topic | অ্যাডভান্সড ইটারেশন টুলস (range(), enumerate(), zip()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/029_topic_range_enumerate_zip.livemd) |
| 030 | 🟡Intermediate | Topic | মেম্বারশিপ Operators (সব ডেটা স্ট্রাকচারে in, not in) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/030_topic_operators_in_not_in.livemd) |
| 031 | 🟡Intermediate | Topic | List Comprehensions (বেসিক syntax এবং কন্ডিশনাল ফিল্টারিং) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/031_topic_list_comprehensions_syntax.livemd) |
| 032 | 🟡Intermediate | PROJECT | স্বয়ংক্রিয় টেক্সট এবং ডেটা ক্লিনার (Loops, Comprehensions, Conditionals) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/032_project_loops_comprehensions_conditionals.livemd) |
| 033 | 🟡Intermediate | Topic | Dictionary এবং Set Comprehensions (Syntax এবং ফিল্টারিং) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/033_topic_dictionary_set_comprehensions_syntax.livemd) |
| 034 | 🟡Intermediate | Topic | Functions এর পরিচিতি (def, বেসিক return স্টেটমেন্ট) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/034_topic_functions_def_return.livemd) |
| 035 | 🟡Intermediate | Topic | Function আর্গুমেন্ট: Positional, Keyword, এবং Default Values | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/035_topic_function_positional_keyword_default_values.livemd) |
| 036 | 🟡Intermediate | Topic | ফ্লেক্সিবল আর্গুমেন্ট (*args, **kwargs) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/036_topic_args_kwargs.livemd) |
| 037 | 🟡Intermediate | Topic | ভেরিয়েবল স্কোপ - Variable Scope (local, global, nonlocal ধারণা) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/037_topic_variable_scope_local_global_nonlocal.livemd) |
| 038 | 🟡Intermediate | PROJECT | কমান্ড-লাইন ম্যাথ ইউটিলিটি (Functions, Scope, Flexible args) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/038_project_functions_scope_flexible_args.livemd) |
| 039 | 🟡Intermediate | Topic | Lambda Functions (অ্যানোনিমাস একক-এক্সপ্রেশন ফাংশন) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/039_topic_lambda_functions.livemd) |
| 040 | 🟡Intermediate | Topic | Higher-Order Functions (map(), filter()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/040_topic_higher_order_functions_map_filter.livemd) |
| 041 | 🟡Intermediate | Topic | reduce() ফাংশন (functools থেকে ইম্পোর্ট করা) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/041_topic_reduce_functools.livemd) |
| 042 | 🟡Intermediate | Topic | Modules এবং import স্টেটমেন্টের পরিচিতি (import, from ... import ...) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/042_topic_modules_import_import_from_import.livemd) |
| 043 | 🟡Intermediate | Topic | স্ট্যান্ডার্ড Math এবং Random মডিউল (math ইউটিলিটি, random সিলেকশন এবং জেনারেশন) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/043_topic_math_random_math_random.livemd) |
| 044 | 🟡Intermediate | Topic | স্ট্যান্ডার্ড Datetime মডিউল (datetime, timedelta, স্ট্রিং ফরম্যাটিং %Y-%m-%d) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/044_topic_datetime_datetime_timedelta_y_m_d.livemd) |
| 045 | 🟡Intermediate | PROJECT | টাইম-ট্র্যাকড পাসওয়ার্ড জেনারেটর (Functions, Datetime, Random) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/045_project_functions_datetime_random.livemd) |
| 046 | 🟡Intermediate | Topic | এরর হ্যান্ডলিংয়ের মূল বিষয় (try, except ব্লক) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/046_topic_try_except.livemd) |
| 047 | 🟡Intermediate | Topic | অ্যাডভান্সড এরর হ্যান্ডলিং (finally, else, নির্দিষ্ট exception টাইপ ধরা) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/047_topic_finally_else_exception.livemd) |
| 048 | 🟡Intermediate | Topic | কাস্টম Exceptions তৈরি করা (raise, assert স্টেটমেন্ট) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/048_topic_exceptions_raise_assert.livemd) |
| 049 | 🟡Intermediate | Topic | আধুনিক পাথ হ্যান্ডলিং (pathlib.Path ফাংশনাল অপারেশন এবং ট্রাভার্সাল) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/049_topic_pathlib_path.livemd) |
| 050 | 🟡Intermediate | Topic | বেসিক ফাইল I/O (টেক্সট ফাইল খোলা, পড়া এবং বন্ধ করা) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/050_topic_i_o.livemd) |
| 051 | 🟡Intermediate | Topic | টেক্সট ফাইলে ডেটা লেখা এবং অ্যাপেন্ড করা ('w', 'a' মোড) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/051_topic_w_a.livemd) |
| 052 | 🟡Intermediate | Topic | Context Managers (নিরাপদ ফাইল হ্যান্ডলিংয়ের জন্য with open() syntax) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/052_topic_context_managers_with_open_syntax.livemd) |
| 053 | 🟡Intermediate | PROJECT | স্বয়ংক্রিয় লগ ফাইল অ্যানালাইজার (File I/O, এরর হ্যান্ডলিং, String Parsing) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/053_project_file_i_o_string_parsing.livemd) |
| 054 | 🟡Intermediate | Topic | JSON ডেটা হ্যান্ডলিং (json.load(), json.loads(), json.dump(), json.dumps()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/054_topic_json_json_load_json_loads_json_dump_json_dumps.livemd) |
| 055 | 🟡Intermediate | Topic | CSV ফাইল নিয়ে কাজ করা (csv.reader(), csv.DictReader(), csv.writer()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/intermediate/055_topic_csv_csv_reader_csv_dictreader_csv_writer.livemd) |
| 056 | 🔴Advanced | Topic | এনভায়রনমেন্ট ভেরিয়েবল এবং কনফিগারেশন (os.environ, os.getenv()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/056_topic_os_environ_os_getenv.livemd) |
| 057 | 🔴Advanced | Topic | python-dotenv দিয়ে সিক্রেট ম্যানেজমেন্ট (.env ফাইল নিরাপদে লোড করা) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/057_topic_python_dotenv_env.livemd) |
| 058 | 🔴Advanced | Topic | HTTP প্রোটোকল বেসিক এবং requests মডিউল (requests.get(), Status Codes) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/058_topic_http_requests_requests_get_status_codes.livemd) |
| 059 | 🔴Advanced | Topic | API রেসপন্স হ্যান্ডলিং (response.json() দিয়ে JSON পার্সিং) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/059_topic_api_response_json_json.livemd) |
| 060 | 🔴Advanced | Topic | অ্যাডভান্সড API হ্যান্ডলিং: পেজিনেশন এবং Cursors নেভিগেশন | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/060_topic_api_cursors.livemd) |
| 061 | 🔴Advanced | PROJECT | সুরক্ষিত API ডেটা ফেচার (Requests, JSON, dotenv, File I/O) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/061_project_api_requests_json_dotenv_file_i_o.livemd) |
| 062 | 🔴Advanced | Topic | অ্যাডভান্সড requests: URL Query Parameters এবং কাস্টম Headers | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/062_topic_requests_url_query_parameters_headers.livemd) |
| 063 | 🔴Advanced | Topic | অ্যাডভান্সড requests: POST রিকোয়েস্ট এবং JSON Payloads পাঠানো | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/063_topic_requests_post_json_payloads.livemd) |
| 064 | 🔴Advanced | Topic | API তে এরর হ্যান্ডলিং (response.raise_for_status(), Request Timeouts) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/064_topic_api_response_raise_for_status_request_timeouts.livemd) |
| 065 | 🔴Advanced | Topic | collections মডিউল (অপ্টিমাইজড কাউন্টিং/গ্রুপিংয়ের জন্য Counter, defaultdict) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/065_topic_collections_counter_defaultdict.livemd) |
| 066 | 🔴Advanced | Topic | collections.deque দিয়ে দক্ষ ডাবল-এন্ডেড কিউ (দ্রুত append/pop অপারেশন) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/066_topic_collections_deque_append_pop.livemd) |
| 067 | 🔴Advanced | Topic | collections.namedtuple দিয়ে লাইটওয়েট স্ট্রাকচার্ড রেকর্ড | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/067_topic_collections_namedtuple.livemd) |
| 068 | 🔴Advanced | PROJECT | API রেসপন্স অ্যানালাইজার (Requests, এরর হ্যান্ডলিং, Collections, Namedtuples) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/068_project_api_requests_collections_namedtuples.livemd) |
| 069 | 🔴Advanced | Topic | contextlib দিয়ে কাস্টম Context Managers (@contextmanager ডেকোরেটর) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/069_topic_contextlib_context_managers_contextmanager.livemd) |
| 070 | 🔴Advanced | Topic | Generators এবং yield কিওয়ার্ড (Lazy evaluation ধারণা) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/070_topic_generators_yield_lazy_evaluation.livemd) |
| 071 | 🔴Advanced | Topic | Generator Expressions (মেমরি-দক্ষ ইটারেবল জেনারেশন) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/071_topic_generator_expressions.livemd) |
| 072 | 🔴Advanced | Topic | অ্যাডভান্সড ফাংশন: Closures এবং Nested Functions (অবজেক্ট ছাড়াই স্টেট ধরে রাখা) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/072_topic_closures_nested_functions.livemd) |
| 073 | 🔴Advanced | Topic | dataclasses দিয়ে স্ট্রাকচার্ড ডেটা কন্টেইনার | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/073_topic_dataclasses.livemd) |
| 074 | 🔴Advanced | Topic | Decorators: ফাংশন র‍্যাপার তৈরি এবং প্রয়োগ করা (@wrapper syntax) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/074_topic_decorators_wrapper_syntax.livemd) |
| 075 | 🔴Advanced | PROJECT | API রেট লিমিটর এবং ক্যাশিং Decorator | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/075_project_api_decorator.livemd) |
| 076 | 🔴Advanced | Topic | ফাইল সিস্টেম নেভিগেশন এবং ম্যানিপুলেশন (os.listdir(), os.mkdir(), os.remove()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/076_topic_os_listdir_os_mkdir_os_remove.livemd) |
| 077 | 🔴Advanced | Topic | tempfile দিয়ে অস্থায়ী ফাইল হ্যান্ডলিং (নিরাপদ অস্থায়ী ফাইল এবং ডিরেক্টরি) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/077_topic_tempfile.livemd) |
| 078 | 🔴Advanced | Topic | হাই-লেভেল ফাইল অপারেশন (shutil.copy(), shutil.move(), shutil.rmtree()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/078_topic_shutil_copy_shutil_move_shutil_rmtree.livemd) |
| 079 | 🔴Advanced | Topic | bisect দিয়ে বাইনারি সার্চ এবং সর্টেড ইনসারশন (দক্ষতার সাথে সর্টেড লিস্ট বজায় রাখা) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/079_topic_bisect.livemd) |
| 080 | 🔴Advanced | Topic | Subprocesses: সিস্টেম কমান্ড কার্যকর করা (subprocess.run(), আউটপুট ক্যাপচার করা) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/080_topic_subprocesses_subprocess_run.livemd) |
| 081 | 🔴Advanced | Topic | Regular Expressions: ম্যাচিং এবং সার্চিং (re.search(), re.match(), বেসিক প্যাটার্ন) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/081_topic_regular_expressions_re_search_re_match.livemd) |
| 082 | 🔴Advanced | Topic | Regular Expressions: এক্সট্রাকশন এবং সাবস্টিটিউশন (re.findall(), re.sub(), ক্যাপচার গ্রুপ) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/082_topic_regular_expressions_re_findall_re_sub.livemd) |
| 083 | 🔴Advanced | PROJECT | সিস্টেম লগ পার্সার এবং Regex এক্সট্রাক্টর (Regex, os, pathlib) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/083_project_regex_regex_os_pathlib.livemd) |
| 084 | 🔴Advanced | Topic | logging মডিউল: কনফিগারেশন এবং লগ লেভেল (DEBUG, INFO, WARNING, ERROR) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/084_topic_logging_debug_info_warning_error.livemd) |
| 085 | 🔴Advanced | Topic | অ্যাডভান্সড logging: Handlers এবং Formatters (একই সাথে কনসোল এবং ফাইলে লগ পাঠানো) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/085_topic_logging_handlers_formatters.livemd) |
| 086 | 🔴Advanced | Topic | Itertools: ইনফিনিট এবং কম্বিনেটোরিক ইটারেটর (count, cycle, combinations) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/086_topic_itertools_count_cycle_combinations.livemd) |
| 087 | 🔴Advanced | Topic | Itertools: ডেটা গ্রুপিং এবং চেইনিং (groupby, chain) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/087_topic_itertools_groupby_chain.livemd) |
| 088 | 🔴Advanced | Topic | Type Hinting এর পরিচিতি (স্কেলার টাইপ: int, str, bool) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/088_topic_type_hinting_int_str_bool.livemd) |
| 089 | 🔴Advanced | Topic | অ্যাডভান্সড Type Hinting (List, Dict, Optional, Union, Callable) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/089_topic_type_hinting_list_dict_optional_union_callable.livemd) |
| 090 | 🔴Advanced | PROJECT | টাইপ-সেফ ওয়েবহুক পেলোড প্রসেসর (Type Hints, Logging, Itertools) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/090_project_type_hints_logging_itertools.livemd) |
| 091 | 🔴Advanced | Topic | স্ক্রিপ্ট ডিবাগিং বুটক্যাম্প: pdb এর ব্যবহার (tracepoints সেট করা, লজিক স্টেপিং) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/091_topic_pdb_tracepoints.livemd) |
| 092 | 🔴Advanced | Topic | স্ক্রিপ্ট রিফ্যাক্টরিং চ্যালেঞ্জ: DRY এবং সিঙ্গেল রেসপন্সিবিলিটি (বিশাল ফাংশন ভাগ করা) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/092_topic_dry.livemd) |
| 093 | 🔴Advanced | Topic | অ্যাসিঙ্ক্রোনাস প্রোগ্রামিং বেসিক (async def, await, Event Loop ধারণা) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/093_topic_async_def_await_event_loop.livemd) |
| 094 | 🔴Advanced | Topic | অ্যাসিঙ্ক্রোনাস টাস্ক ম্যানেজমেন্ট (asyncio.gather(), asyncio.create_task()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/094_topic_asyncio_gather_asyncio_create_task.livemd) |
| 095 | 🔴Advanced | Topic | টাইমআউট এবং অ্যাসিঙ্ক এক্সেপশন (asyncio.wait_for(), অ্যাসিঙ্ক এরর হ্যান্ডলিং) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/095_topic_asyncio_wait_for.livemd) |
| 096 | 🔴Advanced | Topic | Threading বনাম Asyncio (ধারণাগত পার্থক্য এবং GIL এর সাথে থ্রেড সীমাবদ্ধতা) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/096_topic_threading_asyncio_gil.livemd) |
| 097 | 🔴Advanced | PROJECT | কনকারেন্ট মাল্টি-API ডেটা অ্যাগ্রিগেটর (Asyncio, এরর হ্যান্ডলিং, Logging) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/097_project_api_asyncio_logging.livemd) |
| 098 | 🔴Advanced | Topic | ফাংশনাল টেস্টিং (নেটিভ assert ব্যবহার করে আইসোলেটেড টেস্ট ফাংশন লেখা) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/098_topic_assert.livemd) |
| 099 | 🔴Advanced | Topic | নেটিভ ফাংশন মকিং (unittest.mock.patch কে ডেকোরেটর/context manager হিসেবে ব্যবহার) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/099_topic_unittest_mock_patch_context_manager.livemd) |
| 100 | 🔴Advanced | Topic | প্রজেক্ট ডিপেন্ডেন্সি ম্যানেজমেন্ট (venv তৈরি, pip freeze > requirements.txt) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/100_topic_venv_pip_freeze_requirements_txt.livemd) |
| 101 | 🔴Advanced | Topic | শক্তিশালী CLIs তৈরি (argparse, পজিশনাল আর্গুমেন্ট এবং ফ্ল্যাগ) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/101_topic_clis_argparse.livemd) |
| 102 | 🔴Advanced | Topic | পারফরম্যান্স পরিমাপ এবং প্রোফাইলিং (timeit মডিউল) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/102_topic_timeit.livemd) |
| 103 | 🔴Advanced | Topic | functools.singledispatch দিয়ে টাইপ অনুযায়ী Function ডিসপ্যাচ | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/103_topic_functools_singledispatch_function.livemd) |
| 104 | 🔴Advanced | PROJECT | প্রোডাকশন-গ্রেড CLI ইউটিলিটি | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/104_project_cli.livemd) |
| 105 | 🔴Advanced | Topic | ডেটা হ্যাশিং এবং ইন্টিগ্রিটি ভ্যালিডেশন (SHA256 এর জন্য hashlib) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/105_topic_sha256_hashlib.livemd) |
| 106 | 🔴Advanced | Topic | weakref দিয়ে উইক রেফারেন্স (মেমরি-নিরাপদ অবজেক্ট রেফারেন্স) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/106_topic_weakref.livemd) |
| 107 | 🔴Advanced | Topic | অ্যাডভান্সড ফাংশনাল ইউটিলিটি (functools.partial, মেমোইজেশনের জন্য @lru_cache) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/107_topic_functools_partial_lru_cache.livemd) |
| 108 | 🔴Advanced | Topic | atexit দিয়ে স্ক্রিপ্ট শাটডাউন হুক (ক্লিনআপ হ্যান্ডলার) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/108_topic_atexit.livemd) |
| 109 | 🔴Advanced | Topic | signal দিয়ে সিস্টেম সিগন্যাল হ্যান্ডলিং (স্ক্রিপ্ট মার্জিতভাবে বন্ধ করা) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/109_topic_signal.livemd) |
| 110 | 🔴Advanced | Topic | importlib দিয়ে ডায়নামিক ইম্পোর্ট (রানটাইম মডিউল লোডিং) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/110_topic_importlib.livemd) |
| 111 | 🔴Advanced | Topic | uuid দিয়ে ইউনিক আইডি জেনারেশন (ডিস্ট্রিবিউটেড সিস্টেমের জন্য uuid4) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/111_topic_uuid_uuid4.livemd) |
| 112 | 🔴Advanced | PROJECT | এক্সটেনসিবল অটোমেশন ফ্রেমওয়ার্ক | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/bn/advanced/112_project.livemd) |

*বিষয়বস্তুর সম্পূর্ণ তালিকা (১১২টি টপিক + প্রজেক্ট) প্রতিটি ভাষার ফোল্ডারের ভেতরে উপলব্ধ রয়েছে।*

---

## 🏛️ আর্কিটেকচার এবং মেন্টরবৃন্দ

প্রতিটি ল্যাবে একটি **ব্যাখ্যা দ্বার** (Explanation Gate) অন্তর্ভুক্ত রয়েছে যেখানে একজন বিশেষায়িত AI মেন্টর আপনাকে শেখার প্রক্রিয়ায় গাইড করে। প্রতিটি ধাপের মেন্টরের নিজস্ব আলাদা ব্যক্তিত্ব রয়েছে, যা সেই ধাপের মনস্তাত্ত্বিক এবং শিক্ষাগত চাহিদার সাথে মিল রেখে ডিজাইন করা হয়েছে:

| ধাপ | মেন্টর | ব্যক্তিত্ব | এটি কী শেখায় |
|---|---|---|---|
| **১** | নিরাপদ নির্দেশক | আন্তরিক, ধৈর্যশীল, বড় ভাই/বোনের মতো | নিরাপদে সিনট্যাক্স অন্বেষণ করা, "ভাইব কোডিং" দূর করা |
| **২** | বিশ্লেষণাত্মক অংশীদার | কৌতূহলী, কফি-চালিত "লগ গোয়েন্দা" | এরর ট্রেস (error traces) পড়া, সিস্টেম ক্র্যাশের কারণ বোঝা |
| **৩** | লজিক্যাল মাচান | সুশৃঙ্খল, উৎসাহদাতা "সিনিয়র বিল্ডার" | ডেটা প্রবাহকে ভিজ্যুয়ালাইজ করা (ইনপুট → ট্রান্সফর্ম → আউটপুট) |
| **৪** | মার্জিত সমালোচক | ব্যঙ্গাত্মক, খাঁটি নীতিবাদী, "কঠোর ভালোবাসা" (tough love) | ইডিওম্যাটিক কোড (idiomatic code), ফাংশনাল প্যাটার্ন, খারাপ অভ্যাস ত্যাগ করা |
| **৫** | কৌশলগত অংশীদার | দূরদর্শী, পেশাদার "সিস্টেম আর্কিটেক্ট" | এজ কেস (edge cases), ফল্ট টলারেন্স, বিজনেস লজিকের সাথে সামঞ্জস্য রাখা |

*এই রিপোজিটরিতে **ধাপ ১ (নিরাপদ নির্দেশক)** অন্তর্ভুক্ত রয়েছে।*

---

## 🔗 দরকারী লিংকসমূহ

[Coding5s.com](https://coding5s.com) | [Udemy (Coding5s Premium)](https://www.udemy.com/user/wilbarrios/) | [GitHub](https://github.com/WilfredoBarrios)

---

## 🤝 অবদান (Contributions)

আপনার কি কোনো মতামত বা নতুন ফিচারের পরামর্শ আছে? আপনি যদি যেকোনো উপায়ে এই প্রজেক্টটিকে সমর্থন করতে চান, তবে নির্দ্বিধায় একটি 'issue' খুলুন বা আপনার অবদান রাখুন!

---

## 📄 লাইসেন্স

MIT © [Wil Barrios](https://github.com/WilfredoBarrios)

---
⚡ *Coding5s সিস্টেম — কারিগরি দক্ষতায় অনন্যতা অর্জনের জন্য ডিজাইন করা লার্নিং।*
