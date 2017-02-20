# Interoperability
The goal is to make all the MAN software interoperable, using [ValueFlows](https://github.com/valueflows/valueflows) vocabulary. The MAN software includes:
* Mutual Aid Platform (MAP) - Python / Odoo
* Dane County Time Bank - Community Forge - Drupal
* Locecon resource flow mapping - Python / Django - lower priority
* Poshterity - future
* Common Fund - future

This will involve 
* Determining the detailed requirements in terms of functionality and user experience
* Determining the technical architecture (for example, do we want to write a separate piece(s) of software that sits on top of the existing pieces; or make the MAP the center; etc.)
* Detailed data mapping between the existing software and with ValueFlows.
* Write APIs in each piece of software
* Write and test new software and/or enhance existing software to aggregate and unify the information, including UI.

The initial high-level requirements are:
* Aggregate an individual’s or group’s account from different exchange systems
* Ability to show listings by geography (local + global, etc)
* Different instances in the MAP interacting - showing offers, requests, account info between
* Listings showing in more than 1 system (between different software systems)
* Visible interface between value flow maps and MAP accounts
* Visible interface between poshterity budget and MAP accounts - including showing budget progress on various items (like yesmen action module, that shows progress bars)
* Communications and work tools - best functionality for best use at best time (etherpad, email threads, google docs)
* MAP projects will operate in exchanges



