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

Here are some documents that were done earlier. 
* [Existing categories for marketplace](https://docs.google.com/presentation/d/1GURT08liVTBkGvN0ah6-1tMLDwKC2G0PNZNSZASMDic/edit?usp=sharing)
* [Start of a plan for the interoperability](https://docs.google.com/document/d/14hER3Gqkf1cbQkuMjVshbZF5CtSs5zacJMuen37EHkY/edit?usp=sharing)
* [Notes in diagram form of what might need to be interoperable, really old now](https://docs.google.com/drawings/d/1Bcu0wHJoYJy6HQI1qJsnuHgMkFKJO7dVCFzJO4RVpuA/edit?usp=sharing)
* [UML class diagram of ValueFlows, still under discussion there](https://drive.google.com/file/d/0B6Rd5fQ-CZheSmo0aXJMQV9uMnc/view?usp=sharing)
