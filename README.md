# Mediator pattenr with typescript

## Description

Mediator pattern is used where many objects (Colleagues) have to interact with one another. Mediator in this case serves as a "mediator": Colleagues don't deal with each other anymore. Instead, they deal with the Mediator all the time. It allowes more flexibility by decoupling the Colleagues. Often this pattern is implemented as "publish/subscribe" system. Mediator represents a central hub that subscribe Colleagues for corresponding events and fires the events.

