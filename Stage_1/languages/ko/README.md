# 🧪 Python Core & Scripting 인터랙티브 랩 — 한국어 🇰🇷

[![Livebook](https://img.shields.io/badge/Livebook-FF6B6B?logo=livebook&logoColor=white)](https://livebook.dev)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **눈으로만 읽지 말고, 직접 코드를 쓰며 Python을 배우세요.**
> 본 과정은 Livebook의 인터랙티브 환경을 활용하여 코어 스크립팅부터 기술적 마스터(전문가) 단계까지 도달할 수 있도록 설계된 **Coding5s** 인터랙티브 커리큘럼의 한국어 버전입니다.

---

## 🚀 어떻게 시작하나요?

본 랩을 인터랙티브하게 경험하려면 컴퓨터에 Python 런타임 연동이 완료된 **Livebook**이 설치되어 있어야 합니다.

1. **Livebook 설치:** [livebook.dev](https://livebook.dev)에서 다운로드하세요.
2. **랩 열기:** 아래 폴더들을 살펴보고 각 파일 내부에 있는 **"Run in Livebook"** 버튼을 클릭하거나, Livebook 세션에 URL을 직접 임포트하세요.

---

## 📚 Coding5s 방법론 (5단계)

저희의 접근 방식은 **통제된 인지적 마찰(Controlled Cognitive Friction)**에 기반합니다. 각 랩은 다음 단계를 통해 학습을 안내합니다:

| 단계 | 명칭 | 목표 |
|-------|------|-----------|
| **1** | 기초 실습 (Practice) | 제로 베이스에서 직접 코드 작성하기 |
| **2** | 디버깅 (Debug) | 의도적으로 심어놓은 구문(Syntax) 및 논리 에러 찾기 |
| **3** | 코드 완성 (Complete) | 아키텍처 및 알고리즘의 공백 채우기 |
| **4** | 리팩터링 (Refactor) | 기존 스크립트 최적화 (플랫 구조 vs 모듈화 구조) |
| **5** | 기능 확장 (Extend) | 프로덕션 환경에 바로 적용 가능한 새로운 기능 추가 |

*본 저장소(Repository)는 **단계 1 (기초 실습)**을 포함하고 있습니다.*

---

## 🛠️ 각 Livebook은 어떻게 사용하나요?

각 `.livemd` 파일 내부에서 다음의 간단한 워크플로우를 따르세요:

1. **Livebook**(데스크톱 앱 또는 브라우저 버전)에서 파일을 엽니다.
2. **단계 1 프롬프트**를 복사하여 평소 선호하는 AI 챗(ChatGPT, Gemini, Claude 등)에 붙여넣습니다.
3. AI가 해당 주제에 맞는 **3~5개의 실행 가능한 마이크로 예제**를 생성합니다.
4. 해당 예제들을 Livebook의 **실행 셀(execution cell)**에 복사하고 실행합니다.
5. 코드를 수정하고 실험하면서 출력 결과가 실시간으로 어떻게 바뀌는지 확인합니다.

---

## 🧠 소크라테스식 멘토 (AI)

각 Livebook에는 **멘토(Mentor) 프롬프트**도 포함되어 있습니다. 여러분이 작성한 코드, 그리고 논리에 대한 짧은 설명과 함께 이 프롬프트를 동일한 AI 챗에 붙여넣을 수 있습니다. 멘토는 다음과 같이 행동합니다:

- (처음에는) 정답을 직접 **알려주지 않습니다**
- 스스로 에러를 발견할 수 있도록 소크라테스식 질문을 던집니다
- **프로그래밍 개념**을 설명하기 위해 현실 세계의 비유(Analogy)를 사용합니다
- '느낌대로 코딩하는 습관(Vibe Coding)'을 버리고 진짜 엔지니어링 직관을 기르도록 돕습니다
- 구체적인 질문을 던졌을 때는 시니어 레벨의 전문적인 답변을 제공합니다

---

## 🛠️ 인터랙티브 커리큘럼 — 단계 1: 실습 랩

**Run in Livebook** 배지를 클릭하면 각 랩을 사용자의 환경에서 바로 열 수 있습니다.

| # |  Level |  Type |Topic Name | Interactive Lab |
| :--- | :--- | :--- | :--- | :--- |
| 001 | 🟢Beginner | Topic | 기본 Syntax 및 출력 (print(), Comments, Indentation) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/001_topic_syntax_print_comments_indentation.livemd) |
| 002 | 🟢Beginner | Topic | 변수 및 Dynamic Typing (Assignment, Naming Conventions) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/002_topic_dynamic_typing_assignment_naming_conventions.livemd) |
| 003 | 🟢Beginner | Topic | 기본 데이터 타입 (int, float, str, bool) 및 type() | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/003_topic_int_float_str_bool_type.livemd) |
| 004 | 🟢Beginner | Topic | 산술 연산 (+, -, *, /, //, %, **) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/004_topic.livemd) |
| 005 | 🟢Beginner | Topic | 비교 및 ID 연산자 (==, !=, >, <, is, is not) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/005_topic_id_is_is_not.livemd) |
| 006 | 🟢Beginner | PROJECT | 팁 및 비용 분할 계산기 (Math 연산 및 variables 조합) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/006_project_math_variables.livemd) |
| 007 | 🟢Beginner | Topic | 사용자 입력 및 Type Casting (input(), int(), float(), str()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/007_topic_type_casting_input_int_float_str.livemd) |
| 008 | 🟢Beginner | Topic | 논리 연산자 (and, or, not) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/008_topic_and_or_not.livemd) |
| 009 | 🟢Beginner | Topic | 기본 String 연산 (Concatenation, Repetition, Indexing []) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/009_topic_string_concatenation_repetition_indexing.livemd) |
| 010 | 🟢Beginner | Topic | String 포매팅 (f-strings, .format()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/010_topic_string_f_strings_format.livemd) |
| 011 | 🟢Beginner | Topic | 공통 String Methods (lower(), upper(), strip(), replace(), split()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/011_topic_string_methods_lower_upper_strip_replace_split.livemd) |
| 012 | 🟢Beginner | PROJECT | 대화형 사용자 프로필 생성기 (I/O, formatting, string methods) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/012_project_i_o_formatting_string_methods.livemd) |
| 013 | 🟢Beginner | Topic | 제어 흐름: 기본 조건문 (if, else) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/013_topic_if_else.livemd) |
| 014 | 🟢Beginner | Topic | 제어 흐름: 체인 및 중첩 조건문 (elif, nested if) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/014_topic_elif_nested_if.livemd) |
| 015 | 🟢Beginner | Topic | 제어 흐름: Structural Pattern Matching (match/case) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/015_topic_structural_pattern_matching_match_case.livemd) |
| 016 | 🟢Beginner | Topic | Lists 입문 (Creation, Indexing, Mutability concept) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/016_topic_lists_creation_indexing_mutability_concept.livemd) |
| 017 | 🟢Beginner | Topic | List 수정 Methods (append(), insert(), extend(), remove(), pop()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/017_topic_list_methods_append_insert_extend_remove_pop.livemd) |
| 018 | 🟢Beginner | Topic | Sequence Slicing 및 Strides ([start:stop:step]) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/018_topic_sequence_slicing_strides_start_stop_step.livemd) |
| 019 | 🟢Beginner | PROJECT | 기본 할 일 관리 프로그램 (조건문 및 List 조작) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/019_project_list.livemd) |
| 020 | 🟢Beginner | Topic | Tuples 입문 (Creation, Immutability, Unpacking) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/020_topic_tuples_creation_immutability_unpacking.livemd) |
| 021 | 🟢Beginner | Topic | Dictionaries 입문 (Key-Value pairs, Creation, Direct Access) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/021_topic_dictionaries_key_value_pairs_creation_direct_access.livemd) |
| 022 | 🟢Beginner | Topic | Dictionary Methods (keys(), values(), items(), get(), update()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/022_topic_dictionary_methods_keys_values_items_get_update.livemd) |
| 023 | 🟢Beginner | Topic | Sets 입문 (Creation, Uniqueness, add(), remove()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/023_topic_sets_creation_uniqueness_add_remove.livemd) |
| 024 | 🟢Beginner | Topic | Set 연산 (union(), intersection(), difference(), symmetric_difference()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/024_topic_set_union_intersection_difference_symmetric_difference.livemd) |
| 025 | 🟢Beginner | PROJECT | 연락처 및 데이터 중복 제거기 (Dicts, Tuples, Sets) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/025_project_dicts_tuples_sets.livemd) |
| 026 | 🟢Beginner | Topic | 반복: for 루프 (strings, lists, tuples 반복) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/026_topic_for_strings_lists_tuples.livemd) |
| 027 | 🟢Beginner | Topic | 반복: while 루프 및 제어문 (break, continue, pass) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/027_topic_while_break_continue_pass.livemd) |
| 028 | 🟢Beginner | Topic | Walrus Operator를 사용한 할당 표현식 (:=) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/beginner/028_topic_walrus_operator.livemd) |
| 029 | 🟡Intermediate | Topic | 고급 반복 도구 (range(), enumerate(), zip()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/029_topic_range_enumerate_zip.livemd) |
| 030 | 🟡Intermediate | Topic | 멤버십 연산자 (모든 데이터 구조에서의 in, not in) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/030_topic_in_not_in.livemd) |
| 031 | 🟡Intermediate | Topic | List Comprehensions (기본 syntax 및 조건부 필터링) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/031_topic_list_comprehensions_syntax.livemd) |
| 032 | 🟡Intermediate | PROJECT | 자동 텍스트 및 데이터 클리너 (Loops, Comprehensions, Conditionals) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/032_project_loops_comprehensions_conditionals.livemd) |
| 033 | 🟡Intermediate | Topic | Dictionary 및 Set Comprehensions (Syntax 및 필터링) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/033_topic_dictionary_set_comprehensions_syntax.livemd) |
| 034 | 🟡Intermediate | Topic | Functions 입문 (def, 기본 return 문) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/034_topic_functions_def_return.livemd) |
| 035 | 🟡Intermediate | Topic | Function 인자: Positional, Keyword, 및 Default Values | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/035_topic_function_positional_keyword_default_values.livemd) |
| 036 | 🟡Intermediate | Topic | 가변 인자 (*args, **kwargs) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/036_topic_args_kwargs.livemd) |
| 037 | 🟡Intermediate | Topic | 변수 범위 - Variable Scope (local, global, nonlocal 개념) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/037_topic_variable_scope_local_global_nonlocal.livemd) |
| 038 | 🟡Intermediate | PROJECT | 명령줄 수학 유틸리티 (Functions, Scope, Flexible args) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/038_project_functions_scope_flexible_args.livemd) |
| 039 | 🟡Intermediate | Topic | Lambda Functions (익명 단일 표현식 함수) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/039_topic_lambda_functions.livemd) |
| 040 | 🟡Intermediate | Topic | Higher-Order Functions (map(), filter()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/040_topic_higher_order_functions_map_filter.livemd) |
| 041 | 🟡Intermediate | Topic | reduce() 함수 (functools에서 import) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/041_topic_reduce_functools_import.livemd) |
| 042 | 🟡Intermediate | Topic | Modules 및 import 문 입문 (import, from ... import ...) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/042_topic_modules_import_import_from_import.livemd) |
| 043 | 🟡Intermediate | Topic | 표준 Math 및 Random 모듈 (math 유틸리티, random 선택 및 생성) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/043_topic_math_random_math_random.livemd) |
| 044 | 🟡Intermediate | Topic | 표준 Datetime 모듈 (datetime, timedelta, 문자열 포매팅 %Y-%m-%d) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/044_topic_datetime_datetime_timedelta_y_m_d.livemd) |
| 045 | 🟡Intermediate | PROJECT | 시간 추적 비밀번호 생성기 (Functions, Datetime, Random) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/045_project_functions_datetime_random.livemd) |
| 046 | 🟡Intermediate | Topic | 에러 핸들링 기초 (try, except 블록) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/046_topic_try_except.livemd) |
| 047 | 🟡Intermediate | Topic | 고급 에러 핸들링 (finally, else, 특정 exception 유형 캡처) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/047_topic_finally_else_exception.livemd) |
| 048 | 🟡Intermediate | Topic | 사용자 정의 예외 발생 (raise, assert 문) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/048_topic_raise_assert.livemd) |
| 049 | 🟡Intermediate | Topic | 현대적인 경로 처리 (pathlib.Path 기능적 연산 및 탐색) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/049_topic_pathlib_path.livemd) |
| 050 | 🟡Intermediate | Topic | 기본 파일 I/O (텍스트 파일 열기, 읽기 및 닫기) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/050_topic_i_o.livemd) |
| 051 | 🟡Intermediate | Topic | 텍스트 파일에 데이터 쓰기 및 추가 ('w', 'a' 모드) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/051_topic_w_a.livemd) |
| 052 | 🟡Intermediate | Topic | Context Managers (안전한 파일 처리를 위한 with open() syntax) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/052_topic_context_managers_with_open_syntax.livemd) |
| 053 | 🟡Intermediate | PROJECT | 자동 로그 파일 분석기 (File I/O, 에러 핸들링, String Parsing) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/053_project_file_i_o_string_parsing.livemd) |
| 054 | 🟡Intermediate | Topic | JSON 데이터 처리 (json.load(), json.loads(), json.dump(), json.dumps()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/054_topic_json_json_load_json_loads_json_dump_json_dumps.livemd) |
| 055 | 🟡Intermediate | Topic | CSV 파일 작업 (csv.reader(), csv.DictReader(), csv.writer()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/intermediate/055_topic_csv_csv_reader_csv_dictreader_csv_writer.livemd) |
| 056 | 🔴Advanced | Topic | 환경 변수 및 설정 (os.environ, os.getenv()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/056_topic_os_environ_os_getenv.livemd) |
| 057 | 🔴Advanced | Topic | python-dotenv를 이용한 비밀 정보 관리 (.env 파일 안전하게 로드) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/057_topic_python_dotenv_env.livemd) |
| 058 | 🔴Advanced | Topic | HTTP 프로토콜 기초 및 requests 모듈 (requests.get(), Status Codes) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/058_topic_http_requests_requests_get_status_codes.livemd) |
| 059 | 🔴Advanced | Topic | API 응답 처리 (response.json()을 이용한 JSON 파싱) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/059_topic_api_response_json_json.livemd) |
| 060 | 🔴Advanced | Topic | 고급 API 처리: 페이지네이션 및 Cursors 탐색 | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/060_topic_api_cursors.livemd) |
| 061 | 🔴Advanced | PROJECT | 보안 API 데이터 페처 (Requests, JSON, dotenv, File I/O) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/061_project_api_requests_json_dotenv_file_i_o.livemd) |
| 062 | 🔴Advanced | Topic | 고급 requests: URL Query Parameters 및 Custom Headers | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/062_topic_requests_url_query_parameters_custom_headers.livemd) |
| 063 | 🔴Advanced | Topic | 고급 requests: POST 요청 및 JSON Payloads 전송 | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/063_topic_requests_post_json_payloads.livemd) |
| 064 | 🔴Advanced | Topic | API 에러 핸들링 (response.raise_for_status(), Request Timeouts) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/064_topic_api_response_raise_for_status_request_timeouts.livemd) |
| 065 | 🔴Advanced | Topic | collections 모듈 (최적화된 카운팅/그룹화를 위한 Counter, defaultdict) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/065_topic_collections_counter_defaultdict.livemd) |
| 066 | 🔴Advanced | Topic | collections.deque를 이용한 효율적인 데크 (빠른 append/pop 연산) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/066_topic_collections_deque_append_pop.livemd) |
| 067 | 🔴Advanced | Topic | collections.namedtuple을 이용한 가벼운 구조화 레코드 | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/067_topic_collections_namedtuple.livemd) |
| 068 | 🔴Advanced | PROJECT | API 응답 분석기 (Requests, 에러 핸들링, Collections, Namedtuples) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/068_project_api_requests_collections_namedtuples.livemd) |
| 069 | 🔴Advanced | Topic | contextlib를 이용한 커스텀 Context Managers (@contextmanager 데코레이터) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/069_topic_contextlib_context_managers_contextmanager.livemd) |
| 070 | 🔴Advanced | Topic | Generators 및 yield 키워드 (Lazy evaluation 개념) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/070_topic_generators_yield_lazy_evaluation.livemd) |
| 071 | 🔴Advanced | Topic | Generator Expressions (메모리 효율적인 이터러블 생성) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/071_topic_generator_expressions.livemd) |
| 072 | 🔴Advanced | Topic | 고급 함수: Closures 및 Nested Functions (객체 없이 상태 유지) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/072_topic_closures_nested_functions.livemd) |
| 073 | 🔴Advanced | Topic | dataclasses를 이용한 구조화된 데이터 컨테이너 | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/073_topic_dataclasses.livemd) |
| 074 | 🔴Advanced | Topic | Decorators: Function 래퍼 생성 및 적용 (@wrapper syntax) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/074_topic_decorators_function_wrapper_syntax.livemd) |
| 075 | 🔴Advanced | PROJECT | API 속도 제한기 및 캐싱 Decorator | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/075_project_api_decorator.livemd) |
| 076 | 🔴Advanced | Topic | 파일 시스템 탐색 및 조작 (os.listdir(), os.mkdir(), os.remove()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/076_topic_os_listdir_os_mkdir_os_remove.livemd) |
| 077 | 🔴Advanced | Topic | tempfile을 이용한 임시 파일 처리 (안전한 임시 파일 및 디렉터리) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/077_topic_tempfile.livemd) |
| 078 | 🔴Advanced | Topic | 상위 수준 파일 작업 (shutil.copy(), shutil.move(), shutil.rmtree()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/078_topic_shutil_copy_shutil_move_shutil_rmtree.livemd) |
| 079 | 🔴Advanced | Topic | bisect를 이용한 이진 탐색 및 정렬 삽입 (정렬된 리스트의 효율적 유지) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/079_topic_bisect.livemd) |
| 080 | 🔴Advanced | Topic | Subprocesses: 시스템 명령 실행 (subprocess.run(), 출력 캡처) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/080_topic_subprocesses_subprocess_run.livemd) |
| 081 | 🔴Advanced | Topic | 정규 표현식: 매칭 및 검색 (re.search(), re.match(), 기본 패턴) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/081_topic_re_search_re_match.livemd) |
| 082 | 🔴Advanced | Topic | 정규 표현식: 추출 및 치환 (re.findall(), re.sub(), 캡처 그룹) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/082_topic_re_findall_re_sub.livemd) |
| 083 | 🔴Advanced | PROJECT | 시스템 로그 파서 및 Regex 추출기 (Regex, os, pathlib) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/083_project_regex_regex_os_pathlib.livemd) |
| 084 | 🔴Advanced | Topic | logging 모듈: 설정 및 로그 레벨 (DEBUG, INFO, WARNING, ERROR) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/084_topic_logging_debug_info_warning_error.livemd) |
| 085 | 🔴Advanced | Topic | 고급 logging: Handlers 및 Formatters (콘솔과 파일에 동시 로그 전송) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/085_topic_logging_handlers_formatters.livemd) |
| 086 | 🔴Advanced | Topic | Itertools: 무한 및 조합 이터레이터 (count, cycle, combinations) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/086_topic_itertools_count_cycle_combinations.livemd) |
| 087 | 🔴Advanced | Topic | Itertools: 데이터 그룹화 및 연결 (groupby, chain) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/087_topic_itertools_groupby_chain.livemd) |
| 088 | 🔴Advanced | Topic | Type Hinting 입문 (스칼라 타입: int, str, bool) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/088_topic_type_hinting_int_str_bool.livemd) |
| 089 | 🔴Advanced | Topic | 고급 Type Hinting (List, Dict, Optional, Union, Callable) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/089_topic_type_hinting_list_dict_optional_union_callable.livemd) |
| 090 | 🔴Advanced | PROJECT | 타입 안정성이 보장된 Webhook 페이로드 프로세서 (Type Hints, Logging, Itertools) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/090_project_webhook_type_hints_logging_itertools.livemd) |
| 091 | 🔴Advanced | Topic | 스크립트 디버깅 부트캠프: pdb 사용 (tracepoints 설정, 로직 단계별 실행) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/091_topic_pdb_tracepoints.livemd) |
| 092 | 🔴Advanced | Topic | 스크립트 리팩터링 과제: DRY 및 단일 책임 원칙 (거대 함수 분할) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/092_topic_dry.livemd) |
| 093 | 🔴Advanced | Topic | 비동기 프로그래밍 기초 (async def, await, Event Loop 개념) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/093_topic_async_def_await_event_loop.livemd) |
| 094 | 🔴Advanced | Topic | 비동기 작업 관리 (asyncio.gather(), asyncio.create_task()) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/094_topic_asyncio_gather_asyncio_create_task.livemd) |
| 095 | 🔴Advanced | Topic | 타임아웃 및 비동기 예외 (asyncio.wait_for(), 비동기 에러 핸들링) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/095_topic_asyncio_wait_for.livemd) |
| 096 | 🔴Advanced | Topic | Threading vs. Asyncio (개념적 차이 및 GIL에 따른 기능적 스레드 제한) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/096_topic_threading_vs_asyncio_gil.livemd) |
| 097 | 🔴Advanced | PROJECT | 동시 다중 API 데이터 애그리게이터 (Asyncio, 에러 핸들링, Logging) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/097_project_api_asyncio_logging.livemd) |
| 098 | 🔴Advanced | Topic | 기능 테스트 (기본 assert를 이용한 격리된 테스트 함수 작성) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/098_topic_assert.livemd) |
| 099 | 🔴Advanced | Topic | 기본 함수 Mocking (unittest.mock.patch를 데코레이터/Context Manager로 사용) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/099_topic_mocking_unittest_mock_patch_context_manager.livemd) |
| 100 | 🔴Advanced | Topic | 프로젝트 의존성 관리 (venv 생성, pip freeze > requirements.txt) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/100_topic_venv_pip_freeze_requirements_txt.livemd) |
| 101 | 🔴Advanced | Topic | 견고한 CLIs 빌드 (argparse, 위치 기반 인자 및 플래그) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/101_topic_clis_argparse.livemd) |
| 102 | 🔴Advanced | Topic | 성능 측정 및 프로파일링 (timeit 모듈) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/102_topic_timeit.livemd) |
| 103 | 🔴Advanced | Topic | functools.singledispatch를 이용한 타입별 Function 디스패치 | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/103_topic_functools_singledispatch_function.livemd) |
| 104 | 🔴Advanced | PROJECT | 프로덕션 수준의 CLI 유틸리티 | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/104_project_cli.livemd) |
| 105 | 🔴Advanced | Topic | 데이터 해싱 및 무결성 검증 (SHA256을 위한 hashlib) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/105_topic_sha256_hashlib.livemd) |
| 106 | 🔴Advanced | Topic | weakref를 이용한 약한 참조 (메모리 안전 객체 참조) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/106_topic_weakref.livemd) |
| 107 | 🔴Advanced | Topic | 고급 함수형 유틸리티 (functools.partial, 메모이제이션을 위한 @lru_cache) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/107_topic_functools_partial_lru_cache.livemd) |
| 108 | 🔴Advanced | Topic | atexit를 이용한 스크립트 종료 훅 (정리 핸들러) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/108_topic_atexit.livemd) |
| 109 | 🔴Advanced | Topic | signal을 이용한 시스템 시그널 처리 (스크립트의 정상적인 종료) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/109_topic_signal.livemd) |
| 110 | 🔴Advanced | Topic | importlib를 이용한 동적 임포트 (런타임 모듈 로드) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/110_topic_importlib.livemd) |
| 111 | 🔴Advanced | Topic | uuid를 이용한 고유 ID 생성 (분산 시스템용 uuid4) | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/111_topic_uuid_id_uuid4.livemd) |
| 112 | 🔴Advanced | PROJECT | 확장 가능한 자동화 프레임워크 | [![Run in Livebook](https://livebook.dev/badge/v1/blue.svg)](https://livebook.dev/run?url=https://github.com/WilfredoBarrios/Coding5s-Python-Core-and-Scripting/blob/main/Stage_1/ko/advanced/112_project.livemd) |

*전체 목차(112개 주제 + 프로젝트)는 각 언어별 폴더 안에서 확인할 수 있습니다.*

---

## 🏛️ 아키텍처 & 멘토단

각 랩에는 전문 AI 멘토가 학습 과정을 안내하는 **개념 검문소(Explanation Gate)**가 포함되어 있습니다. 각 단계의 멘토는 해당 페이즈의 심리적 및 페다고지적(교육학적) 요구에 맞춰 설계된 고유한 페르소나를 가지고 있습니다:

| 단계 | 멘토 | 성격 | 가르치는 내용 |
|-------|--------|-------------|------------------|
| **1** | 안전한 가이드 | 따뜻하고 인내심 있음, 친근한 형/누나 같은 존재 | 안전한 구문 탐색, '느낌적 코딩(vibe coding)' 타파 |
| **2** | 분석적인 파트너 | 호기심 많고 커피로 움직이는 '로그 탐정' | 에러 트레이스(error traces) 읽기, 시스템 다운 원인 파악 |
| **3** | 논리적 비계 설정자 | 체계적이며 격려를 아끼지 않는 '시니어 빌더' | 데이터 흐름 시각화 (입력 → 변환 → 출력) |
| **4** | 우아한 비평가 | 냉소적이고 순수주의적인 '엄격한 사랑(tough love)' | 이디엄에 맞는(idiomatic) 코드, 함수형 패턴, 나쁜 습관 교정 |
| **5** | 전략적 파트너 | 선견지명이 있고 프로페셔널한 '시스템 아키텍트' | 예외 케이스(edge cases), 결함 허용성(fault tolerance), 비즈니스 로직 정렬 |

*본 저장소는 **단계 1 (안전한 가이드)** 페르소나를 포함하고 있습니다.*

---

## 🔗 유용한 링크

[Coding5s.com](https://coding5s.com) | [Udemy (Coding5s Premium)](https://www.udemy.com/user/wilbarrios/) | [GitHub](https://github.com/WilfredoBarrios)

---

## 🤝 기여하기 (Contributions)

피드백이나 제안하고 싶은 기능이 있으신가요? 프로젝트를 지원하고 싶으시다면 언제든 Issue를 열거나 자유롭게 기여해 주세요!

---

## 📄 라이선스

MIT © [Wil Barrios](https://github.com/WilfredoBarrios)

---
⚡ *Coding5s 시스템 — 기술적 마스터를 위해 설계된 학습 경험.*
