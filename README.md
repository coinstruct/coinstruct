# [![Coinstruct](https://cloud.githubusercontent.com/assets/23185823/22582682/2c976a22-ea23-11e6-939e-3343d1d39de1.png)](http://www.coinstruct.com/)

Here are the Smart Contracts we used at Coinstruct (Beta!):

- Token.sol
  - This defines the same Token interface as found in the standard library.
- AddressRegistry.sol
  - This defines the AddressRegistry interface, which is used to determined whether a public address (a user) is registered in an external system or not.
- InvestorRegistry.sol
  - This defines the InvestorRegistry contract, which is an implementation of the AddressRegistry interface.
- CrowdFunding.sol
  - This defines the main contract for a crowdfunding campaign.
