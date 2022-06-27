# supermarket-oop
Write all your `.ts` files inside `src` directory.

## How to run
1. clone or download this repo
2. in cmd run the command `npm install`
3. execute tests with the command `npm run test`

## Tests
run test with `npm run test` command

## Classes:
- `CashRegister` (`cashId`, `products: Product[]`, `worker: StaffMember`)
  - `private static cashIdCounter: number = 1;`
- `Consumer` (`isClubMember`)
- `Person` (`firstName`)
- `Product` (`price`, `name`, `brand`, `barcode`)
- `StaffMember` (`role`)

### Class Logic
#### CashRegister
Every cash machine has unique id (`cashId` property), and the machine unique id assiged when you contruct the `CashRegister` object. assign the `cashIdCounter` static property to `cashId` and increment `cashIdCounter` by 1.

you can use `map` and `reduce` inside the function `endPurchase` to calculate the total.

## Inheritance:
`StaffMember` and `Consumer` inherit `Person`

 cashId: number;
    products?: Product[];
    ;
