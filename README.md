## Trong Tu Luu

Software engineer and product designer in London. I design things and then build them, which means the interface decisions and the engineering decisions end up being the same decisions.

Three products are live. The one worth your time is **[Badminton Queue](https://github.com/Tuu01/badclub_queue)**: a session manager for a badminton club that decides who plays next and explains why in one sentence. There is a [live demo](https://vlong.tuuhyped.co.uk) you can sign into with a published demo code and run a court yourself.

If you only read one thing in it, read how the writes work. The whole live session is a single document, so allocating a court is one transaction and the losing write throws a conflict rather than putting a player on two courts at once; there is a test that fires both writes concurrently and asserts exactly one wins. The engine, the rating and the domain types are a pure core with the clock and randomness injected, sitting behind a repository interface with real and in-memory implementations, which is why 121 tests run offline with no credentials and no network.

Before any of this I spent six years running the booking and payment operations of a two-location salon, and was then paid to build the platform that replaced the paper process. That is still the most useful thing about how I work: I have been on the other side of software that did not fit the job.

**Currently:** finishing an MSc in Computer Science at Queen Mary, and looking for a first role in London where design and engineering are not separate teams.

- Portfolio: [tuuhyped.co.uk](https://tuuhyped.co.uk)
- Live booking platform: [nailfairy.co.uk](https://nailfairy.co.uk)
- Stack: TypeScript, React, Next.js, Node, Firestore, Figma
