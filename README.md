## Hyperpay integration Introdution

1- To start hyper pay payment gateway there is no third party integration.
2- here we need card entity id like visa entity id or mada card entity id
3- hyper provide Card widget to enter card details if add new card
4- hyper provide Card widget to enter card cvv if we do payment with save card
5- hyper pay provide api to verify payment

## Testing test card and api and payment widget card

- [hyperPay](https://eu-prod.oppwa.com/v1/paymentWidgets.js) – Payment Widget -[hyperPay](https://eu-prod.oppwa.com) – Verify payment of testing card

## Testing live card api and payment widget card

- [hyperPay](https://test.oppwa.com/v1/paymentWidgets.js) – Payment Widget -[hyperPay](https://test.oppwa.com) – Verify payment of testing card

## Payment with new card

1- we do payment with new card and also with saved card list
2- if we do payment with add new card then pls check code of root file app.tsx
all instruction are there.

## saved card payment

1- when we do payment with save card then the process is same
2- firstly genrate checkout id from select card
3- then behalf of that render the card widget where we enter only cvv no.
4- and then process is same as

### Frameworks

- [Next.js](https://nextjs.org/) – React framework for building performant apps with the best developer experience
- [Node.js](https://authjs.dev/) – Handle user authentication with ease with providers like Google, Twitter, GitHub, etc.

### Code Quality

- [TypeScript](https://www.typescriptlang.org/) – Static type checker for end-to-end typesafety
- [Prettier](https://prettier.io/) – Opinionated code formatter for consistent code style
- [ESLint](https://eslint.org/) – Pluggable linter for Next.js and TypeScript
