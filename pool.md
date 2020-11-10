# POOL

POOL is *the* application for managing all your money. **ALL OF IT!**

Money is managed through a system of *pools* and *streams*. A user will also be given their own person POOL debit card which is used to pull money from any of their *pools* they choose through the POOL app.

## Pools? Streams?
Don't worry, it gets better.

### Pools
A *pool* is the *only* place where money can be **stored**. The amount stored is referred to as the *reserve*. A user many create any number of *pools* and are encouraged to do so in order to customize POOL to fit their need.

### Streams
A *stream* connects two *pools*. A *stream* is **unidirectional** which means that there is always a defined *pullPool* and a *pushPool*. Thus, a *stream* enables money to be moved from the *pullPool* to the *pushPool* and **only** in that direction.

A *stream* contains configurations for *pulling* and *pushing*. These configurations enable the user to create POOL systems that are consistent and safe even when a *drop* requires pulling from other *pools*.

### Drains
A *drain* is simply a special type of *pool* that does not allow *pushes* and does not keep a *reserve*. It implements the POOL debit card.

### Tanks
A *tank* is simply a special type of *pool* that does not allow *pulls* and has an unlimited *reserve*. It implements a bank account or any outside source of money.

### Drops
A *drop* is a change in a *pool* due to a *pull* or a *push* request on that *pool*. A *drop* is initiated by the *pool* which, if needed, will create *drops* through its *pullers* or *pushers* *streams*.

### Flow
The collection of *drops* created by a single *pull* or *push* request is referred to as a *flow*.


## So What?
The possibilities are endless...