# ores-otel-log-erlang-test

Exact-head conformance harness for **erlang**.

This repository tests both `ores-otel/ores.otel.log` and `ORESoftware/next-loggers.ts` using explicit commit SHAs.
The required native command is recorded in `conformance.json`: `rebar3 as test do compile, eunit`.
