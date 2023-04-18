# Eppie

Eppie is an open protocol encrypted p2p email. The idea is to create an easy to use tool for communication and identity management with full account ownership.

At the moment Eppie stores the data using [IPFS](https://github.com/ipfs/ipfs) infrastructure, and the transport layer works through [SBBS](https://github.com/BeamMW/beam/wiki/Secure-bulletin-board-system-(SBBS)). But the architecture allows to easily add new storage and transport technologies. Eppie’s e2e encryption is based on Elliptic-curve cryptography. The application is being written in C# with [Uno](https://github.com/unoplatform/uno) and targets multiple platforms.
