# interview-task-3dnG

## After cloning the repository:

-   Install packages by running `npm install` or `pnpm install`.

## Task Description

There is a store object factory in `./src/todo.mts` which has the following methods on it:

-   `getProfileForUser`
-   `getTransactionsForUser`
-   `getAccountBalanceOfUser`
-   `getFullUserProfile`
-   `getUserWithLargestAccountBalance`
-   `getUserWithSmallestAccountBalance`
-   `getUserWithSmallestPositiveAccountBalance`
-   `getUserWithLargestNegativeAccountBalance`

You task is to implement all of these methods. The `./src/todo.mts` file is also the only file you should modify as part of this task. The store has the following variables with data in scope that you should source the data from: `users`, `userProfiles`, `userTransactions`. You can create more variables for the data if needed for example to transform the data into a different data structure or format. Don't change the definitions or data in the aforementioned variables unless the task description explicitly asks you to do so.

Inside `./src/todo.mts` you will also find `task` function which is being passed the store object that you're working on. After you implement the `getProfileForUser` method you can comment out the line that calls this method and uncomment the next line that calls `getTransactionsForUser` and so on so we always call one method at a time. This is necessary because we want to benchmark the execution time of each method separately.
/todo.mts you will also find task function which is being passed the store object that you're working on. After you implement the getProfileForUser method you can comment out the line that calls this method and uncomment the next line that calls getTransactionsForUser and so on so we always call one method at a time. This is necessary because we want to benchmark the execution time of each method separately.