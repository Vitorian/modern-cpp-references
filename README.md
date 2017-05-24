---
---

# Awesome Modern C++

A collection of resources on modern C++.

The goal is to collect a list of resouces to help people learn about
and leverage modern C++11 and beyond.

## Books

* [The C++ Programming Language](http://amzn.to/2rAE2cK) (Bjarne Stroustrup) [C++11]
* [Effective Modern C++](http://amzn.to/2qXjOZT) (Scott Meyers) [C++11/14]

### Beginner

Introductory, no previous programming experience

* [Programming: Principles and Practice Using C++ (Bjarne Stroustrup) (updated for C++11/C++14)](http://amzn.to/2qX9ssX) An introduction to programming using C++ by the creator of the language. A good read, that assumes no previous programming experience, but is not only for beginners.

Introductory, with previous programming experience

* [C++ Primer *](http://amzn.to/2qhkshD) (Stanley Lippman, Josée Lajoie, and Barbara E. Moo) (updated for C++11)(https://www.amazon.com/dp/0321714113) Coming at 1k pages, this is a very thorough introduction into C++ that covers just about everything in the language in a very accessible format and in great detail. The fifth edition (released August 16, 2012) covers C++11. [Review]
* [A Tour of C++](http://amzn.to/2qX1RsF) (Bjarne Stroustrup) (EBOOK) The “tour” is a quick (about 180 pages and 14 chapters) tutorial overview of all of standard C++ (language and standard library, and using C++11) at a moderately high level for people who already know C++ or at least are experienced programmers. This book is an extended version of the material that constitutes Chapters 2-5 of The C++ Programming Language, 4th edition.
* [Accelerated C++](http://amzn.to/2rRbg4T) (Andrew Koenig and Barbara Moo) This basically covers the same ground as the C++ Primer, but does so on a fourth of its space. This is largely because it does not attempt to be an introduction to programming, but an introduction to C++ for people who've previously programmed in some other language. It has a steeper learning curve, but, for those who can cope with this, it is a very compact introduction into the language. (Historically, it broke new ground by being the first beginner's book to use a modern approach at teaching the language.) [Review]
* [Thinking in C++ - Volume 1](http://amzn.to/2ri2qjD) [Volume 2](http://amzn.to/2rAJpZA) (Bruce Eckel) Two volumes; is a tutorial style free set of intro level books. Downloads: vol 1, vol 2. Unfortunately they’re marred by a number of trivial errors (e.g. maintaining that temporaries are automatically const), with no official errata list. A partial 3rd party errata list is available at (http://www.computersciencelab.com/Eckel.htm), but it’s apparently not maintained.  Not to be confused with C++ Primer Plus (Stephen Prata), with a significantly less favorable review.

Best practices

[Effective C++](http://amzn.to/2qX3mJh) (Scott Meyers) This was written with the aim of being the best second book C++ programmers should read, and it succeeded. Earlier editions were aimed at programmers coming from C, the third edition changes this and targets programmers coming from languages like Java. It presents ~50 easy-to-remember rules of thumb along with their rationale in a very accessible (and enjoyable) style. For C++11 and C++14 the examples and a few issues are outdated and Effective Modern C++ should be preferred. [Review]
Effective Modern C++ (Scott Meyers) This is basically the new version of Effective C++, aimed at C++ programmers making the transition from C++03 to C++11 and C++14.
Effective STL (Scott Meyers) This aims to do the same to the part of the standard library coming from the STL what Effective C++ did to the language as a whole: It presents rules of thumb along with their rationale. [Review]
Intermediate

More Effective C++ (Scott Meyers) Even more rules of thumb than Effective C++. Not as important as the ones in the first book, but still good to know.
Exceptional C++ (Herb Sutter) Presented as a set of puzzles, this has one of the best and thorough discussions of the proper resource management and exception safety in C++ through Resource Acquisition is Initialization (RAII) in addition to in-depth coverage of a variety of other topics including the pimpl idiom, name lookup, good class design, and the C++ memory model. [Review]
More Exceptional C++ (Herb Sutter) Covers additional exception safety topics not covered in Exceptional C++, in addition to discussion of effective object oriented programming in C++ and correct use of the STL. [Review]
Exceptional C++ Style (Herb Sutter) Discusses generic programming, optimization, and resource management; this book also has an excellent exposition of how to write modular code in C++ by using nonmember functions and the single responsibility principle. [Review]
C++ Coding Standards (Herb Sutter and Andrei Alexandrescu) “Coding standards” here doesn't mean “how many spaces should I indent my code?” This book contains 101 best practices, idioms, and common pitfalls that can help you to write correct, understandable, and efficient C++ code. [Review]
C++ Templates: The Complete Guide (David Vandevoorde and Nicolai M. Josuttis) This is the book about templates as they existed before C++11. It covers everything from the very basics to some of the most advanced template metaprogramming and explains every detail of how templates work (both conceptually and at how they are implemented) and discusses many common pitfalls. Has excellent summaries of the One Definition Rule (ODR) and overload resolution in the appendices. A second edition is scheduled for 2017. [Review]
Advanced

Modern C++ Design (Andrei Alexandrescu) A groundbreaking book on advanced generic programming techniques. Introduces policy-based design, type lists, and fundamental generic programming idioms then explains how many useful design patterns (including small object allocators, functors, factories, visitors, and multimethods) can be implemented efficiently, modularly, and cleanly using generic programming. [Review]
C++ Template Metaprogramming (David Abrahams and Aleksey Gurtovoy)
C++ Concurrency In Action (Anthony Williams) A book covering C++11 concurrency support including the thread library, the atomics library, the C++ memory model, locks and mutexes, as well as issues of designing and debugging multithreaded applications.
Advanced C++ Metaprogramming (Davide Di Gennaro) A pre-C++11 manual of TMP techniques, focused more on practice than theory. There are a ton of snippets in this book, some of which are made obsolete by typetraits, but the techniques, are nonetheless useful to know. If you can put up with the quirky formatting/editing, it is easier to read than Alexandrescu, and arguably, more rewarding. For more experienced developers, there is a good chance that you may pick up something about a dark corner of C++ (a quirk) that usually only comes about through extensive experience.
Reference Style - All Levels

The C++ Programming Language (Bjarne Stroustrup) (updated for C++11) The classic introduction to C++ by its creator. Written to parallel the classic K&R, this indeed reads very much alike it and covers just about everything from the core language to the standard library, to programming paradigms to the language's philosophy. [Review]
C++ Standard Library Tutorial and Reference (Nicolai Josuttis) (updated for C++11) The introduction and reference for the C++ Standard Library. The second edition (released on April 9, 2012) covers C++11. [Review]
The C++ IO Streams and Locales (Angelika Langer and Klaus Kreft) There's very little to say about this book except that, if you want to know anything about streams and locales, then this is the one place to find definitive answers. [Review]
C++11/14 References:

The C++ Standard (INCITS/ISO/IEC 14882-2011) This, of course, is the final arbiter of all that is or isn't C++. Be aware, however, that it is intended purely as a reference for experienced users willing to devote considerable time and effort to its understanding. As usual, the first release was quite expensive ($300+ US), but it has now been released in electronic form for $60US.
The C++14 standard is available, but seemingly not in an economical form – directly from the ISO it costs 198 Swiss Francs (about $200 US). For most people, the final draft before standardization is more than adequate (and free). Many will prefer an even newer draft, documenting new features that are likely to be included in C++17.
Overview of the New C++ (C++11/14) (PDF only) (Scott Meyers) (updated for C++1y/C++14) These are the presentation materials (slides and some lecture notes) of a three-day training course offered by Scott Meyers, who's a highly respected author on C++. Even though the list of items is short, the quality is high.
The C++ Core Guidelines (C++11/14/17/…) (edited by Bjarne Stroustrup and Herb Sutter) is an evolving online document consisting of a set of guidelines for using modern C++ well. The guidelines are focused on relatively higher-level issues, such as interfaces, resource management, memory management and concurrency affecting application architecture and library design. The project was announced at CppCon'15 by Bjarne Stroustrup and others and welcomes contributions from the community. Most guidelines are supplemented with a rationale and examples as well as discussions of possible tool support. Many rules are designed specifically to be automatically checkable by static analysis tools.
The C++ Super-FAQ (Marshall Cline, Bjarne Stroustrup and others) is an effort by the Standard C++ Foundation to unify the C++ FAQs previously maintained individually by Marshall Cline and Bjarne Stroustrup and also incorporating new contributions. The items mostly address issues at an intermediate level and are often written with a humorous tone. Not all items might be fully up to date with the latest edition of the C++ standard yet.
cppreference.com (C++03/11/14/17/…) (initiated by Nate Kohl) is a wiki that summarizes the basic core-language features and has extensive documentation of the C++ standard library. The documentation is very precise but is easier to read than the official standard document and provides better navigation due to its wiki nature. The project documents all versions of the C++ standard and the site allows filtering the display for a specific version. The project was presented by Nate Kohl at CppCon'14.
Classics / Older

Note: Some information contained within these books may not be up-to-date or no longer considered best practice.

The Design and Evolution of C++ (Bjarne Stroustrup) If you want to know why the language is the way it is, this book is where you find answers. This covers everything before the standardization of C++.
Ruminations on C++ - (Andrew Koenig and Barbara Moo) [Review]
Advanced C++ Programming Styles and Idioms (James Coplien) A predecessor of the pattern movement, it describes many C++-specific “idioms”. It's certainly a very good book and might still be worth a read if you can spare the time, but quite old and not up-to-date with current C++.
Large Scale C++ Software Design (John Lakos) Lakos explains techniques to manage very big C++ software projects. Certainly a good read, if it only was up to date. It was written long before C++98, and misses on many features (e.g. namespaces) important for large scale projects. If you need to work in a big C++ software project, you might want to read it, although you need to take more than a grain of salt with it. The first volume of a new edition is expected in 2015.
Inside the C++ Object Model (Stanley Lippman) If you want to know how virtual member functions are commonly implemented and how base objects are commonly laid out in memory in a multi-inheritance scenario, and how all this affects performance, this is where you will find thorough discussions of such topics.
The Annotated C++ Reference Manual (Bjarne Stroustrup, Margaret A. Ellis) This book is quite outdated in the fact that it explores the 1989 C++ 2.0 version - Templates, exceptions, namespaces and new casts were not yet introduced. Saying that however, this book goes through the entire C++ standard of the time explaining the rationale, the possible implementations and features of the language. This is not a book to learn programming principles and patterns on C++, but to understand every aspect of the C++ language.



## Blogs

* [Andrzej's C++ blog](https://akrzemi1.wordpress.com/) - Guidelines and thoughts about C++.
* [C++ Hints](http://cpphints.com/) - Common mistakes and their solutions.
* [Embedded in Academia](http://blog.regehr.org/) - John Regehr, Professor of Computer Science, University of Utah, USA.
* [Eric Niebler](http://ericniebler.com/)
* [Guru of the Week (new posts)](http://herbsutter.com/gotw/) - A regular series of C++ programming problems created and written by Herb Sutter.
* [Guru of the Week (older posts)](http://www.gotw.ca/gotw/) - Older Guru of the Week posts.
* [Marshall's C++ Musings](https://cplusplusmusings.wordpress.com/)
* [Paul Fultz II's Blog](http://pfultz2.com/blog/)
* [Preshing on Programming](http://preshing.com/)
* [Simplify C++](http://arne-mertz.de/) - Write clean and maintainable C++.
* [Sticky Bits](https://blog.feabhas.com/) - A blog looking at developing software for real-time and embedded systems.
* [Sutter's Mill](http://herbsutter.com/) - Herb Sutter on software development.
* [The View from Aristeia](http://scottmeyers.blogspot.com/) -Scott Meyers' Professional Activities and Interests.
* [Visual C++ Team Blog](https://blogs.msdn.microsoft.com/vcblog/)
* [Why is a raven like a writing desk?](http://www.elbeno.com/blog/)

## Conferences

* [ACCU](http://accu.org/index.php/conferences) - The Conference for Developers.
* [C++ Now](http://cppnow.org/) - A gathering of C++ experts and enthusiasts.
* [CppCon](http://cppcon.org/) - The C++ Conference.
* [Meeting C++](http://meetingcpp.com/) - A independent C++ Conference.

## Libraries


* [autocheck](https://github.com/thejohnfreeman/autocheck) - QuickCheck and SmallCheck clones for C++.
* [Bandit](http://banditcpp.org/) - A header-only framework for C++11 that wants to make working with unit tests a pleasant experience.
* [Boost.Hana](http://boostorg.github.io/hana/) - Your standard library for metaprogramming.
* [Boost](http://www.boost.org/) - Collection of C++ libraries.
* [C++ Format](https://github.com/cppformat/cppformat) - Small, safe and fast formatting library for C++.
* [CAF](http://actor-framework.org/) - An Open Source Implementation of the Actor Model in C++.
* [Catch](https://github.com/philsquared/Catch) - A modern, C++-native, header-only, framework for unit-tests, TDD and BDD.
* [doctest](https://github.com/onqtam/doctest) - The lightest feature rich C++ single header testing framework.
* [cereal](https://github.com/USCiLab/cereal) - A C++11 library for serialization.
* [ChaiScript](http://chaiscript.com/) - An easy to use embedded scripting language for C++.
* [Cinder](https://libcinder.org/) - Cinder is a free and open source library for professional-quality creative coding in C++.
* [cpptoml](https://github.com/skystrife/cpptoml) - A header-only library for parsing TOML configuration files.
* [cppitertools](https://github.com/ryanhaining/cppitertools) - itertools (python) implementation for C++14
* [cpr](https://github.com/whoshuu/cpr) - C++ Requests: Curl for People, a spiritual port of Python Requests.
* [Crow](https://github.com/ipkn/crow) - Crow is very fast and easy to use C++ micro web framework.
* [cxxopts](https://github.com/jarro2783/cxxopts) -  Lightweight C++ command line option parser.
* [docopt.cpp](https://github.com/docopt/docopt.cpp) - docopt creates beautiful command-line interfaces.
* [fixed_size_function](https://github.com/pmed/fixed_size_function) - Fixed size function wrapper like std::function.
* [Folly](https://github.com/facebook/folly) - Facebook Open-source Library.
* [iod](https://github.com/matt-42/iod) -  Meta programming utilities for C++14.
* [json](https://github.com/nlohmann/json) - JSON for Modern C++.
* [jsoncpp](https://github.com/open-source-parsers/jsoncpp) - A C++ library for interacting with JSON.
* [Junction](https://github.com/preshing/junction) - Concurrent data structures in C++.
* [mongo-cxx-driver](https://github.com/mongodb/mongo-cxx-driver) - C++ Driver for MongoDB.
* [mstch](https://github.com/no1msd/mstch) -  A implementation of Mustache templates using modern C++.
* [Mustache](https://github.com/kainjow/Mustache) - Mustache text templates in C++11.
* [Nonius](https://nonius.io/) - A C++ micro-benchmarking framework.
* [PEGTL](https://github.com/ColinH/PEGTL) - Parsing Expression Grammar Template Library (C++11, header-only).
* [pistache](http://pistache.io/) - An elegant C++ REST framework.
* [pybind11](https://github.com/pybind/pybind11) - Seamless operability between C++11 and Python.
* [rang](https://github.com/agauniyal/rang) - A simple, modern & header only C++11 library for colors in your terminal.
* [range-v3](https://github.com/ericniebler/range-v3) - Experimental range library for C++11/14/17.
* [rapidcheck](https://github.com/emil-e/rapidcheck) - QuickCheck clone for C++.
* [redox](https://github.com/hmartiro/redox) - Modern, asynchronous, and wicked fast C++11 client for Redis.
* [simple_match](https://github.com/jbandela/simple_match) - Simple header only pattern matching for c++14.
* [sol2](https://github.com/ThePhD/sol2) - C++ library binding to Lua.
* [sqlite3pp](https://github.com/iwongu/sqlite3pp) - C++ wrapper of SQLite3 API.
* [sqlite_orm](https://github.com/fnc12/sqlite_orm) - powerful header only SQLite3 ORM library for C++14
* [sqlpp11](https://github.com/rbock/sqlpp11) - A type safe SQL template library for C++.
* [TBB](https://github.com/01org/tbb) - Intel Threading Building Blocks library for advanced multithreaded operations in C++.
* [tinyformat.h](https://github.com/c42f/tinyformat) - Minimal, type safe printf replacement library for C++.
* [tinytoml](https://github.com/mayah/tinytoml) -A header only C++11 library for parsing TOML.
* [tweeny](https://github.com/mobius3/tweeny) - A header only interpolation library with 30+ easing functions.
* [yaml-cpp](https://github.com/jbeder/yaml-cpp) - A YAML parser and emitter in C++.

## Tools

* [American fuzzy lop](http://lcamtuf.coredump.cx/afl/) - American fuzzy lop is a security-oriented fuzzer.
* [cget](https://github.com/pfultz2/cget) - CMake package retrieval.
* [clang-format](http://clang.llvm.org/docs/ClangFormat.html) - A tool to format C++ code.
* [clang-tidy](http://clang.llvm.org/extra/clang-tidy/) - A clang-based C++ "linter" and static analysis tool.
* [CMake](https://cmake.org/) - Cross-platform family of tools designed to build, test and package software.
* [Compiler Explorer](https://gcc.godbolt.org/) - Interactively explore the assembly output of your C++ code.
* [conan](https://www.conan.io/) - C/C++ package manager.
* [cppcheck](http://cppcheck.sourceforge.net/) - Static analysis of C/C++ code.
* [Hunter](https://github.com/ruslo/hunter) - Cross-platform package manager for C++.
* [irony-mode](https://github.com/Sarcasm/irony-mode) -  A C/C++ minor mode for Emacs powered by libclang.
* [modern-cpp-font-lock-mode](https://github.com/ludwigpacifici/modern-cpp-font-lock) - Syntax highlighting support for Modern C++ with emacs

