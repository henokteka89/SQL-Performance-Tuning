# SQL-Performance-Tuning

SQL Server query and server tuning scripts, notes and study material, consolidated from separate repositories. Each folder is one former repo, with its full commit history preserved.

## Tuning notes and study material
| Folder | What it covers |
|---|---|
| [performance-tuning-notes](performance-tuning-notes) | Tuning notes: index usage checks, regressions |
| [Performance-Tuning](Performance-Tuning) | Fragmentation and unused indexes, expensive queries by CPU, high compile time queries |
| [performancetuning-adam-mechanics-5-culprits-95-problem](performancetuning-adam-mechanics-5-culprits-95-problem) | "5 culprits cause 95% of performance problems" (document) |
| [PerfTuning](PerfTuning) | Query plans and expensive queries (OneNote) |
| [10-Query-tuning-tips](10-Query-tuning-tips) | Query optimization techniques (PDF) |
| [MS-study-design-and-performance-evaluation-SQL-server](MS-study-design-and-performance-evaluation-SQL-server) | Design (normalization, data types, indexes, columnstore) and evaluating performance improvements |
| [automatic-tuning-and-memory-optimized-tempdb](automatic-tuning-and-memory-optimized-tempdb) | Automatic tuning, intelligent query processing, memory-optimized tempdb |
| [SQLPerformance](SQLPerformance) | Scalar UDF inlining |

## Plan cache and expensive queries
| Folder | What it covers |
|---|---|
| [query-hash-plan-hash-Plan-handle-No-query-store-](query-hash-plan-hash-Plan-handle-No-query-store-) | Query hash, plan hash and plan handle without Query Store |
| [Query-detail-based-on-plan-handle](Query-detail-based-on-plan-handle) | Query details from a plan handle |
| [top5-queries-with-high-IO](top5-queries-with-high-IO) | Top 5 queries by I/O |
| [Implicit-conversion-find-all-queries-with-implicit-conversion](Implicit-conversion-find-all-queries-with-implicit-conversion) | Find queries with implicit conversions |
| [Turn-On-Optimize-for-Ad-Hoc-Workloads-](Turn-On-Optimize-for-Ad-Hoc-Workloads-) | Optimize for ad hoc workloads |
| [Powershell-parse-xml-statistics-IO-time-output](Powershell-parse-xml-statistics-IO-time-output) | Parse STATISTICS IO/TIME output with PowerShell |

## Parameters
| Folder | What it covers |
|---|---|
| [Capture-parameter-values-of-stored-proc](Capture-parameter-values-of-stored-proc) | Capture stored procedure parameter values (Extended Events), as a managed procedure |
| [capture-parameter-values](capture-parameter-values) | Capture parameter values |
| [showparametervaluefromxml](showparametervaluefromxml) | Show compiled parameter values from plan XML |

## tempdb
| Folder | What it covers |
|---|---|
| [tempdb-contention-tips-to-reduce-it](tempdb-contention-tips-to-reduce-it) | Reducing tempdb contention |
| [tempdb-metadata-contention](tempdb-metadata-contention) | tempdb metadata contention and fixes |
| [Tempdb-usage-per-session-_-whatisfilling-tempdb](Tempdb-usage-per-session-_-whatisfilling-tempdb) | tempdb usage per session: what is filling tempdb |
| [load-block-tempdb-pro](load-block-tempdb-pro) | sp_whopro with tempdb and load test procedures |

## Engine features
| Folder | What it covers |
|---|---|
| [batchmode-erik](batchmode-erik) | Batch mode (Erik Darling) |
| [In-Memory-OLTP-Memory-Optimized-table](In-Memory-OLTP-Memory-Optimized-table) | In-Memory OLTP and memory-optimized tables |

## Stress testing
| Folder | What it covers |
|---|---|
| [Sqlstresstest-with-powershell](Sqlstresstest-with-powershell) | SQL stress test with PowerShell |
| [WHOPRO-AND-SQL-STRESS-TEST](WHOPRO-AND-SQL-STRESS-TEST) | sp_whopro and SQL stress testing |
