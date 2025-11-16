---

# Awesome C++

A collection of resources on contemporary C++.

---

## Books

### Beginner

Introductory, no previous programming experience

* [Programming: Principles and Practice Using C++ (Bjarne Stroustrup) (updated for C++11/C++14)](http://amzn.to/2qX9ssX) An introduction to programming using C++ by the creator of the language. A good read, that assumes no previous programming experience, but is not only for beginners.

Introductory, with previous programming experience

* [C++ Primer](http://amzn.to/2qhkshD) (Stanley Lippman, Josée Lajoie, and Barbara E. Moo) (updated for C++11) Coming at 1k pages, this is a very thorough introduction into C++ that covers just about everything in the language in a very accessible format and in great detail. The fifth edition (released August 16, 2012) covers C++11. [Review]
* [A Tour of C++](http://amzn.to/2qX1RsF) (Bjarne Stroustrup) (EBOOK) The “tour” is a quick (about 180 pages and 14 chapters) tutorial overview of all of standard C++ (language and standard library, and using C++11) at a moderately high level for people who already know C++ or at least are experienced programmers. This book is an extended version of the material that constitutes Chapters 2-5 of The C++ Programming Language, 4th edition.
* [Accelerated C++](http://amzn.to/2rRbg4T) (Andrew Koenig and Barbara Moo) This basically covers the same ground as the C++ Primer, but does so on a fourth of its space. This is largely because it does not attempt to be an introduction to programming, but an introduction to C++ for people who've previously programmed in some other language. It has a steeper learning curve, but, for those who can cope with this, it is a very compact introduction into the language. (Historically, it broke new ground by being the first beginner's book to use a modern approach at teaching the language.) [Review]
* [Thinking in C++ - Volume 1](http://amzn.to/2ri2qjD) [Volume 2](http://amzn.to/2rAJpZA) (Bruce Eckel) Two volumes; is a tutorial style free set of intro level books. Downloads: vol 1, vol 2. Unfortunately they’re marred by a number of trivial errors (e.g. maintaining that temporaries are automatically const), with no official errata list. A partial 3rd party errata list is available at (http://www.computersciencelab.com/Eckel.htm), but it’s apparently not maintained.  Not to be confused with C++ Primer Plus (Stephen Prata), with a significantly less favorable review.

### Best practices

* [Effective C++](http://amzn.to/2qX3mJh) (Scott Meyers) This was written with the aim of being the best second book C++ programmers should read, and it succeeded. Earlier editions were aimed at programmers coming from C, the third edition changes this and targets programmers coming from languages like Java. It presents ~50 easy-to-remember rules of thumb along with their rationale in a very accessible (and enjoyable) style. For C++11 and C++14 the examples and a few issues are outdated and Effective Modern C++ should be preferred. [Review]
* [Effective Modern C++](http://amzn.to/2qXjOZT) (Scott Meyers) This is basically the new version of Effective C++, aimed at C++ programmers making the transition from C++03 to C++11 and C++14.
* [Effective STL](http://amzn.to/2riactP) (Scott Meyers) This aims to do the same to the part of the standard library coming from the STL what Effective C++ did to the language as a whole: It presents rules of thumb along with their rationale. [Review]
* [C++20 - The Complete Guide](https://leanpub.com/cpp20) (Nicolai Josuttis) Comprehensive guide to all C++20 features including concepts, ranges, coroutines, modules, and more. Written by an experienced C++ trainer and book author.
* [C++ Best Practices](https://leanpub.com/cppbestpractices) (Jason Turner) A collection of best practices for modern C++ development, covering topics from compilation to testing and debugging.

### ### Intermediate

* [More Effective C++](http://amzn.to/2qXlrot) (Scott Meyers) Even more rules of thumb than Effective C++. Not as important as the ones in the first book, but still good to know.
* [Exceptional C++](http://amzn.to/2qXwiRh) (Herb Sutter) Presented as a set of puzzles, this has one of the best and thorough discussions of the proper resource management and exception safety in C++ through Resource Acquisition is Initialization (RAII) in addition to in-depth coverage of a variety of other topics including the pimpl idiom, name lookup, good class design, and the C++ memory model. [Review]
* [More Exceptional C++](http://amzn.to/2qQqubT) (Herb Sutter) Covers additional exception safety topics not covered in Exceptional C++, in addition to discussion of effective object oriented programming in C++ and correct use of the STL. [Review]
* [Exceptional C++ Style](http://amzn.to/2qQeJlE) (Herb Sutter) Discusses generic programming, optimization, and resource management; this book also has an excellent exposition of how to write modular code in C++ by using nonmember functions and the single responsibility principle. [Review]
* [C++ Coding Standards](http://amzn.to/2rATdTf) (Herb Sutter and Andrei Alexandrescu) “Coding standards” here doesn't mean “how many spaces should I indent my code?” This book contains 101 best practices, idioms, and common pitfalls that can help you to write correct, understandable, and efficient C++ code. [Review]
* [C++ Templates: The Complete Guide](http://amzn.to/2rVxEt2) (David Vandevoorde and Nicolai M. Josuttis) This is the book about templates as they existed before C++11. It covers everything from the very basics to some of the most advanced template metaprogramming and explains every detail of how templates work (both conceptually and at how they are implemented) and discusses many common pitfalls. Has excellent summaries of the One Definition Rule (ODR) and overload resolution in the appendices. A second edition is scheduled for 2017. [Review]

### Advanced

* [Modern C++ Design](http://amzn.to/2riaEbI) (Andrei Alexandrescu) A groundbreaking book on advanced generic programming techniques. Introduces policy-based design, type lists, and fundamental generic programming idioms then explains how many useful design patterns (including small object allocators, functors, factories, visitors, and multimethods) can be implemented efficiently, modularly, and cleanly using generic programming. [Review]
* [C++ Template Metaprogramming](http://amzn.to/2qht4ot) (David Abrahams and Aleksey Gurtovoy)
* [C++ Concurrency In Action (Second Edition)](https://www.manning.com/books/c-plus-plus-concurrency-in-action-second-edition) (Anthony Williams) Updated for C++17 and C++20, this book covers C++ concurrency support including the thread library, the atomics library, the C++ memory model, locks and mutexes, as well as issues of designing and debugging multithreaded applications.
* [Advanced C++ Metaprogramming](http://amzn.to/2rRAfVM) (Davide Di Gennaro) A pre-C++11 manual of TMP techniques, focused more on practice than theory. There are a ton of snippets in this book, some of which are made obsolete by typetraits, but the techniques, are nonetheless useful to know. If you can put up with the quirky formatting/editing, it is easier to read than Alexandrescu, and arguably, more rewarding. For more experienced developers, there is a good chance that you may pick up something about a dark corner of C++ (a quirk) that usually only comes about through extensive experience.
* [Beautiful C++: 30 Core Guidelines for Writing Clean, Safe, and Fast Code](https://www.oreilly.com/library/view/beautiful-c-30/9780137647767/) (J. Guy Davidson and Kate Gregory) Based on the C++ Core Guidelines, this book provides 30 practical guidelines for writing better C++ code.
* [C++17 - The Complete Guide](https://leanpub.com/cpp17) (Nicolai Josuttis) Comprehensive coverage of all C++17 features.
* [C++ Move Semantics - The Complete Guide](https://leanpub.com/cppmove) (Nicolai Josuttis) In-depth coverage of move semantics, perfect forwarding, and related topics.

### Reference Style - All Levels

* [The C++ Programming Language](http://amzn.to/2rAE2cK) (Bjarne Stroustrup) (updated for C++11) The classic introduction to C++ by its creator. Written to parallel the classic K&R, this indeed reads very much alike it and covers just about everything from the core language to the standard library, to programming paradigms to the language's philosophy. [Review]
* [C++ Standard Library Tutorial and Reference](http://amzn.to/2ri6GzE) (Nicolai Josuttis) (updated for C++11) The introduction and reference for the C++ Standard Library. The second edition (released on April 9, 2012) covers C++11. [Review]
* [The C++ IO Streams and Locales](http://amzn.to/2qXjcS7) (Angelika Langer and Klaus Kreft) There's very little to say about this book except that, if you want to know anything about streams and locales, then this is the one place to find definitive answers. [Review]

### C++ Standards:

* [The C++ Standard (C++11)](https://www.iso.org/standard/50372.html) (INCITS/ISO/IEC 14882-2011) This, of course, is the final arbiter of all that is or isn't C++. Be aware, however, that it is intended purely as a reference for experienced users willing to devote considerable time and effort to its understanding.
* [The C++14 Standard](https://www.iso.org/standard/64029.html) (ISO/IEC 14882:2014) - Minor improvements and bug fixes to C++11.
* [The C++17 Standard](https://www.iso.org/standard/68564.html) (ISO/IEC 14882:2017) - Major update including std::optional, std::variant, structured bindings, and more.
* [The C++20 Standard](https://www.iso.org/standard/79358.html) (ISO/IEC 14882:2020) - Massive update including concepts, ranges, coroutines, modules, and more.
* [The C++23 Standard](https://www.iso.org/standard/83626.html) (ISO/IEC 14882:2023) - Latest standard with improvements to ranges, std::print, std::expected, and more.
* Free draft standards are available for those who don't want to purchase the official documents. Search for "C++ draft standard" for the latest working drafts.
* [The C++ Core Guidelines](https://github.com/isocpp/CppCoreGuidelines) (C++11/14/17/20/23/…) (edited by Bjarne Stroustrup and Herb Sutter) is an evolving online document consisting of a set of guidelines for using modern C++ well. The guidelines are focused on relatively higher-level issues, such as interfaces, resource management, memory management and concurrency affecting application architecture and library design. The project was announced at CppCon'15 by Bjarne Stroustrup and others and welcomes contributions from the community. Most guidelines are supplemented with a rationale and examples as well as discussions of possible tool support. Many rules are designed specifically to be automatically checkable by static analysis tools.
* [The C++ Super-FAQ](https://isocpp.org/faq) (Marshall Cline, Bjarne Stroustrup and others) is an effort by the Standard C++ Foundation to unify the C++ FAQs previously maintained individually by Marshall Cline and Bjarne Stroustrup and also incorporating new contributions. The items mostly address issues at an intermediate level and are often written with a humorous tone.
* [cppreference.com](https://en.cppreference.com) (C++03/11/14/17/20/23/26/…) (initiated by Nate Kohl) is a wiki that summarizes the basic core-language features and has extensive documentation of the C++ standard library. The documentation is very precise but is easier to read than the official standard document and provides better navigation due to its wiki nature. The project documents all versions of the C++ standard and the site allows filtering the display for a specific version.

### Classics / Older

Note: Some information contained within these books may not be up-to-date or no longer considered best practice.

* [The Design and Evolution of C++](http://amzn.to/2riaPDL) (Bjarne Stroustrup) If you want to know why the language is the way it is, this book is where you find answers. This covers everything before the standardization of C++.
* [Ruminations on C++](http://amzn.to/2rVw3Uf) - (Andrew Koenig and Barbara Moo) [Review]
* [Advanced C++ Programming Styles and Idioms](http://amzn.to/2ricCbT) (James Coplien) A predecessor of the pattern movement, it describes many C++-specific “idioms”. It's certainly a very good book and might still be worth a read if you can spare the time, but quite old and not up-to-date with current C++.
* [Large Scale C++ Software Design](http://amzn.to/2ricGs9) (John Lakos) Lakos explains techniques to manage very big C++ software projects. Certainly a good read, if it only was up to date. It was written long before C++98, and misses on many features (e.g. namespaces) important for large scale projects. If you need to work in a big C++ software project, you might want to read it, although you need to take more than a grain of salt with it. The first volume of a new edition is expected in 2015.
* [Inside the C++ Object Model](http://amzn.to/2rinHcR) (Stanley Lippman) If you want to know how virtual member functions are commonly implemented and how base objects are commonly laid out in memory in a multi-inheritance scenario, and how all this affects performance, this is where you will find thorough discussions of such topics.
* [The Annotated C++ Reference Manual](http://amzn.to/2qQgX4t) (Bjarne Stroustrup, Margaret A. Ellis) This book is quite outdated in the fact that it explores the 1989 C++ 2.0 version - Templates, exceptions, namespaces and new casts were not yet introduced. Saying that however, this book goes through the entire C++ standard of the time explaining the rationale, the possible implementations and features of the language. This is not a book to learn programming principles and patterns on C++, but to understand every aspect of the C++ language.

## Blogs

* [Andrzej's C++ blog](https://akrzemi1.wordpress.com/) - Guidelines and thoughts about C++.
* [Arthur O'Dwyer's blog](https://quuxplusone.github.io/blog/) - Modern C++ insights, particularly on templates and the standard library.
* [Barry Revzin's blog](https://brevzin.github.io/) - Deep dives into C++ language features and standardization.
* [C++ Hints](http://cpphints.com/) - Common mistakes and their solutions.
* [C++ Team Blog (Microsoft)](https://devblogs.microsoft.com/cppblog/) - Updates from the Visual C++ team and C++ community.
* [Embedded in Academia](http://blog.regehr.org/) - John Regehr, Professor of Computer Science, University of Utah, USA.
* [Eric Niebler](http://ericniebler.com/)
* [Fluent C++](https://www.fluentcpp.com/) - Jonathan Boccara's blog on expressive C++ code.
* [Guru of the Week (new posts)](http://herbsutter.com/gotw/) - A regular series of C++ programming problems created and written by Herb Sutter.
* [Guru of the Week (older posts)](http://www.gotw.ca/gotw/) - Older Guru of the Week posts.
* [foonathan::blog()](https://www.foonathan.net/) - Jonathan Müller's blog on C++ library design.
* [Marshall's C++ Musings](https://cplusplusmusings.wordpress.com/)
* [Modernes C++](https://www.modernescpp.com/) - Rainer Grimm's blog about modern C++.
* [Paul Fultz II's Blog](http://pfultz2.com/blog/)
* [Preshing on Programming](http://preshing.com/)
* [Simplify C++](https://arne-mertz.de/) - Write clean and maintainable C++.
* [Sticky Bits](https://blog.feabhas.com/) - A blog looking at developing software for real-time and embedded systems.
* [Sutter's Mill](http://herbsutter.com/) - Herb Sutter on software development.
* [The View from Aristeia](http://scottmeyers.blogspot.com/) - Scott Meyers' Professional Activities and Interests.
* [Why is a raven like a writing desk?](http://www.elbeno.com/blog/)

## Conferences

* [ACCU](https://accu.org/conf-main/main/) - The Conference for Developers (UK-based).
* [C++ Now](https://cppnow.org/) - A gathering of C++ experts and enthusiasts (formerly BoostCon).
* [CppCon](https://cppcon.org/) - The largest C++ conference, held annually in Colorado, USA.
* [Meeting C++](https://meetingcpp.com/) - An independent C++ conference held in Berlin, Germany.
* [C++ on Sea](https://cpponsea.uk/) - A C++ conference in Folkestone, UK.
* [Pacific++](https://pacificplusplus.com/) - C++ conference in the Pacific region (Australia/New Zealand).
* [Core C++](https://corecpp.org/) - C++ conference in Israel.
* [CPPP](https://cppp.fr/) - C++ conference in France.
* [embo++](https://www.embo.io/) - European conference focused on embedded C++.

## Libraries

* [abseil-cpp](https://abseil.io/) - Google's collection of C++ library code designed to augment the C++ standard library.
* [asio](https://think-async.com/Asio/) - Cross-platform C++ library for network and low-level I/O programming (standalone version of Boost.Asio).
* [autocheck](https://github.com/thejohnfreeman/autocheck) - QuickCheck and SmallCheck clones for C++.
* [Bandit](http://banditcpp.org/) - A header-only framework for C++11 that wants to make working with unit tests a pleasant experience.
* [Boost.Hana](http://boostorg.github.io/hana/) - Your standard library for metaprogramming.
* [Boost](http://www.boost.org/) - Collection of C++ libraries.
* [CAF](http://actor-framework.org/) - An Open Source Implementation of the Actor Model in C++.
* [Catch2](https://github.com/catchorg/Catch2) - A modern, C++-native, header-only, test framework for unit-tests, TDD and BDD (version 3 requires C++14).
* [cereal](https://github.com/USCiLab/cereal) - A C++11 library for serialization.
* [ChaiScript](http://chaiscript.com/) - An easy to use embedded scripting language for C++.
* [Cinder](https://libcinder.org/) - Cinder is a free and open source library for professional-quality creative coding in C++.
* [cppitertools](https://github.com/ryanhaining/cppitertools) - itertools (python) implementation for C++17.
* [cpptoml](https://github.com/skystrife/cpptoml) - A header-only library for parsing TOML configuration files.
* [cpr](https://github.com/libcpr/cpr) - C++ Requests: Curl for People, a spiritual port of Python Requests.
* [Crow](https://github.com/CrowCpp/Crow) - Crow is a very fast and easy to use C++ micro web framework.
* [cxxopts](https://github.com/jarro2783/cxxopts) - Lightweight C++ command line option parser.
* [docopt.cpp](https://github.com/docopt/docopt.cpp) - docopt creates beautiful command-line interfaces.
* [doctest](https://github.com/doctest/doctest) - The fastest feature-rich C++ single-header testing framework.
* [entt](https://github.com/skypjack/entt) - A fast and reliable entity-component system (ECS) and much more.
* [expected](https://github.com/TartanLlama/expected) - C++11/14/17 std::expected with functional-style extensions.
* [fmt](https://github.com/fmtlib/fmt) - Modern formatting library (now basis for std::format in C++20).
* [Folly](https://github.com/facebook/folly) - Facebook Open-source Library.
* [frozen](https://github.com/serge-sans-paille/frozen) - Header-only library for constexpr containers, algorithms, and hash tables.
* [glaze](https://github.com/stephenberry/glaze) - Extremely fast, in-memory JSON and other formats for modern C++.
* [GoogleTest](https://github.com/google/googletest) - Google's C++ test framework.
* [gRPC](https://grpc.io/) - High-performance RPC framework.
* [HTTPlib](https://github.com/yhirose/cpp-httplib) - A single-file, header-only C++ HTTP/HTTPS server and client library.
* [imgui](https://github.com/ocornut/imgui) - Bloat-free graphical user interface library for C++.
* [iod](https://github.com/matt-42/iod) - Meta programming utilities for C++14.
* [json](https://github.com/nlohmann/json) - JSON for Modern C++.
* [jsoncpp](https://github.com/open-source-parsers/jsoncpp) - A C++ library for interacting with JSON.
* [Junction](https://github.com/preshing/junction) - Concurrent data structures in C++.
* [libcuckoo](https://github.com/efficient/libcuckoo) - A high-performance, concurrent hash table.
* [magic_enum](https://github.com/Neargye/magic_enum) - Static reflection for enums (header-only, C++17).
* [mongo-cxx-driver](https://github.com/mongodb/mongo-cxx-driver) - C++ Driver for MongoDB.
* [mstch](https://github.com/no1msd/mstch) - A implementation of Mustache templates using modern C++.
* [Mustache](https://github.com/kainjow/Mustache) - Mustache text templates in C++11.
* [nanobench](https://github.com/martinus/nanobench) - Simple, fast, accurate micro-benchmarking for C++11/14/17/20.
* [Outcome](https://github.com/ned14/outcome) - Lightweight error-handling library (alternative to exceptions).
* [PEGTL](https://github.com/taocpp/PEGTL) - Parsing Expression Grammar Template Library (C++17, header-only).
* [pistache](http://pistache.io/) - An elegant C++ REST framework.
* [pybind11](https://github.com/pybind/pybind11) - Seamless operability between C++11 and Python.
* [rang](https://github.com/agauniyal/rang) - A simple, modern & header only C++11 library for colors in your terminal.
* [range-v3](https://github.com/ericniebler/range-v3) - Range library for C++14/17/20 (basis for C++20 ranges).
* [rapidcheck](https://github.com/emil-e/rapidcheck) - QuickCheck clone for C++.
* [rapidjson](https://github.com/Tencent/rapidjson) - Fast JSON parser/generator for C++.
* [redox](https://github.com/hmartiro/redox) - Modern, asynchronous, and wicked fast C++11 client for Redis.
* [refl-cpp](https://github.com/veselink1/refl-cpp) - Static reflection for C++17 (header-only, non-intrusive).
* [robin-hood-hashing](https://github.com/martinus/robin-hood-hashing) - Fast and memory-efficient hash table (C++14/17).
* [spdlog](https://github.com/gabime/spdlog) - Very fast, header-only/compiled, C++ logging library.
* [simple_match](https://github.com/jbandela/simple_match) - Simple header only pattern matching for C++14.
* [simdjson](https://github.com/simdjson/simdjson) - Parsing gigabytes of JSON per second.
* [sol2](https://github.com/ThePhD/sol2) - C++ library binding to Lua.
* [sqlite3pp](https://github.com/iwongu/sqlite3pp) - C++ wrapper of SQLite3 API.
* [sqlite_orm](https://github.com/fnc12/sqlite_orm) - Powerful header only SQLite3 ORM library for C++14.
* [sqlpp11](https://github.com/rbock/sqlpp11) - A type safe SQL template library for C++.
* [TaskFlow](https://github.com/taskflow/taskflow) - Modern C++ parallel programming library.
* [TBB](https://github.com/oneapi-src/oneTBB) - Intel Threading Building Blocks library for advanced multithreaded operations in C++.
* [tinyformat.h](https://github.com/c42f/tinyformat) - Minimal, type safe printf replacement library for C++.
* [tinytoml](https://github.com/mayah/tinytoml) - A header only C++11 library for parsing TOML.
* [toml++](https://github.com/marzer/tomlplusplus) - Header-only TOML config file parser and serializer for C++17.
* [tweeny](https://github.com/mobius3/tweeny) - A header only interpolation library with 30+ easing functions.
* [yaml-cpp](https://github.com/jbeder/yaml-cpp) - A YAML parser and emitter in C++.

## Tools

* [American fuzzy lop](http://lcamtuf.coredump.cx/afl/) - American fuzzy lop is a security-oriented fuzzer.
* [Buck2](https://buck2.build/) - Fast build system from Meta.
* [Bazel](https://bazel.build/) - Fast, scalable, multi-language build system from Google.
* [ccache](https://ccache.dev/) - Compiler cache that speeds up recompilation.
* [cget](https://github.com/pfultz2/cget) - CMake package retrieval.
* [clang-format](https://clang.llvm.org/docs/ClangFormat.html) - A tool to format C++ code.
* [clang-tidy](https://clang.llvm.org/extra/clang-tidy/) - A clang-based C++ "linter" and static analysis tool.
* [clangd](https://clangd.llvm.org/) - Language server for C++ providing IDE features.
* [CMake](https://cmake.org/) - Cross-platform family of tools designed to build, test and package software.
* [Compiler Explorer](https://godbolt.org/) - Interactively explore the assembly output of your C++ code.
* [conan](https://conan.io/) - C/C++ package manager.
* [cppcheck](http://cppcheck.sourceforge.net/) - Static analysis of C/C++ code.
* [C++ Insights](https://cppinsights.io/) - See how your C++ code is transformed by the compiler.
* [include-what-you-use](https://include-what-you-use.org/) - Tool to analyze #includes in C/C++ source files.
* [Hunter](https://github.com/cpp-pm/hunter) - Cross-platform package manager for C++.
* [Meson](https://mesonbuild.com/) - Fast and user-friendly build system.
* [Ninja](https://ninja-build.org/) - Small build system with a focus on speed.
* [PVS-Studio](https://pvs-studio.com/) - Static code analyzer for C, C++, C#, and Java.
* [sccache](https://github.com/mozilla/sccache) - Shared compilation cache from Mozilla.
* [vcpkg](https://vcpkg.io/) - C++ package manager from Microsoft.
* [Xmake](https://xmake.io/) - Lightweight cross-platform build utility based on Lua.

This list has been compiled by **Henrique Bucher** with the help of the C++ community.

- [Vitorian LLC](vitorian.com/x1)
- [henry@vitorian.com](mailto:henry@vitorian.com)
- [github.com/hftrader](https://github.com/hftrader)
- [twitter.com/hftconsulting](https://twitter.com/hftconsulting)
- [linkedin.com/in/hftrader](https://www.linkedin.com/in/hftrader)

