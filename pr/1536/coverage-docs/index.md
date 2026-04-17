# RustDoc Coverage Report

**conjure-cp:** 0% with examples, 25% documented -- 0/1/4
**conjure-cp-cli:** 0% with examples, 35% documented -- 0/47/135
**conjure-cp-core:** 4% with examples, 50% documented -- 23/312/628
**conjure-cp-enum-compatibility-macro:** 33% with examples, 100% documented -- 1/3/3
**conjure-cp-essence-macros:** 67% with examples, 67% documented -- 2/2/3
**conjure-cp-essence-parser:** 0% with examples, 17% documented -- 0/26/156
**conjure-cp-lsp:** 0% with examples, 0% documented -- 0/0/28
**conjure-cp-rule-macros:** 33% with examples, 67% documented -- 1/2/3
**conjure-cp-rules:** 0% with examples, 100% documented -- 0/1/1
**minion-sys:** 2% with examples, 27% documented -- 2/33/121
**tree-morph:** 7% with examples, 100% documented -- 7/95/95
**tree-morph-macros:** 50% with examples, 50% documented -- 1/1/2
**tree-sitter-essence:** 33% with examples, 100% documented -- 1/3/3

PR: [#1536](https://github.com/conjure-cp/conjure-oxide/pull/1536)
Commit: [5cc32042bb56eb71ab6a71639757800b0d7dfe85](https://github.com/conjure-cp/conjure-oxide/commit/5cc32042bb56eb71ab6a71639757800b0d7dfe85)

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
| crates/conjure-cp-cli/src/utils/conjure.rs | ❌ 0% *(0/4)* | ❌ 0% *(0/4)* |
| crates/conjure-cp-cli/src/utils/misc.rs | ❌ 0% *(0/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-cli/src/utils/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-cli/src/main.rs | ❌ 9% *(1/11)* | ❌ 0% *(0/11)* |
| crates/conjure-cp-cli/src/pretty.rs | ❌ 20% *(1/5)* | ❌ 0% *(0/5)* |
| crates/conjure-cp-cli/src/utils/testing.rs | ❌ 31% *(4/13)* | ❌ 0% *(0/13)* |
| crates/conjure-cp-cli/src/solve.rs | ❌ 40% *(8/20)* | ❌ 0% *(0/20)* |
| crates/conjure-cp-cli/src/test_solve.rs | ❌ 40% *(2/5)* | ❌ 0% *(0/5)* |
| crates/conjure-cp-cli/src/find_conjure.rs | ❌ 50% *(1/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-cli/src/cli.rs | ❌ 55% *(26/47)* | ❌ 0% *(0/47)* |
| crates/conjure-cp-cli/src/utils/json.rs | ❌ 67% *(2/3)* | ❌ 0% *(0/3)* |
| crates/conjure-cp-cli/src/print_info_schema.rs | ✅ 100% *(2/2)* | ❌ 0% *(0/2)* |

## RustDoc coverage for `conjure-cp-core`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/conjure-cp-core/src/ast/cnf_clause.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/ast/domains/attrs.rs | ❌ 0% *(0/17)* | ❌ 0% *(0/17)* |
| crates/conjure-cp-core/src/ast/domains/range.rs | ❌ 0% *(0/6)* | ❌ 0% *(0/6)* |
| crates/conjure-cp-core/src/ast/metadata.rs | ❌ 0% *(0/4)* | ❌ 0% *(0/4)* |
| crates/conjure-cp-core/src/ast/partial_eval.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/ast/records.rs | ❌ 0% *(0/4)* | ❌ 0% *(0/4)* |
| crates/conjure-cp-core/src/ast/sat_encoding.rs | ❌ 0% *(0/4)* | ❌ 0% *(0/4)* |
| crates/conjure-cp-core/src/context.rs | ❌ 0% *(0/12)* | ❌ 0% *(0/12)* |
| crates/conjure-cp-core/src/parse/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/parse/parse_model.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/solver/adaptors/minion/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/solver/adaptors/rustsat/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/solver/adaptors/smt/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/stats/mod.rs | ❌ 0% *(0/7)* | ❌ 0% *(0/7)* |
| crates/conjure-cp-core/src/settings.rs | ❌ 4% *(2/54)* | ❌ 0% *(0/54)* |
| crates/conjure-cp-core/src/ast/eval.rs | ❌ 9% *(1/11)* | ❌ 0% *(0/11)* |
| crates/conjure-cp-core/src/error.rs | ❌ 11% *(1/9)* | ❌ 0% *(0/9)* |
| crates/conjure-cp-core/src/ast/domains/error.rs | ❌ 17% *(1/6)* | ❌ 0% *(0/6)* |
| crates/conjure-cp-core/src/ast/types.rs | ❌ 17% *(2/12)* | ❌ 0% *(0/12)* |
| crates/conjure-cp-core/src/ast/literals.rs | ❌ 18% *(2/11)* | ❌ 0% *(0/11)* |
| crates/conjure-cp-core/src/stats/rewriter_stats.rs | ❌ 20% *(1/5)* | ❌ 0% *(0/5)* |
| crates/conjure-cp-core/src/ast/abstract_comprehension.rs | ❌ 21% *(7/34)* | ❌ 0% *(0/34)* |
| crates/conjure-cp-core/src/ast/comprehension.rs | ❌ 32% *(9/28)* | ❌ 0% *(0/28)* |
| crates/conjure-cp-core/src/ast/atom.rs | ❌ 33% *(1/3)* | ❌ 0% *(0/3)* |
| crates/conjure-cp-core/src/rule_engine/rule.rs | ❌ 33% *(5/15)* | ❌ 7% *(1/15)* |
| crates/conjure-cp-core/src/solver/mod.rs | ❌ 36% *(15/42)* | ❌ 0% *(0/42)* |
| crates/conjure-cp-core/src/ast/domains/unresolved.rs | ❌ 38% *(6/16)* | ❌ 0% *(0/16)* |
| crates/conjure-cp-core/src/stats/solver_stats.rs | ❌ 44% *(4/9)* | ❌ 0% *(0/9)* |
| crates/conjure-cp-core/src/ast/ac_operators.rs | ❌ 50% *(5/10)* | ❌ 10% *(1/10)* |
| crates/conjure-cp-core/src/ast/model.rs | ❌ 50% *(3/6)* | ❌ 0% *(0/6)* |
| crates/conjure-cp-core/src/ast/reference.rs | ❌ 50% *(1/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/ast/symbol_table.rs | ❌ 50% *(1/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/ast/variables.rs | ❌ 50% *(1/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/instantiate.rs | ❌ 50% *(1/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/rule_engine/rewriter_common.rs | ❌ 50% *(1/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/rule_engine/resolve_rules.rs | ❌ 57% *(4/7)* | ❌ 0% *(0/7)* |
| crates/conjure-cp-core/src/solver/states.rs | ❌ 64% *(7/11)* | ❌ 0% *(0/11)* |
| crates/conjure-cp-core/src/ast/domains/domain.rs | ❌ 67% *(4/6)* | ❌ 0% *(0/6)* |
| crates/conjure-cp-core/src/ast/domains/ground.rs | ❌ 69% *(9/13)* | ❌ 0% *(0/13)* |
| crates/conjure-cp-core/src/solver/model_modifier.rs | ❌ 70% *(7/10)* | ❌ 0% *(0/10)* |
| crates/conjure-cp-core/src/lib.rs | ❌ 75% *(3/4)* | ❌ 50% *(2/4)* |
| crates/conjure-cp-core/src/rule_engine/mod.rs | ❌ 75% *(6/8)* | ❌ 63% *(5/8)* |
| crates/conjure-cp-core/src/solver/adaptors/smt/theories.rs | ❌ 75% *(9/12)* | ❌ 0% *(0/12)* |
| crates/conjure-cp-core/src/ast/declaration.rs | ❌ 77% *(34/44)* | ❌ 27% *(12/44)* |
| crates/conjure-cp-core/src/ast/mod.rs | ❌ 80% *(4/5)* | ❌ 0% *(0/5)* |
| crates/conjure-cp-core/src/representation.rs | ❌ 83% *(10/12)* | ❌ 0% *(0/12)* |
| crates/conjure-cp-core/src/ast/categories.rs | ❌ 89% *(8/9)* | ❌ 0% *(0/9)* |
| crates/conjure-cp-core/src/ast/matrix.rs | ✅ 91% *(10/11)* | ❌ 9% *(1/11)* |
| crates/conjure-cp-core/src/ast/serde.rs | ✅ 91% *(10/11)* | ❌ 0% *(0/11)* |
| crates/conjure-cp-core/src/ast/expressions.rs | ✅ 93% *(84/90)* | ❌ 0% *(0/90)* |
| crates/conjure-cp-core/src/ast/assertions.rs | ✅ 100% *(4/4)* | ❌ 0% *(0/4)* |
| crates/conjure-cp-core/src/ast/moo.rs | ✅ 100% *(1/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/ast/name.rs | ✅ 100% *(6/6)* | ❌ 0% *(0/6)* |
| crates/conjure-cp-core/src/ast/pretty.rs | ✅ 100% *(8/8)* | ❌ 0% *(0/8)* |
| crates/conjure-cp-core/src/bug.rs | ✅ 100% *(1/1)* | ✅ 100% *(1/1)* |
| crates/conjure-cp-core/src/parse/example_models.rs | ✅ 100% *(2/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/rule_engine/rewrite_morph.rs | ✅ 100% *(1/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/rule_engine/rewrite_naive.rs | ✅ 100% *(1/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/rule_engine/rule_set.rs | ✅ 100% *(2/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/solver/adaptors/minion/adaptor.rs | ✅ 100% *(2/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/solver/adaptors/mod.rs | ✅ 100% *(1/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-core/src/solver/adaptors/rustsat/adaptor.rs | ✅ 100% *(2/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-core/src/solver/adaptors/smt/adaptor.rs | ✅ 100% *(2/2)* | ❌ 0% *(0/2)* |

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
| crates/conjure-cp-essence-parser/src/diagnostics/diagnostics_api.rs | ❌ 0% *(0/34)* | ❌ 0% *(0/34)* |
| crates/conjure-cp-essence-parser/src/diagnostics/error_detection/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-essence-parser/src/diagnostics/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-essence-parser/src/diagnostics/source_map.rs | ❌ 0% *(0/20)* | ❌ 0% *(0/20)* |
| crates/conjure-cp-essence-parser/src/lib.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-essence-parser/src/parser/expression.rs | ❌ 0% *(0/4)* | ❌ 0% *(0/4)* |
| crates/conjure-cp-essence-parser/src/parser/find.rs | ❌ 0% *(0/4)* | ❌ 0% *(0/4)* |
| crates/conjure-cp-essence-parser/src/parser/keyword_checks.rs | ❌ 0% *(0/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-essence-parser/src/parser/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-essence-parser/src/parser/parse_exprs.rs | ❌ 0% *(0/3)* | ❌ 0% *(0/3)* |
| crates/conjure-cp-essence-parser/src/parser/parse_literal.rs | ❌ 0% *(0/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-essence-parser/src/parser_legacy.rs | ❌ 0% *(0/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-essence-parser/src/parser/parse_model.rs | ❌ 20% *(1/5)* | ❌ 0% *(0/5)* |
| crates/conjure-cp-essence-parser/src/errors.rs | ❌ 22% *(6/27)* | ❌ 0% *(0/27)* |
| crates/conjure-cp-essence-parser/src/diagnostics/error_detection/collect_errors.rs | ❌ 25% *(1/4)* | ❌ 0% *(0/4)* |
| crates/conjure-cp-essence-parser/src/parser/domain.rs | ❌ 33% *(1/3)* | ❌ 0% *(0/3)* |
| crates/conjure-cp-essence-parser/src/parser/syntax_errors.rs | ❌ 33% *(1/3)* | ❌ 0% *(0/3)* |
| crates/conjure-cp-essence-parser/src/parser/traversal.rs | ❌ 33% *(2/6)* | ❌ 0% *(0/6)* |
| crates/conjure-cp-essence-parser/src/parser/util.rs | ❌ 36% *(10/28)* | ❌ 0% *(0/28)* |
| crates/conjure-cp-essence-parser/src/parser/letting.rs | ❌ 50% *(1/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-essence-parser/src/parser/macros.rs | ✅ 100% *(3/3)* | ❌ 0% *(0/3)* |

## RustDoc coverage for `conjure-cp-lsp`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/conjure-cp-lsp/src/handlers/cache.rs | ❌ 0% *(0/9)* | ❌ 0% *(0/9)* |
| crates/conjure-cp-lsp/src/handlers/hovering.rs | ❌ 0% *(0/2)* | ❌ 0% *(0/2)* |
| crates/conjure-cp-lsp/src/handlers/mod.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-lsp/src/handlers/sync_event.rs | ❌ 0% *(0/9)* | ❌ 0% *(0/9)* |
| crates/conjure-cp-lsp/src/lib.rs | ❌ 0% *(0/1)* | ❌ 0% *(0/1)* |
| crates/conjure-cp-lsp/src/server.rs | ❌ 0% *(0/6)* | ❌ 0% *(0/6)* |

## RustDoc coverage for `conjure-cp-rule-macros`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/conjure-cp-rule-macros/src/lib.rs | ❌ 67% *(2/3)* | ❌ 33% *(1/3)* |

## RustDoc coverage for `conjure-cp-rules`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/conjure-cp-rules/src/lib.rs | ✅ 100% *(1/1)* | ❌ 0% *(0/1)* |

## RustDoc coverage for `minion-sys`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/minion-sys/src/ast.rs | ❌ 13% *(13/101)* | ❌ 0% *(0/101)* |
| crates/minion-sys/src/error.rs | ✅ 100% *(10/10)* | ❌ 0% *(0/10)* |
| crates/minion-sys/src/lib.rs | ✅ 100% *(1/1)* | ✅ 100% *(1/1)* |
| crates/minion-sys/src/print.rs | ✅ 100% *(6/6)* | ❌ 0% *(0/6)* |
| crates/minion-sys/src/run.rs | ✅ 100% *(3/3)* | ❌ 33% *(1/3)* |

## RustDoc coverage for `tree-morph`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/tree-morph/src/cache.rs | ✅ 100% *(31/31)* | ❌ 0% *(0/31)* |
| crates/tree-morph/src/commands.rs | ✅ 100% *(5/5)* | ❌ 20% *(1/5)* |
| crates/tree-morph/src/engine.rs | ✅ 100% *(4/4)* | ❌ 25% *(1/4)* |
| crates/tree-morph/src/engine_builder.rs | ✅ 100% *(24/24)* | ❌ 0% *(0/24)* |
| crates/tree-morph/src/engine_zipper.rs | ✅ 100% *(1/1)* | ❌ 0% *(0/1)* |
| crates/tree-morph/src/helpers.rs | ✅ 100% *(7/7)* | ❌ 0% *(0/7)* |
| crates/tree-morph/src/lib.rs | ✅ 100% *(2/2)* | ❌ 50% *(1/2)* |
| crates/tree-morph/src/rule.rs | ✅ 100% *(20/20)* | ❌ 20% *(4/20)* |
| crates/tree-morph/src/update.rs | ✅ 100% *(1/1)* | ❌ 0% *(0/1)* |

## RustDoc coverage for `tree-morph-macros`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/tree-morph-macros/src/lib.rs | ❌ 50% *(1/2)* | ❌ 50% *(1/2)* |

## RustDoc coverage for `tree-sitter-essence`

| File | Percentage Documented | Percentage with examples |
|----|----|----|
| crates/tree-sitter-essence/bindings/rust/lib.rs | ✅ 100% *(3/3)* | ❌ 33% *(1/3)* |

