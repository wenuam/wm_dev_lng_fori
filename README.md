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
	<n ? n < 2
	<Fib(n - 2) + Fib(n - 1)

Fib(777)
```
Output :
```
1081213530912648191985419587942084110095342850438593857649766278346130479286685742885693301250359913460718567974798268702550329302771992851392180275594318434818082
```

[Big numbers][apa] built-in.

[apa]: https://en.wikipedia.org/wiki/Arbitrary-precision_arithmetic

```fori
Fib("777")
```
Output :
```
1081213530912648191985419587942084110095342850438593857649766278346130479286685742885693301250359913460718567974798268702550329302771992851392180275594318434818082
```

Automatic type detection and conversion, if possible. Otherwise...

```fori
Fib("toto")
```
Output :
```
:Can't compare alpha to number in 'Fib(n):1:"<n="toto" ? n="toto" < 2"'
```

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

FORI is **NOT** a General-purpose Programming Language, even though it can.

It is a [Domain Specific Language][dsl] taylored for [data analysis][da] and mangling.

[dsl]: https://en.wikipedia.org/wiki/Domain-specific_language
[da]: https://en.wikipedia.org/wiki/Data_analysis

## Features

- Ultra-compact stand-alone multi-platform interpreter
- Optimized [byte-code][bc] interpreter and native [op-code][oc] emitter
- Soft real-time capabilities and hierarchic dependencies solver

[bc]: https://en.wikipedia.org/wiki/Bytecode
[oc]: https://en.wikipedia.org/wiki/Opcode

## Inspirations

* Primary

[Erlang][erl]: [actor model][am], [lightweight threading][lwp], [message passing][ipc], node distribution.

[erl]: https://www.erlang.org/
[erl]: https://github.com/erlang/otp
[lwp]: https://en.wikipedia.org/wiki/Light-weight_process
[ipc]: https://en.wikipedia.org/wiki/Message_passing


[Picat][pi]: [satisfaction solver][csp], syntax, librairies, stand-alone.

[pi]: https://picat-lang.org/
[csp]: https://en.wikipedia.org/wiki/Constraint_satisfaction_problem


[Factor][factor]: [concatenative programming][cp], syntax, libraries, interfaces, [tutorial].

[factor]: https://factorcode.org/
[factor]: https://github.com/factor/factor
[cp]: https://en.wikipedia.org/wiki/Concatenative_programming_language
[tutorial]: https://github.com/andreaferretti/factor-tutorial


[Fire][fire]: [reactive programming][rp], streams, data processing.

[fire]: https://github.com/jweinst1/Fire


[Wind][wind]: [flow-based programming][fbp], filters.

[wind]: https://github.com/jweinst1/Wind
[fbp]: https://en.wikipedia.org/wiki/Flow-based_programming


* Secondary

[Jupyter notebook][ipynb]: [reactive programming][rp] with scientific oriented languages ([Julia][jl] - [Python][py] - [R][r]).

[ipynb]: https://jupyter.org/
[ipynb]: https://github.com/jupyter/notebook
[jl]: https://julialang.org/
[py]: https://www.python.org/
[r]: https://www.r-project.org/


[Jancy][jnc]: [reactive programming][rp], low-level capabilities, interfaces.

[jnc]: http://jancy.org/
[jnc]: https://github.com/vovkos/jancy
[rp]: https://en.wikipedia.org/wiki/Reactive_programming


[Pony][pony]: [actor model][am], [object-oriented][oop], high performance.

[pony]: https://www.ponylang.io/
[pony]: https://github.com/ponylang/ponyc
[oop]: https://en.wikipedia.org/wiki/Object-oriented_programming


[Zig][zig]: multi-paradigm programming language, imperative and functional.

[zig]: https://ziglang.org/
[zig]: https://github.com/ziglang/zig


[Nim][nim]: multi-paradigm programming language, statically-typed.

[nim]: https://nim-lang.org/
[nim]: https://github.com/nim-lang/Nim


[Umka][um]: statically-typed, garbage collection.

[um]: https://github.com/vtereshkov/umka-lang


[Lily][lily]: statically-typed, reference counting garbage collection.

[lily]: https://lily-lang.org/
[lily]: https://github.com/FascinatedBox/lily


[Yona][yona]: dynamically-typed, functional style.

[yona]: https://yona-lang.org/
[yona]: https://github.com/yona-lang/yona/


[Huginn][hgn]: interpreted, object oriented, functional style.

[hgn]: https://huginn.org/
[hgn]: https://github.com/AmokHuginnsson/huginn


[Wind PL][w]: type system, low-level capabilities, interfaces.

[w]: https://doc.wind-lang.me/
[w]: https://github.com/wind-language/wind


[Adorad][ad]: interpreted, object oriented, functional style.

[ad]: https://github.com/adorad/adorad


[Lemon][lm]: dynamically-typed, embeddable.

[lm]: http://www.lemon-lang.org/
[lm]: https://github.com/lemon-lang/lemon


[Cold][cold]: constraint-based, interpreter.

[cold]: https://github.com/briansteffens/cold


## License

WM licensing model
