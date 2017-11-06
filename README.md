# Hello World Dapp

Simple voting dapp based on [Mahesh Murthy's Medium article](https://medium.com/@mvmurthy/full-stack-hello-world-voting-ethereum-dapp-tutorial-part-1-40d2d0d807c2)

This updates his tutorial with new web3 1.X bindings, and packages the tutorial for easy installation.

### Installation and Usage

Clone repository and run
```
npm install
```
Then launch the testpc server with
```
npm run testrpc
```
and from a separate shell
```
npm run http_server
```

Then point your browser to `http://localhost:8000` for the web version of the voting app.

The `server.js` file includes the VotingContract setup and deployment. For comparision you should be able to follow the original tutorial to get an idea of what was changed from the pre 1.0 `web3` to the 1.0 `web3` bindings.
