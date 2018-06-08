# RustFest 2018 impl days project list

**This url is: https://bit.ly/impldays**

Adresses:

* Mozilla: 16bis Boulevard Montmartre, 75009 Paris (https://goo.gl/maps/VNEL8yGFerQ2)
* Formeret Espace Clery: 17, rue de Cléry, 75002 Paris (https://goo.gl/maps/4G6eUFvoYqR2)

# realtime data

## mozilla fill status

40 of 55

## Formeret Espace Cléry room 101 fill status

0 of 40

# Tuesday, May 29th

## Currently running

Don't break the table plz :( :laughing: 

| What? | Where? | Audience  |
| -------- | -------- | -------- |
| embedded | Formeret 101 | Solving the hard(ware) problems |
| cargo related | Formeret 101 | everything that looks simple but isn't :wink: |
| cargo | Mozilla | (apprently there are two concurrent groups?) |
| “good first bug” / E-easy issues | Mozilla | who wants to do some more? RSVP irc://irc.mozilla.org/#rustfest-easyissues |
| pep | Formeret 101 | peope |
| shared libs for Android | Mozilla | |
| Non-lexical Lifetimes (NLL) | Mozilla | compiler hackers *or* Prolog hackers |
| command line interface (CLI) | Mozilla | |
| COAP (IOT comunication protocol) support for tokio | Mozilla | |
| Prototyping Deref/DerefMut on `match`-patterns  | Mozilla | |
| Quinn (QUIC implementation) | Formeret 101 | |




## Done

| Who?            | What? |
| --------        | ----- |
| @dns2utf8 | Played with integrating QUIC into [SGE Cluster Interface](https://crates.io/crates/son_of_grid_engine) |
| @g2p | Sent a [PR to add an rdrand ABI to Nebulet](https://github.com/nebulet/nebulet/issues/29)|
| @farodin91 | https://github.com/assert-rs/predicates-rs/pull/42|
| @darArch | https://github.com/rust-lang-nursery/rust-clippy/pull/2815|
| @pacman82 | [PR to rustc with a small refactoring](https://github.com/rust-lang/rust/pull/51159)|
| @gibix + @apiraino (basically just watching) | https://github.com/rust-av/speexdsp-rs/issues/1 and https://github.com/rust-av/speexdsp-rs/issues/2 |
| @faern | [Making rustc intrinsics `const fn`s](https://github.com/rust-lang/rust/pull/51171)
| @rnestler | [publishing lpc11uxx-hal 0.1.0](https://crates.io/crates/lpc11uxx-hal)|
| @Amanieu + @SimonSapin | More incremental progress on `GlobalAlloc` https://github.com/rust-lang/rust/issues/49668 |
| @evolix1 | [QUIC QPACK decoding](https://github.com/djc/quinn/pull/20) |
| @esteve | https://github.com/rust-lang/cargo/pull/5590 |
| @esteve | https://github.com/rust-lang/cargo/pull/5592 |
| @oli-obk | https://github.com/rust-lang/rust/pull/51122 |
| @vladimir-lu | tried to understand https://github.com/rust-lang-nursery/polonius and datafrog implementations |
| @killercup | https://crates.io/crates/success |
| @ag_dubs + @killercup | https://github.com/ashleygwilliams/cargo-generate |
| @simonasker | First (tiny) contribution! https://github.com/rust-lang/cargo/pull/5591 |
| @jvff | Improved speed of Polonius CFG simplification attempt: https://github.com/rust-lang-nursery/polonius/compare/master...jvff:condense-cfg |
| @farodin91 | https://github.com/assert-rs/predicates-rs/pull/43 |
| @farodin91 | Try to write tests for the test window https://github.com/intellij-rust/intellij-rust/pull/2337 |
| @vakaras | Opened [PR](https://github.com/rust-lang-nursery/polonius/pull/64) for comparing NLL algorithms |
| japaric | Resumed work on the [llvm-tools PR](https://github.com/rust-lang/rust/pull/50336) |


# Monday, May 28th

| What? | Where? | Audience  |
| -------- | -------- | -------- |
| Conference Planning Workshop | Mozilla (Kitchen) | Everyone interested in running a (Rust) conference |
| "good first bug" / E-easy issues | Mozilla | starting contributors #rustfest-easyissues |
| Non-lexical Lifetimes (NLL) / Polonius | Mozilla | rustc (or Prolog) hackers | 
| WebAssembly | Formeret 101 | Work on WASM issues |
| embedded | Formeret 201 | TOK and more |
| QUIC | Formeret 101 | Work on Quinn, the QUIC implementation |
| Networking | Mozilla | improve existing and/or bugged implementations such as tokio-coap and tokio-mqttc |
| Cli | Mozilla | |
| OpenPGP | Formeret (pEp t-shirts) 101 | OpenPGP Integration in Rust ecosystem / Sequoia Implementation (https://sequoia-pgp.org)
| Linter | Formeret 101 | Improve rustc linter docs & linter experiments |
| Cargo  | Formeret 101  | Everything Cargo / Android `externalNativeBuild` |
| GlobalAlloc | Mozilla | API designers and allocation wizards |
| Rust VST workshop (audio plugins) | Mozilla | Anyone who is interested in using Rust for audio or art in general 
| auto-Deref & DerefMut in patterns | Mozilla | Trying to implement the ‶future extension″ section of [RFC 2005](https://github.com/rust-lang/rfcs/blob/master/text/2005-match-ergonomics.md) (WIP POC https://github.com/naominitel/rust/tree/match-autoderef) |



## Done

| Who?            | What? |
| --------        | ----- |
| dns2utf8        | https://github.com/RustFestEU/paris.rustfest.eu/pull/57 |
| boxdot + gferon | https://github.com/rust-lang/cargo/pull/5584 |
| killercup       | https://github.com/killercup/quicli (0.3) |
| epage           | Published https://crates.io/crates/escargot |
| hoodie          | https://github.com/kbknapp/clap-rs/issues/965 |
| Doc             | https://github.com/rust-lang-nursery/rust-clippy/pull/2813 |
| Nemo157         | https://github.com/Nemo157/vdom-rsjs |
| apiraino + meven | https://github.com/hyperium/hyper/pull/1524 |
| apiraino + meven | triaged https://github.com/rust-lang-nursery/rustfmt/issues/2743 |
| nercury         | `externalNativeBuild { cargo }` [repo with sample](https://github.com/Nercury/impl-days-android-sample/blob/master/app/build.gradle) progress: cargo plugin options are retrievable |
| zayenz          | https://github.com/rust-lang-nursery/rust-clippy/issues/2812 |
| spacekookie | Published https://crates.io/crates/confy (0.3) | 
| epage       | Published https://crates.io/crates/assert_fs |
| matklad, killercup | https://github.com/rust-lang/cargo/issues/5586 |
| fanzier | https://github.com/rust-lang-nursery/rust-clippy/pull/2811 |
| djc | https://github.com/djc/quinn/issues/7 |
| pacman82 | miri: `u128` as representation of `PatternKind::Range {hi, lo}`.
| Nemo157 | https://github.com/azdle/tokio-coap/pull/2 |
| Nemo157 | https://github.com/Nemo157/coap-browse (well, started) |
| ctz | https://github.com/djc/quinn/pull/19 |
| pierrechevalier83 | https://github.com/kbknapp/clap-rs/pull/1277 |
| pnkfelix | https://github.com/pnkfelix/rust/tree/issue-47184-unzip-types-to-mir-typeck-bindings |
| Emeric | https://github.com/djc/quinn/issues/14 |
| spacekookie + yosh | https://crates.io/crates/human-panic published a ✨ `1.0` ✨  | 
| jvff | Studied Polonius and attempted to write an [initial implementation to condense the CFG](https://github.com/jvff/polonius/compare/master...jvff:condense-cfg) |
| utaal + yati-sagade | Support for [displaying polonius debug output with graphviz](https://github.com/rust-lang-nursery/polonius/issues/12) (Pull request [here](https://github.com/rust-lang-nursery/polonius/pull/63)) |
| rnestler | https://crates.io/crates/lpc11uxx/0.2.0 |
| Aaronepower     | https://github.com/assert-rs/predicates-rs/pull/39 |
| - | [Build a rocket](https://twitter.com/simukis/status/1001122476011802626) |
| pep. | https://github.com/rust-lang/cargo/issues/2527#issuecomment-392552719 |
| epage | published https://crates.io/crates/assert_cmd |
| flaki, badboy, zsuzanna, matt, enrico, emanuel | FOSS conference organisation workshop, findings written down here: https://github.com/rust-community/foss-events-planner/issues | 
| ogham | buncha docs PRs + used crates to make [checkback](https://github.com/ogham/checkback) |
| gferon | https://github.com/rust-lang/cargo/pull/5584 |
| boxdot | https://github.com/rust-lang/cargo/pull/5589 |
| matklad | https://github.com/rust-lang/cargo/pull/5587 |
| killercup | https://crates.io/crates/clap-verbosity-flag |
| zayenz | Initial API-level design review by killercup for planned rust crate |
| hoodie | found and filed an [ICE](https://github.com/rust-lang/rust/issues/51161) |
| zayenz | filed [clippy bug 2818](https://github.com/rust-lang-nursery/rust-clippy/issues/2818) and [clippy pull request 2819](https://github.com/rust-lang-nursery/rust-clippy/pull/2819) |
| zayenz | [WIP PR for clap-rs clippy cleanups](https://github.com/kbknapp/clap-rs/pull/1278) |
|@Amanieu + @SimonSapin | Incremental progress on `GlobalAlloc` https://github.com/rust-lang/rust/issues/49668 |
| pftbest | Uncovered LLVM bug https://bugs.llvm.org/show_bug.cgi?id=37618 |
|Lamb|Learning about the contribution process and how to work on the compiler by working on this issue https://github.com/rust-lang/rust/issues/50974|
| zayenz | [PR for compilation error in clap](https://github.com/kbknapp/clap-rs/pull/1279) |
| vakaras | [PR for NLL issue 50716](https://github.com/rust-lang/rust/pull/51139) |
| japaric | Gave away 2 STM32F3DISCOVERY boards and had 4 newbies to embedded and/or embedded Rust work through the [Discovery book](https://japaric.github.io/discovery/) to learn some embedded Rust |
| japaric | Resumed work on the [#[panic_implementation] PR](https://github.com/rust-lang/rust/pull/50338) |


# messages

(post your questions/comments here)

Someone proposed a pattern matching improvement (extending https://github.com/rust-lang/rfcs/blob/master/text/2005-match-ergonomics.md) using Deref/DerefMut. As I have this idea since a long time, I'd like to talk with the person that proposed this subject. I'm Guillaume P. (TeXitoi everywhere), Mozilla, CLI table (the middle one), red shirt.

@meven and @apiraino tried to work on some "good first issues" on the `rustfmt` project, but we were kind of put back because we couldn't easily get to compile it against rust nightly (probably due to the latest `rustfmt` library updates)
