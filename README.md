# JavaScript Conditional Statements and Loops

This project contains solutions to four basic JavaScript tasks focused on
working with conditional statements and loops.

## Project Structure

```
├── js/
│ ├── task-1.js
│ ├── task-2.js
│ └── task-3.js
│ └── task-3.js
│ └── task-4.js
├── index.html
├── .gitignore
├── .prettierrc
└── README.md
```

## Tasks

### Task 1 — Droid Order

File:[js/task-1.js](./js/task-1.js)

Function `makeTransaction(quantity, pricePerDroid, customerCredits)` implements
calculation of the total cost of ordering droids.  
Returns a success message with the order details if the customer has enough
credits, or `"Insufficient funds!"` otherwise.

Example:

`makeTransaction(5, 3000, 23000) // "You ordered 5 droids worth 15000 credits!"`

### Task 2 — Message Formatting

File:[js/task-2.js](./js/task-2.js)

Function `formatMessage(message, maxLength)` implements checking a string's
length against a maximum.  
Returns the original string if it fits within `maxLength`, or a version
truncated to `maxLength` characters with `"..."` appended if it exceeds the
limit.

Example:

`formatMessage('Curabitur ligula sapien', 16) // "Curabitur ligula..."`

### Task 3 — Spam Check

File:[js/task-3.js](./js/task-3.js)

Function `checkForSpam(message)` implements checking whether a string contains
the forbidden words `spam` or `sale` (case-insensitive).  
Returns `true` if a forbidden word is found, `false` otherwise.

Example:

`checkForSpam('Latest technology news') // false`

### Task 4 — Shipping Cost

File:[js/task-4.js](./js/task-4.js)

Function `getShippingCost(country)` implements using a `switch` statement to
return the shipping cost message for supported countries (China — 100, Chile —
250, Australia — 170, Jamaica — 120 credits).  
Returns `"Sorry, there is no delivery to your country"` for unsupported
destinations.

Example:

`getShippingCost('Australia') // "Shipping to Australia will cost 170 credits"`
