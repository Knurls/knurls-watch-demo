# Vertical: Luxury Watches
It is critically important to capture both the entities and the actions that makeup this ecosystem. 

To that end, we have attempted to capture - at a high level - those **participants**, **assets**, **transactions**, and **events** below, with sub-classes where appropriate.

**Participants** | *Entities that act on **Assets** through **Events** or **Transactions***
`Manufacturer` *the originator of the **Asset** in question*
`Retailer` *the authorized first-party seller of the **Asset***
`Customer` *the buyer of the **Asset** from the `Retailer`*
`Appraiser` *a third-party value assessor who is neither the `Manufacturer`, `Retailer`,or `Customer`
`Servicer` *a third-party service provider who initiates a `Service` **Event** on an **Asset***
`Customizer` *a third-party service provider who initiates a `Modification` **Event** on an **Asset***
`Auctioneer` *a third-party facilitator of a **Transaction** of an **Asset** who is not acting as a `Retailer`*
`Media` *a third-party who creates content about any other entity in the ecosystem*
`Insurer` *a third-party who insures the value of an **Asset** for another **Participant***

**Assets** | *Individual elements that impacted by **Participants** through **Events** or **Transactions***
`Watch` *the assembled timepiece in its completed state*
`OEM Watch Components` *individual components comprising a piece of a whole timepiece - such as movement, case, etc.*
`Custom Watch Components` *customizing luxury watches - or "modding" - is common and custom parts should be treated separately*
`Straps` *additional straps in a variety of materials are typically included with luxury watches*
`Case` *many luxury watches arrive with travel cases, could be original packaging, as well*
`Winder` *automatic watches require movement to stay powered, and external winders are often used to keep unworn watches from running out of power reserve*
`Accessory` *additional accessories - whether OEM or third-party - can be added to expand the **Asset** subclass*

**Transaction** | *Transactions are events that changes the ownership status of an **Asset***
`Manufacture` *the **Asset** is created and capture on the blockchain*
`Distribute` *the **Asset** is transferred from the manufacturer to the retailer*
`Sale` *the **Asset** is sold by a `Retailer` to a `Customer`
`Transfer` *the **Asset** ownership is otherwise transferred (gifted, inherited, auctioned, private party, etc.)*

**Event** | *Events that change ownership status of an **Asset** are classified as a **Transaction***
`Service` *routine service is important to keep the **Asset** in good working order*
`Modification` *modifications can add or detract from the value of an **Asset***
`Damage` *an incident impacting the value, physical, or operational characteristics of an **Asset** above and beyond normal wear and tear*
`Loss` *the failure to keep or retain control of an **Asset***
`Destruction` *an incident that eliminates any remaining value or function of an **Asset***
