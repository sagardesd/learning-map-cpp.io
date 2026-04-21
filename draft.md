# C++ Learning Roadmap — My Reading List

## C++11 — The Modern C++ Revolution — ~50% of study time

| # | Topic | Article Link |
|---|-------|-------------|
| 1 | **auto Type Deduction** — auto, decltype basics, type inference | [Read Article](https://medium.com/@sagar.necindia/auto-keyword-cpp11-6fa48a67b4bf) |
| 2 | **Range-based for Loops** — for (auto& x : container) syntax | _not yet added_ |
| 3 | **nullptr** — Replacing NULL with type-safe nullptr | _not yet added_ |
| 4 | **Uniform / Brace Initialization** — T obj{args}, initializer lists, narrowing prevention | _not yet added_ |
| 5 | **Scoped Enums (enum class)** — enum class, underlying types, no implicit conversion | [Read Article](https://medium.com/@sagar.necindia/c-11-scoped-enum-6943c9c9b7df) |
| 6 | **static_assert** — Compile-time assertions | _not yet added_ |
| 7 | **using Aliases & override / final / noexcept** — Type aliases, virtual function safety, exception specs | _not yet added_ |
| 8 | **Rvalue References (&&)** — Lvalue vs rvalue, reference collapsing | [Read Article](https://medium.com/@sagar.necindia/move-semantics-rvalues-and-move-constructors-3c5e88c87a21) |
| 9 | **Move Constructors & Move Assignment** — Transferring ownership efficiently | [Read Article](https://medium.com/@sagar.necindia/move-semantics-rvalues-and-move-constructors-3c5e88c87a21) |
| 10 | **std::move** — Casting to rvalue reference, enabling moves | [Read Article](https://medium.com/@sagar.necindia/move-semantics-rvalues-and-move-constructors-3c5e88c87a21) |
| 11 | **Perfect Forwarding & std::forward** — Forwarding references, preserving value category | [Read Article](https://medium.com/@sagar.necindia/cpp-forwarding-references-perfect-forwarding-ec7a9285d8b5) |
| 12 | **Rule of Five** — Destructor, copy/move constructors, copy/move assignment | [Read Article](https://medium.com/@sagar.necindia/cpp-rvo-return-value-optimization-b6f468057298) |
| 13 | **Copy Elision / RVO / NRVO** — Compiler optimizations avoiding copies | [Read Article](https://medium.com/@sagar.necindia/cpp-rvo-return-value-optimization-b6f468057298) |
| 14 | **std::unique_ptr** — Exclusive ownership smart pointer | [Read Article](https://medium.com/@sagar.necindia/c-11-exclusive-ownership-smart-pointer-std-unique-ptr-t-80d5a91bfc88) |
| 15 | **std::shared_ptr & std::weak_ptr** — Shared ownership, breaking circular references | [Read Article](https://medium.com/@sagar.necindia/c-11-understanding-std-shared-ptr-t-shared-ownership-of-resources-d3e666514e0b) |
| 16 | **RAII Pattern** — Resource Acquisition Is Initialization — deep understanding | [Read Article](https://towardsdev.com/raii-c-way-to-resource-management-22404eb1d9d6) |
| 17 | **Lambda Expressions — Basics** — Syntax, return types, inline function objects | _not yet added_ |
| 18 | **Lambda Capture Clauses** — [=], [&], [this], mixed captures | _not yet added_ |
| 19 | **Mutable Lambdas & std::function** — Modifying captured values, type-erased callables | _not yet added_ |
| 20 | **Variadic Templates** — template<typename... Args>, parameter packs | [Read Article](https://medium.com/@sagar.necindia/c-11-variadic-templates-6751f81f83cf) |
| 21 | **decltype** — Querying expression types at compile time | [Read Article](https://medium.com/towardsdev/cpp-decltype-explained-guide-c389abd7a6ca) |
| 22 | **SFINAE & std::enable_if** — Substitution Failure Is Not An Error | _not yet added_ |
| 23 | **<type_traits> Library** — is_integral, is_same, conditional, etc. | _not yet added_ |
| 24 | **constexpr (Basics)** — Compile-time evaluation of functions and variables | [Read Article](https://medium.com/@sagar.necindia/constexpr-part-i-the-engine-of-modern-c-meta-programming-d9896938f8ba) |
| 25 | **std::thread** — Creating and joining threads | _not yet added_ |
| 26 | **std::mutex & std::lock_guard** — Mutual exclusion, RAII locking | _not yet added_ |
| 27 | **std::condition_variable** — Thread synchronization, wait/notify | _not yet added_ |
| 28 | **std::future, std::promise, std::async** — Asynchronous computation results | _not yet added_ |
| 29 | **std::atomic** — Lock-free atomic operations | _not yet added_ |
| 30 | **Memory Model** — acquire, release, seq_cst, happens-before | _not yet added_ |
| 31 | **std::array & std::unordered_map/set** — Fixed-size array, hash-based containers | _not yet added_ |
| 32 | **std::tuple & std::tie** — Heterogeneous fixed-size collection, structured unpacking | _not yet added_ |
| 33 | **std::function & std::bind** — Type-erased callable wrapper, partial application | _not yet added_ |
| 34 | **std::chrono** — Clocks, durations, time points | _not yet added_ |
| 35 | **<random> Library** — Engines, distributions, proper RNG | _not yet added_ |
| 36 | **std::initializer_list & User-defined Literals** — Brace-init lists, custom suffixes (operator"") | _not yet added_ |

## C++14 — Quality-of-Life Polish — ~5% of study time

| # | Topic | Article Link |
|---|-------|-------------|
| 1 | **Generic Lambdas (auto params)** — [](auto x) { ... } — polymorphic lambdas | _not yet added_ |
| 2 | **Lambda Init Captures** — [x = std::move(y)] — generalized captures | _not yet added_ |
| 3 | **std::make_unique** — Safe unique_ptr creation, no naked new | [Read Article](https://towardsdev.com/why-std-make-unique-beats-new-in-modern-c-7e2ba653737e) |
| 4 | **Return Type Deduction** — auto return on regular functions | _not yet added_ |
| 5 | **Relaxed constexpr** — Loops, local variables, if/else in constexpr functions | _not yet added_ |
| 6 | **Variable Templates** — template<typename T> constexpr T pi = ... | _not yet added_ |
| 7 | **decltype(auto)** — Deducing exact type including references | _not yet added_ |
| 8 | **Binary Literals & Digit Separators** — 0b1010, 1'000'000 — readability | _not yet added_ |
| 9 | **std::shared_timed_mutex** — Reader-writer locks, std::shared_lock | _not yet added_ |
| 10 | **std::integer_sequence** — Compile-time integer sequences, index_sequence | _not yet added_ |

## C++17 — Major Productivity Boost — ~15% of study time

| # | Topic | Article Link |
|---|-------|-------------|
| 1 | **Structured Bindings** — auto [key, value] = pair; — decomposition | _not yet added_ |
| 2 | **if constexpr** — Compile-time branching in templates | _not yet added_ |
| 3 | **if / switch with Initializers** — if (auto it = m.find(k); it != m.end()) | _not yet added_ |
| 4 | **Class Template Argument Deduction (CTAD)** — std::pair p{1, 2.0}; — no explicit template args | _not yet added_ |
| 5 | **Fold Expressions** — (args + ...) — variadic template folding | _not yet added_ |
| 6 | **Inline Variables & constexpr Lambdas** — inline static, lambdas in constexpr context | _not yet added_ |
| 7 | **Nested Namespaces & Attributes** — A::B::C, [[nodiscard]], [[maybe_unused]] | _not yet added_ |
| 8 | **std::optional** — Nullable value type — replacing sentinel values | _not yet added_ |
| 9 | **std::variant** — Type-safe union, std::visit | _not yet added_ |
| 10 | **std::any** — Type-erased single value container | _not yet added_ |
| 11 | **std::string_view** — Non-owning string reference, zero-copy | _not yet added_ |
| 12 | **std::filesystem** — Paths, directory iteration, file operations | _not yet added_ |
| 13 | **Parallel Algorithms** — std::execution::par, par_unseq, seq | _not yet added_ |
| 14 | **std::scoped_lock & std::shared_mutex** — Multi-mutex RAII lock, reader-writer improved | _not yet added_ |
| 15 | **std::invoke / std::apply** — Uniform callable invocation, tuple unpacking | _not yet added_ |
| 16 | **std::byte & Numeric Utilities** — std::byte, clamp, gcd, lcm, from_chars, to_chars | _not yet added_ |

## C++20 — The Second Revolution — ~22% of study time

| # | Topic | Article Link |
|---|-------|-------------|
| 1 | **Concepts — Basics** — concept keyword, what problems they solve | [Read Article](https://towardsdev.com/c-concepts-constraining-templates-c-20-c862f2947c61) |
| 2 | **requires Clauses & Expressions** — requires { expr; }, compound requirements | [Read Article](https://towardsdev.com/c-concepts-constraining-templates-c-20-c862f2947c61) |
| 3 | **Standard Library Concepts** — std::integral, std::copyable, std::ranges::range | [Read Article](https://towardsdev.com/c-concepts-constraining-templates-c-20-c862f2947c61) |
| 4 | **Abbreviated Function Templates** — void foo(std::integral auto x) — concise syntax | [Read Article](https://medium.com/@sagar.necindia/c-20-abbreviated-function-templates-a-modern-approach-to-generic-programming-ff98e4f5316c) |
| 5 | **Ranges — Philosophy & Basics** — Lazy evaluation, composability, range adaptors | [Read Article](https://medium.com/@sagar.necindia/cpp20-ranges-deep-dive-core-mechanics-62b6661b2885) |
| 6 | **Range Views** — views::filter, transform, take, drop, reverse | [Read Article](https://towardsdev.com/cpp20-std-views-guide-ranges-pipelines-a95790b3cd8c) |
| 7 | **Pipe Composition & Projections** — view1 | view2 | view3, projection parameters | [Read Article](https://medium.com/towardsdev/cpp20-std-views-guide-ranges-pipelines-a95790b3cd8c) |
| 8 | **Sentinels vs Iterators** — Generalized end conditions, subrange | [Read Article](https://medium.com/towardsdev/cpp-sentinels-adl-cpo-guide-8a8499c13720) |
| 9 | **Coroutines — Mental Model** — Suspension, resumption, lazy computation | [Read Article](https://towardsdev.com/cpp20-coroutines-demystified-part-1-generator-mental-model-67ace9265be3) |
| 10 | **co_await, co_yield, co_return** — Core coroutine keywords | [Read Article](https://towardsdev.com/cpp20-coroutines-part-2-co-await-task-async-patterns-8e47cc94d49d) |
| 11 | **Promise Type & coroutine_handle** — Customization machinery for coroutines | _not yet added_ |
| 12 | **Writing Generators & Async Tasks** — Practical coroutine patterns | _not yet added_ |
| 13 | **Modules** — export module, import, header units, build systems | _not yet added_ |
| 14 | **Spaceship Operator (<=>)** — Three-way comparison, strong/weak/partial ordering | [Read Article](https://towardsdev.com/cpp20-spaceship-operator-three-way-comparison-b1213302bf93) |
| 15 | **Designated Initializers** — Point{.x = 1, .y = 2} — named member init | [Read Article](https://medium.com/@sagar.necindia/designated-initialization-in-c-20-making-your-code-self-documenting-99f7920ef140) |
| 16 | **consteval & constinit** — Immediate functions, guaranteed static init | [Read Article](https://medium.com/towardsdev/consteval-cpp20-guide-6e8175dd4a73) |
| 17 | **Expanded constexpr** — constexpr vector, string, virtual, try-catch | [Read Article](https://medium.com/@sagar.necindia/cpp-constexpr-evolution-cpp11-to-cpp20-8830aa9a1275) |
| 18 | **Lambda Improvements** — Template lambdas, pack captures, unevaluated ctx | [Read Article](https://medium.com/@sagar.necindia/from-specific-to-general-a-guide-to-predicates-functors-and-lambda-functions-in-c-9b4ba2f282dc) |
| 19 | **std::format** — Python-like string formatting | _not yet added_ |
| 20 | **std::span** — Non-owning contiguous view, replacing ptr+size | [Read Article](https://towardsdev.com/cpp20-std-span-guide-memory-views-8373dc211f6a) |
| 21 | **std::jthread & stop_token** — Auto-joining thread, cooperative cancellation | [Read Article](https://towardsdev.com/c-20-std-jthread-the-thread-you-always-wanted-no-more-manual-joins-6a3558ff081e) |
| 22 | **Latches, Barriers & Semaphores** — std::latch, std::barrier, std::counting_semaphore | _not yet added_ |
| 23 | **Calendar & Time Zones (chrono)** — year_month_day, zoned_time, time zone support | _not yet added_ |
| 24 | **std::source_location** — Replacing __FILE__, __LINE__ macros | [Read Article](https://medium.com/towardsdev/profiling-cpp20-range-pipelines-source-location-38ad26547eb9) |
| 25 | **Bit Utilities & <numbers>** — bit_cast, popcount, countl_zero, pi, e constants | [Read Article](https://towardsdev.com/cpp20-bit-header-clean-portable-333de74203f1) |
| 26 | **Container Improvements** — erase_if, starts_with, ends_with, contains() | _not yet added_ |

## C++23 — Refinement & Completion — ~8% of study time

| # | Topic | Article Link |
|---|-------|-------------|
| 1 | **if consteval** — Detect compile-time vs runtime context | _not yet added_ |
| 2 | **Deducing this** — Explicit object parameter — CRTP-free mixins | _not yet added_ |
| 3 | **Multidimensional operator[]** — operator[](int x, int y) — matrix access | _not yet added_ |
| 4 | **auto(x) & static operator()** — Decay-copy expressions, static call operators | _not yet added_ |
| 5 | **[[assume(expr)]]** — Optimizer hints, undefined if false | _not yet added_ |
| 6 | **views::zip & views::zip_transform** — Parallel range iteration | _not yet added_ |
| 7 | **views::chunk & views::chunk_by** — Splitting ranges into groups | _not yet added_ |
| 8 | **views::slide & views::stride** — Sliding windows, stepping through ranges | _not yet added_ |
| 9 | **views::enumerate & views::cartesian_product** — Index+value pairs, cross-product of ranges | _not yet added_ |
| 10 | **ranges::to<Container>()** — Materialize a view/range into a container | _not yet added_ |
| 11 | **ranges::fold_left / fold_right** — Range-based reduce/accumulate | _not yet added_ |
| 12 | **std::expected<T, E>** — Error handling without exceptions | _not yet added_ |
| 13 | **std::mdspan** — Multidimensional non-owning view | _not yet added_ |
| 14 | **std::generator** — Standard coroutine generator type | _not yet added_ |
| 15 | **std::print / std::println** — Modern formatted output (replacing cout) | _not yet added_ |
| 16 | **std::flat_map / std::flat_set** — Sorted vector-backed associative containers | _not yet added_ |
| 17 | **std::stacktrace** — Programmatic stack trace capture | _not yet added_ |
| 18 | **std::move_only_function** — Non-copyable callable wrapper | _not yet added_ |
| 19 | **Monadic std::optional** — and_then, transform, or_else — chaining | _not yet added_ |
| 20 | **Utility Additions** — unreachable(), to_underlying, byteswap, out_ptr | _not yet added_ |

