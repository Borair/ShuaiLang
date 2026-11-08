# ShuaiLang

ShuaiLang is an experimental event-driven programming language with `.sl` source files, Medic-inspired sections, and `@` directives.

## Current implementation

The v3.1 interpreter, bytecode compiler, static analysis, language server, tests, and examples have been developed locally. **The complete source code has not yet been uploaded to this repository.**

## Local development

With the ShuaiLang v3.1 source package extracted:

```sh
python3 -m unittest discover -s tests -q
python3 shuailang.py run examples/control_flow.sl
```

## Status

Experimental. Do not use for untrusted programs or production workloads.
