# RustDoc Coverage Report

**conjure-cp:** 0% with examples, 25% documented -- 0/1/4
**conjure-cp-cli:** 0% with examples, 42% documented -- 0/81/194
**conjure-cp-cli-fuzz:** 0% with examples, 0% documented -- 0/0/1
**conjure-cp-core:** 2% with examples, 50% documented -- 22/472/942
**conjure-cp-enum-compatibility-macro:** 33% with examples, 100% documented -- 1/3/3
**conjure-cp-essence-macros:** 67% with examples, 67% documented -- 2/2/3
**conjure-cp-essence-parser:** 0% with examples, 16% documented -- 0/30/193
**conjure-cp-lsp:** 0% with examples, 0% documented -- 0/0/29
**conjure-cp-rule-macros:** 25% with examples, 50% documented -- 1/2/4
**conjure-cp-rules:** 3% with examples, 9% documented -- 1/3/35
**minion-sys:** 1% with examples, 32% documented -- 2/50/158
**tree-sitter-essence:** 33% with examples, 100% documented -- 1/3/3

PR: [#1945](https://github.com/conjure-cp/conjure-oxide/pull/1945)
Commit: [8fd1d50de56e9d073acaa0a0e338748197199e2e](https://github.com/conjure-cp/conjure-oxide/commit/8fd1d50de56e9d073acaa0a0e338748197199e2e)

## RustDoc coverage for `conjure-cp`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/conjure-cp/src/defaults.rs | ❌ 0% *(0/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp/src/lib.rs | ❌ 50% *(1/2)* | ❌ 0% *(0/2)* |

## RustDoc coverage for `conjure-cp-cli`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/conjure-cp-cli/src/lib.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-cli/src/rule_trace_aggregates.rs | ❌ 0% *(0/19)* | ❌ 0% *(0/19)* |
| crates/conjure-cp-cli/src/utils/misc.rs | ❌ 0% *(0/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-cli/src/utils/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-cli/src/main.rs | ❌ 8% *(1/12)* | ❌ 0% *(0/12)* |
| crates/conjure-cp-cli/src/utils/conjure.rs | ❌ 17% *(3/18)* | ❌ 0% *(0/18)* |
| crates/conjure-cp-cli/src/pretty.rs | ❌ 20% *(1/5)* | ❌ 0% *(0/5)* |
| crates/conjure-cp-cli/src/utils/testing.rs | ❌ 33% *(5/15)* | ❌ 0% *(0/15)* |
| crates/conjure-cp-cli/src/test_solve.rs | ❌ 40% *(2/5)* | ❌ 0% *(0/5)* |
| crates/conjure-cp-cli/src/find_conjure.rs | ❌ 50% *(1/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-cli/src/solve.rs | ❌ 50% *(15/30)* | ❌ 0% *(0/30)* |
| crates/conjure-cp-cli/src/cli.rs | ❌ 52% *(33/63)* | ❌ 0% *(0/63)* |
| crates/conjure-cp-cli/src/utils/json.rs | ❌ 67% *(2/3)* | ❌ 0% *(0/3)* |
| crates/conjure-cp-cli/src/print_info_schema.rs | ✅ 100% *(2/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-cli/src/utils/simplified_json.rs | ✅ 100% *(16/16)* | ❌ 0% *(0/16)* |

## RustDoc coverage for `conjure-cp-cli-fuzz`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| fuzz/fuzz_targets/fuzz_detect_errors.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |

## RustDoc coverage for `conjure-cp-core`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/conjure-cp-core/src/ast/cnf_clause.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/ast/domains/range.rs | ❌ 0% *(0/6)* | ❌ 0% *(0/6)* |
| crates/conjure-cp-core/src/ast/sat_encoding.rs | ❌ 0% *(0/4)* | ❌ 0% *(0/4)* |
| crates/conjure-cp-core/src/context.rs | ❌ 0% *(0/12)* | ❌ 0% *(0/12)* |
| crates/conjure-cp-core/src/parse/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/parse/parse_model.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/representation/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/representation/store.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/representation/util.rs | ❌ 0% *(0/3)* | ❌ 0% *(0/3)* |
| crates/conjure-cp-core/src/solver/adaptors/minion/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/solver/adaptors/rustsat/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/solver/adaptors/smt/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/stats/mod.rs | ❌ 0% *(0/7)* | ❌ 0% *(0/7)* |
| crates/conjure-cp-core/src/utils/bimap.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/utils/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/ast/domains/attrs.rs | ❌ 8% *(4/52)* | ❌ 0% *(0/52)* |
| crates/conjure-cp-core/src/representation/stored.rs | ❌ 10% *(2/20)* | ❌ 0% *(0/20)* |
| crates/conjure-cp-core/src/error.rs | ❌ 11% *(1/9)* | ❌ 0% *(0/9)* |
| crates/conjure-cp-core/src/utils/view.rs | ❌ 11% *(1/9)* | ❌ 0% *(0/9)* |
| crates/conjure-cp-core/src/ast/domains/error.rs | ❌ 13% *(1/8)* | ❌ 0% *(0/8)* |
| crates/conjure-cp-core/src/stats/rewriter_stats.rs | ❌ 17% *(1/6)* | ❌ 0% *(0/6)* |
| crates/conjure-cp-core/src/ast/types.rs | ❌ 18% *(3/17)* | ❌ 0% *(0/17)* |
| crates/conjure-cp-core/src/ast/literals.rs | ❌ 19% *(3/16)* | ❌ 0% *(0/16)* |
| crates/conjure-cp-core/src/ast/abstract_comprehension.rs | ❌ 21% *(7/34)* | ❌ 0% *(0/34)* |
| crates/conjure-cp-core/src/solver/adaptors/minion/adaptor.rs | ❌ 21% *(6/28)* | ❌ 0% *(0/28)* |
| crates/conjure-cp-core/src/settings.rs | ❌ 23% *(17/75)* | ❌ 0% *(0/75)* |
| crates/conjure-cp-core/src/ast/domains/int_val.rs | ❌ 25% *(1/4)* | ❌ 0% *(0/4)* |
| crates/conjure-cp-core/src/ast/records.rs | ❌ 25% *(1/4)* | ❌ 0% *(0/4)* |
| crates/conjure-cp-core/src/representation/types.rs | ❌ 27% *(10/37)* | ❌ 0% *(0/37)* |
| crates/conjure-cp-core/src/ast/atom.rs | ❌ 33% *(1/3)* | ❌ 0% *(0/3)* |
| crates/conjure-cp-core/src/ast/objective.rs | ❌ 33% *(2/6)* | ❌ 0% *(0/6)* |
| crates/conjure-cp-core/src/ast/reference.rs | ❌ 33% *(1/3)* | ❌ 0% *(0/3)* |
| crates/conjure-cp-core/src/representation/registry.rs | ❌ 33% *(2/6)* | ❌ 0% *(0/6)* |
| crates/conjure-cp-core/src/ast/comprehension.rs | ❌ 34% *(10/29)* | ❌ 0% *(0/29)* |
| crates/conjure-cp-core/src/solver/mod.rs | ❌ 35% *(15/43)* | ❌ 0% *(0/43)* |
| crates/conjure-cp-core/src/ast/eval.rs | ❌ 42% *(8/19)* | ❌ 0% *(0/19)* |
| crates/conjure-cp-core/src/ast/model.rs | ❌ 43% *(3/7)* | ❌ 0% *(0/7)* |
| crates/conjure-cp-core/src/bug.rs | ❌ 43% *(3/7)* | ❌ 14% *(1/7)* |
| crates/conjure-cp-core/src/stats/solver_stats.rs | ❌ 44% *(4/9)* | ❌ 0% *(0/9)* |
| crates/conjure-cp-core/src/ast/ac_operators.rs | ❌ 46% *(6/13)* | ❌ 8% *(1/13)* |
| crates/conjure-cp-core/src/ast/symbol_table.rs | ❌ 50% *(1/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/ast/variables.rs | ❌ 50% *(1/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/rule_engine/rewriter_common.rs | ❌ 50% *(1/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/rule_engine/rule.rs | ❌ 50% *(13/26)* | ❌ 4% *(1/26)* |
| crates/conjure-cp-core/src/utils/combinatorics.rs | ❌ 50% *(5/10)* | ❌ 0% *(0/10)* |
| crates/conjure-cp-core/src/representation/errors.rs | ❌ 56% *(18/32)* | ❌ 0% *(0/32)* |
| crates/conjure-cp-core/src/rule_engine/resolve_rules.rs | ❌ 57% *(4/7)* | ❌ 0% *(0/7)* |
| crates/conjure-cp-core/src/ast/domains/unresolved.rs | ❌ 64% *(9/14)* | ❌ 0% *(0/14)* |
| crates/conjure-cp-core/src/solver/states.rs | ❌ 64% *(7/11)* | ❌ 0% *(0/11)* |
| crates/conjure-cp-core/src/ast/partial_eval.rs | ❌ 67% *(2/3)* | ❌ 0% *(0/3)* |
| crates/conjure-cp-core/src/instantiate.rs | ❌ 67% *(2/3)* | ❌ 0% *(0/3)* |
| crates/conjure-cp-core/src/solver/model_modifier.rs | ❌ 70% *(7/10)* | ❌ 0% *(0/10)* |
| crates/conjure-cp-core/src/lib.rs | ❌ 75% *(3/4)* | ❌ 50% *(2/4)* |
| crates/conjure-cp-core/src/rule_engine/mod.rs | ❌ 75% *(6/8)* | ❌ 63% *(5/8)* |
| crates/conjure-cp-core/src/ast/declaration.rs | ❌ 80% *(41/51)* | ❌ 22% *(11/51)* |
| crates/conjure-cp-core/src/ast/mod.rs | ❌ 83% *(5/6)* | ❌ 0% *(0/6)* |
| crates/conjure-cp-core/src/representation/legacy.rs | ❌ 83% *(10/12)* | ❌ 0% *(0/12)* |
| crates/conjure-cp-core/src/ast/domains/domain.rs | ❌ 88% *(7/8)* | ❌ 0% *(0/8)* |
| crates/conjure-cp-core/src/ast/categories.rs | ❌ 89% *(8/9)* | ❌ 0% *(0/9)* |
| crates/conjure-cp-core/src/ast/serde.rs | ✅ 91% *(10/11)* | ❌ 0% *(0/11)* |
| crates/conjure-cp-core/src/ast/expressions.rs | ✅ 95% *(111/117)* | ❌ 0% *(0/117)* |
| crates/conjure-cp-core/src/ast/assertions.rs | ✅ 100% *(4/4)* | ❌ 0% *(0/4)* |
| crates/conjure-cp-core/src/ast/domains/ground.rs | ✅ 100% *(15/15)* | ❌ 0% *(0/15)* |
| crates/conjure-cp-core/src/ast/expression_arena.rs | ✅ 100% *(2/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/ast/matrix.rs | ✅ 100% *(22/22)* | ❌ 5% *(1/22)* |
| crates/conjure-cp-core/src/ast/metadata.rs | ✅ 100% *(5/5)* | ❌ 0% *(0/5)* |
| crates/conjure-cp-core/src/ast/moo.rs | ✅ 100% *(1/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/ast/name.rs | ✅ 100% *(6/6)* | ❌ 0% *(0/6)* |
| crates/conjure-cp-core/src/ast/pretty.rs | ✅ 100% *(12/12)* | ❌ 0% *(0/12)* |
| crates/conjure-cp-core/src/objective.rs | ✅ 100% *(2/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/parse/example_models.rs | ✅ 100% *(2/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/representation/default_impls.rs | ✅ 100% *(5/5)* | ❌ 0% *(0/5)* |
| crates/conjure-cp-core/src/rule_engine/rewrite.rs | ✅ 100% *(1/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/rule_engine/rule_set.rs | ✅ 100% *(2/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/solver/adaptors/mod.rs | ✅ 100% *(1/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/solver/adaptors/rustsat/adaptor.rs | ✅ 100% *(2/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/solver/adaptors/smt/adaptor.rs | ✅ 100% *(2/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/solver/adaptors/smt/theories.rs | ✅ 100% *(4/4)* | ❌ 0% *(0/4)* |

## RustDoc coverage for `conjure-cp-enum-compatibility-macro`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/conjure-cp-enum-compatibility-macro/src/lib.rs | ✅ 100% *(3/3)* | ❌ 33% *(1/3)* |

## RustDoc coverage for `conjure-cp-essence-macros`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/conjure-cp-essence-macros/src/lib.rs | ❌ 67% *(2/3)* | ❌ 67% *(2/3)* |

## RustDoc coverage for `conjure-cp-essence-parser`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/conjure-cp-essence-parser/src/diagnostics/diagnostics_api.rs | ❌ 0% *(0/37)* | ❌ 0% *(0/37)* |
| crates/conjure-cp-essence-parser/src/diagnostics/error_detection/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-essence-parser/src/diagnostics/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-essence-parser/src/diagnostics/semantic_tokens.rs | ❌ 0% *(0/18)* | ❌ 0% *(0/18)* |
| crates/conjure-cp-essence-parser/src/diagnostics/source_map.rs | ❌ 0% *(0/21)* | ❌ 0% *(0/21)* |
| crates/conjure-cp-essence-parser/src/lib.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-essence-parser/src/parser/expression.rs | ❌ 0% *(0/4)* | ❌ 0% *(0/4)* |
| crates/conjure-cp-essence-parser/src/parser/keyword_checks.rs | ❌ 0% *(0/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-essence-parser/src/parser/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-essence-parser/src/parser/parse_exprs.rs | ❌ 0% *(0/3)* | ❌ 0% *(0/3)* |
| crates/conjure-cp-essence-parser/src/parser/parse_literal.rs | ❌ 0% *(0/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-essence-parser/src/parser_legacy.rs | ❌ 0% *(0/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-essence-parser/src/parser/find.rs | ❌ 14% *(1/7)* | ❌ 0% *(0/7)* |
| crates/conjure-cp-essence-parser/src/parser/parse_model.rs | ❌ 20% *(1/5)* | ❌ 0% *(0/5)* |
| crates/conjure-cp-essence-parser/src/errors.rs | ❌ 22% *(6/27)* | ❌ 0% *(0/27)* |
| crates/conjure-cp-essence-parser/src/diagnostics/error_detection/collect_errors.rs | ❌ 25% *(1/4)* | ❌ 0% *(0/4)* |
| crates/conjure-cp-essence-parser/src/parser/util.rs | ❌ 31% *(12/39)* | ❌ 0% *(0/39)* |
| crates/conjure-cp-essence-parser/src/parser/domain.rs | ❌ 33% *(1/3)* | ❌ 0% *(0/3)* |
| crates/conjure-cp-essence-parser/src/parser/traversal.rs | ❌ 33% *(2/6)* | ❌ 0% *(0/6)* |
| crates/conjure-cp-essence-parser/src/parser/letting.rs | ❌ 50% *(1/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-essence-parser/src/parser/syntax_errors.rs | ❌ 50% *(2/4)* | ❌ 0% *(0/4)* |
| crates/conjure-cp-essence-parser/src/parser/macros.rs | ✅ 100% *(3/3)* | ❌ 0% *(0/3)* |

## RustDoc coverage for `conjure-cp-lsp`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/conjure-cp-lsp/src/handlers/cache.rs | ❌ 0% *(0/9)* | ❌ 0% *(0/9)* |
| crates/conjure-cp-lsp/src/handlers/hovering.rs | ❌ 0% *(0/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-lsp/src/handlers/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-lsp/src/handlers/semantic_highlighting.rs | ❌ 0% *(0/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-lsp/src/handlers/sync_event.rs | ❌ 0% *(0/8)* | ❌ 0% *(0/8)* |
| crates/conjure-cp-lsp/src/lib.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-lsp/src/server.rs | ❌ 0% *(0/6)* | ❌ 0% *(0/6)* |

## RustDoc coverage for `conjure-cp-rule-macros`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/conjure-cp-rule-macros/src/lib.rs | ❌ 50% *(2/4)* | ❌ 25% *(1/4)* |

## RustDoc coverage for `conjure-cp-rules`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/conjure-cp-rules/src/types/function/as_relation/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/function/explicit/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/int/bv/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/int/direct/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/int/lia/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/int/log/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/int/order/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/matrix/array/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/matrix/components/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/matrix/packed/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/mset/counts/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/mset/occurrence/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/mset/packed/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/mset/repetition/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/partition/as_set/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/partition/occurrence/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/partition/packed/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/permutation/as_function/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/record/components/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/record/packed/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/relation/as_set/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/relation/occurrence/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/relation/packed/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/sequence/explicit/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/sequence/packed/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/set/explicit/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/set/occurrence/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/set/packed/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/tuple/components/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/tuple/packed/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/variant/components/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/types/variant/packed/representation.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-rules/src/lib.rs | ✅ 100% *(2/2)* | ❌ 50% *(1/2)* |
| crates/conjure-cp-rules/src/representation.rs | ✅ 100% *(1/1)* | ❌ 0% *(0/1)* |

## RustDoc coverage for `minion-sys`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/minion-sys/src/ast.rs | ❌ 13% *(14/105)* | ❌ 0% *(0/105)* |
| crates/minion-sys/src/run.rs | ❌ 48% *(16/33)* | ❌ 3% *(1/33)* |
| crates/minion-sys/src/error.rs | ✅ 100% *(13/13)* | ❌ 0% *(0/13)* |
| crates/minion-sys/src/lib.rs | ✅ 100% *(1/1)* | ✅ 100% *(1/1)* |
| crates/minion-sys/src/print.rs | ✅ 100% *(6/6)* | ❌ 0% *(0/6)* |

## RustDoc coverage for `tree-sitter-essence`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/tree-sitter-essence/bindings/rust/lib.rs | ✅ 100% *(3/3)* | ❌ 33% *(1/3)* |

