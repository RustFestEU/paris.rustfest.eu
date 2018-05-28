# RustFest 2018 impl days project list

**This url is: https://bit.ly/impldays**

Adresses:

* Mozilla: 16bis Boulevard Montmartre, 75009 Paris (https://goo.gl/maps/VNEL8yGFerQ2)
* Formeret Espace Clery: 17, rue de Cléry, 75002 Paris (https://goo.gl/maps/4G6eUFvoYqR2)

# Monday, May 28th

## Currently running

Don't break the table plz :( :laughing:

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
| Nemo157         | https://github.com/Nemo157/vdom-rsjs |
|apiraino + meven | https://github.com/hyperium/hyper/pull/1524 |
| nercury         | `externalNativeBuild { cargo }` progress: dsl syntax works but does nothing |
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
| jvff | Studied Polonius and attempted to write an [initial CFG condensation implementation](https://github.com/jvff/polonius/compare/master...jvff:condense-cfg) |
| utaal + yati-sagade | Progress with [displaying polonius debug output with graphviz](https://github.com/rust-lang-nursery/polonius/issues/12) |
| rnestler | https://crates.io/crates/lpc11uxx/0.2.0 |
| Aaronepower     | https://github.com/assert-rs/predicates-rs/pull/39 |
| - | [Build a rocket](https://twitter.com/simukis/status/1001122476011802626) |
| pep. | https://github.com/rust-lang/cargo/issues/2527#issuecomment-392552719 |
| epage | published https://crates.io/crates/assert_cmd |

# realtime data

## mozilla fill status

0 of 55

## Formeret Espace Cléry fill status

0 of 100

# messages

(post your questions/comments here)

Someone proposed a pattern matching improvement (extending https://github.com/rust-lang/rfcs/blob/master/text/2005-match-ergonomics.md) using Deref/DerefMut. As I have this idea since a long time, I'd like to talk with the person that proposed this subject. I'm Guillaume P. (TeXitoi everywhere), Mozilla, CLI table (the middle one), red shirt.

@meven and @apiraino tried to work on some "good first issues" on the `rustfmt` project, but we were kind of put back because we couldn't easily get to compile it against rust nightly (probably due to the latest `rustfmt` library updates)
