# [Migrating to TypeScript](https://stripe.com/blog/migrating-to-typescript)

Andrew Lunny, a frontend engineer at Stripe, details Stripe’s remarkable achievement in migrating their largest JavaScript codebase – totaling 3.7 million lines of code – from Flow to TypeScript in a single pull request. Lunny highlights Stripe’s initial embrace and early adoption of Flow in 2016 to address the need for increased quality and reliability, but acknowledges issues while working with Flow, citing slow and unreliable in-editor integration compared to alternative type systems such as Typescript. 

Recognizing the company’s evolving needs, Lunny delves into the meticulous planning, preparation, and iterative approach taken during their migration, including the contemplation between various migration strategies and the use of Airtable’s source-to-source conversion tool, [_codemod_](https://github.com/Airtable/typescript-migration-codemod). Despite providing a tangible improvement over more traditional methods, _codemod_ was not comprehensive and required some edge case handling. Ultimately, the successful deployment and the overwhelmingly positive response from engineers – one describing the process as “the single biggest developer productivity boost in their time at Stripe” – underscores the effectiveness of the migration. 

Stripe’s achievement offers a valuable case study on executing large-scale codebase migrations and highlights the importance of listening to feedback from engineers and community collaboration.

## Comments