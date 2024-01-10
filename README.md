# Solana TX Data Extract Code Challenge

 ## Challenge Description

Your challenge is to create a simple application implemented in language of your choice that will interact with the Solana blockchain, to fetch transactions data from the [Phoenix on-chain orderbook DEX](https://www.phoenix.trade/) program, decode the transactions, extract the trade fill events that have happened in the last 1k transactions, and store them in format of your choice (CSV, JSON, etc.).

**RPC API & Resources**

Visit [Helius Dev Portal](https://dev.helius.xyz/dashboard/app), login in with your preferred method to retrieve your free API key, and set this as an environment variable in your app. 

Now, you should be able to use `https://rpc.helius.xyz/?api-key=${YOUR_API_KEY}` to fetch data from this RPC endpoint. There is a 25 RPC request per second rate limit.

Starting off with the [getSignaturesForAddress](https://docs.solana.com/api/http#getsignaturesforaddress) method, you can get a list of TX signatures for the Phoenix DEX Program, and work through with decoding the transactions to extract trade fill events

The [Phoenix SDK repo](https://github.com/Ellipsis-Labs/phoenix-sdk/tree/master) should help you to make sense of their data and logic and identify what you need to extract and store.

**Testing (Nice to have, not a requirement)**

The application should include a basic suite of tests, at least covering the crucial functionality.

100% code coverage isn't expected.

**Development and Build Environment**

Your application should have a fully working development environment. Instructions should be provided on how to run the application in a development setting.

**Submission Guidelines**

Please submit your code in a GitHub repository. It should include:

1. Source code.
2. Test files. (nice to have)
3. A README file containing instructions on how to set up and run your application, including installing dependencies, running tests, starting the development server.
4. The file that contains the trade fills data.
5. Any additional documentation you feel necessary to understand your assumptions, architecture design, and development decisions.

We expect this assignment to take around 4 hours to complete, please inform us if you find that you are spending a lot more time than that.

Finally, just to reiterate, we're not just looking at if the final product works, but also your approach, code quality, choice of libraries, and general adherence to best practices. Good luck!
