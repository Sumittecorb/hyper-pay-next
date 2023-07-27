## Hyperpay integration Introdution
 * To start hyper pay payment gateway there is no third party integration.
 * Here we need card entity id like visa entity id or mada card entity id
 * Hyper provide Card widget to enter card details if add new card
 * Hyper provide Card widget to enter card cvv if we do payment with save card
 * Hyper pay provide api to verify payment

## Testing test card and api and payment widget card



- [hyperPay](https://eu-prod.oppwa.com/v1/paymentWidgets.js) – Payment Widget -[hyperPay](https://eu-prod.oppwa.com) – Verify payment of testing card

## Testing live card api and payment widget card

- [hyperPay](https://test.oppwa.com/v1/paymentWidgets.js) – Payment Widget -[hyperPay](https://test.oppwa.com) – Verify payment of testing card

## Payment with new card

* We do payment with new card and also with saved card list
* If we do payment with add new card then pls check code of root file app.tsx
all instruction are there.

## saved card payment

* When we do payment with save card then the process is same
* Firstly genrate checkout id from select card
* Then behalf of that render the card widget where we enter only cvv no.
* And then process is same as

### Frameworks

- [Next.js](https://nextjs.org/) – React framework for building performant apps with the best developer experience
- [Node.js](https://authjs.dev/) – Handle user authentication with ease with providers like Google, Twitter, GitHub, etc.

### Code Quality

- [TypeScript](https://www.typescriptlang.org/) – Static type checker for end-to-end typesafety
- [Prettier](https://prettier.io/) – Opinionated code formatter for consistent code style
- [ESLint](https://eslint.org/) – Pluggable linter for Next.js and TypeScript
