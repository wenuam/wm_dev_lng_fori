# wm_dev_lng_fori

FORI = Functional Oriented Reactive Interpreter

IROF = Interpreteur Réactif Orienté Fonctionnel

* Home

https://github.com/wenuam/wm_dev_lng_fori

## Look

Here's what some code look like :

- Hello World
```fori
"Hello World!"
"\x1b[1;31mHello \x1b[2;37;41mWorld!"
```
Output :
```
Hello World!
\x1b[1;31mHello \x1b[2;37;41mWorld!
```

No automatic [ANSI Escape Sequences][ansi] interpretation.

	[ansi]: https://en.wikipedia.org/wiki/ANSI_escape_code

- Fibonacci sequence
```fori
Fib(n) =
	n : n < 2
	Fib(n - 2) + Fib(n - 1)

Fib(777)
```
Output :
```
1081213530912648191985419587942084110095342850438593857649766278346130479286685742885693301250359913460718567974798268702550329302771992851392180275594318434818082
```

[Big numbers][apa] built-in.

	[apa]: https://en.wikipedia.org/wiki/Arbitrary-precision_arithmetic

## What

FORI is a [scripting programming language][sl] for fast [iterative development][id].

It focuses on data wrangling using [Actor Model][am] and [Entity Component System][ecs].

The syntax is minimized to the strict essential, yet [meta-programming][mp] capable.

Large system library and [Foreign Function Interface][ffi] with native compiled modules.

	[sl]: https://en.wikipedia.org/wiki/Scripting_language
	[id]: https://en.wikipedia.org/wiki/Iterative_and_incremental_development
	[am]: https://en.wikipedia.org/wiki/Actor_model
	[ecs]: https://en.wikipedia.org/wiki/Entity_component_system
	[mp]: https://en.wikipedia.org/wiki/Metaprogramming
	[ffi]: https://en.wikipedia.org/wiki/Foreign_function_interface

## Why

FORI is **NOT** a General-purpose Programming Language.

It is a [Domain Specific Language][dsl] taylored for [data analysis][da] and mangling.

	[dsl]: https://en.wikipedia.org/wiki/Domain-specific_language
	[da]: https://en.wikipedia.org/wiki/Data_analysis

## Features

- Ultra-compact stand-alone multi-platform interpreter
- Optimized [byte-code][bc] interpreter and native op-code emitter
- Soft real-time capabilites and hierarchic dependencies solver

	[bc]: https://en.wikipedia.org/wiki/Bytecode

## Inspirations

[Jupyter][ipynb]: reactive programming with scientific oriented languages ([Julia][jl] - [Python][py] - [R][r]).

	[ipynb]: https://jupyter.org/
	[jl]: https://julialang.org/
	[py]: https://www.python.org/
	[r]: https://www.r-project.org/

[Erlang][erl]: [actor model][am], [lightweight threading][lwp], [message passing][ipc], node distribution.

	[erl]: https://www.erlang.org/
	[lwp]: https://en.wikipedia.org/wiki/Light-weight_process
	[ipc]: https://en.wikipedia.org/wiki/Message_passing

[Factor][factor]: [concatenative programming][cp], syntax, libraries, interfaces.

	[factor]: https://factorcode.org/
	[cp]: https://en.wikipedia.org/wiki/Concatenative_programming_language

[Jancy][jnc]: [reactive programming][rp], low-level capabilities, interfaces.

	[jnc]: https://github.com/vovkos/jancy
	[rp]: https://en.wikipedia.org/wiki/Reactive_programming

[Picat][pi]: [satisfaction solver][csp], syntax, librairies, stand-alone.

	[pi]: https://picat-lang.org/
	[csp]: https://en.wikipedia.org/wiki/Constraint_satisfaction_problem

[Fire][fire]: [reactive programming][rp], streams, data processing.

	[fire]: https://github.com/jweinst1/Fire

[Wind][wind]: [flow-based programming][fbp], filters.

	[wind]: https://github.com/jweinst1/Wind
	[fbp]: https://en.wikipedia.org/wiki/Flow-based_programming

[Wind][wi]: type system, low-level capabilities, interfaces.

	[wi]: https://doc.wind-lang.me/

## License

WM licensing model
