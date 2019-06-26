Title: This Week in Rust 292
Number: 292
Date: 2019-06-25
Category: This Week in Rust

Hello and welcome to another issue of *This Week in Rust*!
[Rust](http://rust-lang.org) is a systems language pursuing the trifecta: safety, concurrency, and speed.
This is a weekly summary of its progress and community.
Want something mentioned? Tweet us at [@ThisWeekInRust](https://twitter.com/ThisWeekInRust) or [send us a pull request](https://github.com/cmr/this-week-in-rust).
Want to get involved? [We love contributions](https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md).

*This Week in Rust* is openly developed [on GitHub](https://github.com/cmr/this-week-in-rust).
If you find any errors in this week's issue, [please submit a PR](https://github.com/cmr/this-week-in-rust/pulls).

# Updates from Rust Community

## News & Blog Posts

* [Rust for closed-source projects](https://ntcore.com/?p=641)

# Crate of the Week

This week's crate is [winit](https://github.com/rust-windowing/winit), a pure-rust cross-platform window initialization library. Thanks to [Osspial](https://users.rust-lang.org/t/crate-of-the-week/2704/572) for the suggestion!

[Submit your suggestions and votes for next week][submit_crate]!

[submit_crate]: https://users.rust-lang.org/t/crate-of-the-week/2704

# Call for Participation

Always wanted to contribute to open-source projects but didn't know where to start?
Every week we highlight some tasks from the Rust community for you to pick and get started!

Some of these tasks may also have mentors available, visit the task page for more information.

* [Final async/await testing push](https://internals.rust-lang.org/t/final-async-await-testing-push/10423).
* [Rubble: Help wanted solving our BLE stack problem](https://mckeogh.tech/help-wanted-ble/). Rubble is a Bluetooth Low Energy compatible protocol stack for embedded Rust.
* [contrie: Rayon support: FromParallelIterator & ParallelExtend](https://github.com/vorner/contrie/issues/3). ConTrie is a concurrent hash-trie map & set.
* [Request for implementation](https://github.com/dtolnay/request-for-implementation/) - Crates that don't exist but should. Suggest your own design and someone will pick it up. 

If you are a Rust project owner and are looking for contributors, please submit tasks [here][guidelines].

[guidelines]: https://users.rust-lang.org/t/twir-call-for-participation/4821

# Updates from Rust Core

205 pull requests were [merged in the last week][merged]

[merged]: https://github.com/search?q=is%3Apr+org%3Arust-lang+is%3Amerged+merged%3A2019-06-10..2019-06-17

* [Introduce `Let(..)` in AST, remove `IfLet` + `WhileLet` and parse let chains](https://github.com/rust-lang/rust/pull/60861)
* [Support `cfg` and `cfg_attr` on generic parameters](https://github.com/rust-lang/rust/pull/61547)
* [librustc_data_structures: Speedup union of sparse and dense hybrid set](https://github.com/rust-lang/rust/pull/61020)
* [Refactor miri pointer checks](https://github.com/rust-lang/rust/pull/62081)
* [Help LLVM better optimize `slice::Iter`(`Mut`)`::len`](https://github.com/rust-lang/rust/pull/61885)
* [Remove the default type of `Rem::Output`](https://github.com/rust-lang/rust/pull/61874)
* [Make use of `ptr::null`(`_mut`) instead of casting zero](https://github.com/rust-lang/rust/pull/61864)
* [Make `MaybeUninit` `#[repr(transparent)]`](https://github.com/rust-lang/rust/pull/61802)
* [Implement `nth_back` for `slice::`{`Iter`, `IterMut`}](https://github.com/rust-lang/rust/pull/60772)
* [Add custom `nth_back` to `Skip`](https://github.com/rust-lang/rust/pull/60454)
* [Add functions for building raw slices to libcore](https://github.com/rust-lang/rust/pull/60667)
* [rustdoc: Only show methods that appear in `impl` blocks in the Implementors sections of trait doc pages](https://github.com/rust-lang/rust/pull/61505)
* [rustdoc: Generate implementors for all auto traits](https://github.com/rust-lang/rust/pull/60293)

## Approved RFCs

Changes to Rust follow the Rust [RFC (request for comments)
process](https://github.com/rust-lang/rfcs#rust-rfcs). These
are the RFCs that were approved for implementation this week:

*No RFCs were approved this week.*

## Final Comment Period

Every week [the team](https://www.rust-lang.org/team.html) announces the
'final comment period' for RFCs and key PRs which are reaching a
decision. Express your opinions now.

### [RFCs](https://github.com/rust-lang/rfcs/labels/final-comment-period)

*No RFCs are currently in final comment period.*

### [Tracking Issues & PRs](https://github.com/rust-lang/rust/labels/final-comment-period)

*No issues are currently in final comment period.*

## New RFCs

*No new RFCs were proposed this week.*

# Upcoming Events

### Africa

* [Jul  3. Johannesburg, ZA - Johannesburg Rust Meetup - informal discussions on topics related to the language](https://www.meetup.com/Johannesburg-Rust-Meetup/events/dgqmbryzkbfb/).

### Asia Pacific

* [Jun 24. Sydney, AU - Rust Sydney - Meetup 17](https://www.meetup.com/Rust-Sydney/events/262194894/).
* [Jun 25. Seoul, KR - Seoul Rust Meetup, Hapjeong - Deep dive into Rusts standard library](https://www.meetup.com/Rust-Seoul-Meetup/events/srxvzqyzjbhc/).
* [Jun 29. Taipei, TW - Rust Taiwan Meetup](https://www.facebook.com/events/2824830874225735/).
* [Jul  1. Auckland, NZ - Rust AKL - WASM - Implementing a scalable omiscient debugger in Rust](https://www.meetup.com/rust-akl/events/259480968/).
* [Jul  7. Tokyo, JP - Tokyo Rust Meetup - Rust LT #6](https://rust.connpass.com/event/133657/).

### Europe

* [Jun 26. Berlin, DE - OpenTechSchool Berlin - Rust Hack and Learn](https://www.meetup.com/opentechschool-berlin/events/gkkttqyzjbjc/).
* [Jun 26. Milano, IT - Rust Language Milano - Fun with Rusty Robots](https://www.meetup.com/rust-language-milano/events/262155219).
* [Jun 28-29. Firenze, IT - RustLab 2019](https://www.rustlab.it/).

### North America

* [Jun 24. Durham, NC, US - Triangle Rustaceans - Project Night & Lightning Talks](https://www.meetup.com/triangle-rustaceans/events/mfglwpyzjbgc/).
* [Jun 25. Dallas, TX, US - Dallas Rust - Last Tuesday](https://www.meetup.com/Dallas-Rust/events/zfgwzmyzjbhc/).
* [Jun 26. Ann Arbor, US - Ann Arbor Rust Meetup - Monthly Gathering](https://www.meetup.com/Ann-Arbor-Rust-Meetup/events/vsncvqyzjbjc/).
* [Jun 26. Vancouver, BC, CA - Vancouver Rust meetup](https://www.meetup.com/Vancouver-Rust/events/fzqqwqyzjbjc/).
* [Jul  3. Atlanta, GA, US - Grab a beer with fellow Rustaceans](https://www.meetup.com/Rust-ATL/events/kkzkxqyzkbfb/).
* [Jul  3. Indianapolis, IN, US - Indy.rs](https://www.meetup.com/indyrs/events/mffbtpyzkbfb/).

If you are running a Rust event please add it to the [calendar] to get
it mentioned here. Please remember to add a link to the event too.
Email the [Rust Community Team][community] for access.

[calendar]: https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com
[community]: mailto:community-team@rust-lang.org

# Rust Jobs

* [Blockchain Runtime Engineer at Parity, Berlin, DE or remote](https://www.parity.io/jobs/#berlin-blockchain-runtime-engineer).

*Tweet us at [@ThisWeekInRust](https://twitter.com/ThisWeekInRust) to get your job offers listed here!*

# Quote of the Week

> why doesn't 'static, the largest lifetime, not simply eat all the others

– [@mountain_ghosts on twitter](https://twitter.com/mountain_ghosts/status/1133406976002674688?s=09)

> @mountain_ghosts 'static is biggest but actually,, weakest of lifetimes, becuase it is subtype of every lifetime
>
> 'static is big soft friend
>
> pls love and protect it

– [@gankro on twitter](https://twitter.com/Gankro/status/1133435497806815232?s=09)

Thanks to [Christopher Durham](https://users.rust-lang.org/t/twir-quote-of-the-week/328/654) for the suggestion!

[Please submit quotes and vote for next week!](https://users.rust-lang.org/t/twir-quote-of-the-week/328)

*This Week in Rust is edited by: [nasa42](https://github.com/nasa42), [llogiq](https://github.com/llogiq), and [Flavsditz](https://github.com/Flavsditz).*

<small>[Discuss on r/rust]().</small>