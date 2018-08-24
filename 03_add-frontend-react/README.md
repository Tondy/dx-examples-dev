# Example 03: Build a React frontend to interface the DutchX contracts
This project is an example that shows how to create a React frontend project 
that depend on the DutchX and how you can deploy the DutchX contracts in a 
`ganache-cli` local node.

> This example is part of the guide http://dutchx.readthedocs.io/en/latest/
>
> You can find other examples in the [Build on top of DutchX project](https://github.com/gnosis/dx-examples-dev)

## High level recommendations
1. Install and familiarise yourself with [MetaMask](https://metamask.io)
2. For React development, [React Dev-Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en) is highly recommended
3. Testing Solidity contract methods can be tricky without the proper environment. Please check out and add the awesome [DutchX CLI](https://github.com/gnosis/dx-examples-cli) to your arsenal. `truffle console` is also very handy!

----------------------------------

## Initial setup and starting the app locally
First you'll need to grab the project!
```bash
mkdir dx-dapp-project && cd dx-dapp-project
git clone https://github.com/gnosis/dx-examples-dev.git .

# dont forget to head into 03_add-frontend-react now!!

# install the deps, yo
npm install

# start ganache rpc!
npm run rpc

# (in another tab) migrate the contracts ... woo boy
# check out the ganache tab while it migrates O_O
npm run migrate

# and fiiinally, start the thing
# head to localhost:8080 and admire
npm start
```

## Next steps
Congratulations! you now have a working React frontend-truffle project that deploys all the DutchX contracts as 
part of it's first migration and can talk to them - doooope.

That's it for now! Please check back in every now and again and check for updates :) Thanks so much for stopping by and giving all this a go!

Happy buidling