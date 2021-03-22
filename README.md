# GFTP-Loyalty-Program
The GFTP loyalty program allows companies to reward customers. Program members are able to convert their points to tokens and then redeem their tokens at any participating merchants. It can have multiple companies as partners or merchants on the program. Current loyalty program systems are restraint on relations between partners, and with visibility to members. These restraints can be removed by creating the GFTP loyalty program on a blockchain network.

The blockchain model for the GFTP loyalty program enhances the value of tokens to members and brings in new value to the partners or merchants by creating trusted transactions. Participants in this network have a more level relation among each other and tokens are in the centric position to connect all participants.

In this sample code, we will create a GFTP loyalty program as a blockchain web application using Hyperledger Fabric and Node.js. The application will allow members to register on the network where they will create their account. They will be identified on the network with their account number and will create an access key which they will use to sign in. This access key is used as the card id for the member to make transactions and query records. The member once signed in, can make transactions to redeem tokens from the merchants on the network. They can view their transactions as part of the blockchain ledger. The code illustrates the use of permissions as part of the network where a member can only view their transactions.

Similarly for the partner or merchant, they will register by creating an identity on the network and an access key which will be used to view their records. Partners or merchants are allowed to view only transactions they were part of, and thus can keep track of all their transactions of redeemed tokens. The web application shows a basic dashboard for the partner/merchant displaying the total tokens that was redeemed by members. As transactions get complex, the partner/merchant can perform analysis on their transactions to create informative dashboards.


## License
This code pattern is licensed under the Apache Software License, Version 2. Separate third-party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses. Contributions are subject to the [Developer Certificate of Origin, Version 1.1 (DCO)](https://developercertificate.org/) and the [Apache Software License, Version 2](https://www.apache.org/licenses/LICENSE-2.0.txt).

[Apache Software License (ASL) FAQ](https://www.apache.org/foundation/license-faq.html#WhatDoesItMEAN)
