# iv4xr PROJECT

[this README is being worked on]

The _iv4xr Framework_ is an agent-based framework for automated testing highly interactive systems such as computer games or computer simulators. Its cool features include intelligent agents, player experience testing, and integration with other tools such as Model based Testing (MBT) and TESTAR.

Although above we mention "games", iv4xr itself is generic enough to target other types of interactive systems, even services or Java classes as long as these entities can be viewed as interactable systems.

Iv4xr is a _framework_ because it is not a tool that can immediately do its work out of the box. This is not possible due to the unstandardized domains of its targets; e.g. there is no uniform way to interface with computer games, and there is no uniform representation of their states either. So before it can be used, iv4xr Framework requires an interface to be built that would allow it to control and observe the target system under test (SUT).
