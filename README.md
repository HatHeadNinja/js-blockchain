# Super simple, standalone blockchain built for learning.

main.js is a testing file, which creates the blockchain, mines pending transactions, adds pending transactions and rewards miners.

blockchain.js holds most of the blockchain code. There is wallet.js, which really should be incorporated into blockchain.js (DRY!)

I used classes as an experiment but will rewrite with functional programming, It definitely makes it simple to use in an interface as an object but it is unnecessarily complex. Several times I tripped over using, or not using, a 'this' and spending time debugging. Debugging takes longer too, as there is more code overall when using a class in this project.

I also have technical questions around how/when pending transactions are managed to avoid double spending and how perhaps multiple blockchains might be supported, at least in my model.

Other learning experiments to include different consensus mechanisims.

I am going to start a new project and put a front-end to this learning experience.
