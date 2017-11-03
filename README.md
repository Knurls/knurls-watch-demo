# Knurls knurls-watch-demo Documentation

> This documentation is adapted from the basic "Hello World" of Hyperledger Composer samples, which demonstrates the core functionality of Hyperledger Composer by changing the value of an asset. In a more advanced version of the demo, the ownership of the asset would also be tracked, as well as interactions of **participants** upon **assets**, in addition to ownership status.

This demo defines the following entities and interactions:

**Participant**
`SampleParticipant`

**Asset**
`SampleAsset`

**Transaction**
`SampleTransaction`

**Event**
`SampleEvent`

I created some sample participants, including Manufacturer, Retailer, Buyer, Servicer:

[![Sample Participants](https://cdn.pbrd.co/images/GRWLM9m.png)](https://cdn.pbrd.co/images/GRWLM9m.png)

The transactions can be viewed in the Historian, including their creation and their interaction:

[![Transactions Viewed in Historian](https://cdn.pbrd.co/images/GRWN97w.png)](https://cdn.pbrd.co/images/GRWN97w.png)

The transactions are recorded to the blockchain with both a Transaction ID and a timestamp:

[![Individual Transaction](https://cdn.pbrd.co/images/GRWNECK.png)](https://cdn.pbrd.co/images/GRWNECK.png)

In the future, more complex interactions can be captured, as I mentioned above - participants upon individual assets, such as Manufacturer creates Watch, Manufacturer ships Watch to Retailer, Retailer sells Watch to Customer, Customer has Watch serviced by Servicer, Servicer services Watch component X, etc.
