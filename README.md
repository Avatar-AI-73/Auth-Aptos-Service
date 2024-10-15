# Project: Avatar AI auth service (via Aptos)

## Description

This project is an API for verifying transactions on the Aptos network and generating JWT tokens.
It provides several endpoints for handling transactions and token verification. 
The key features include: 
- JWT token generation based on the verification of signed messages from the Aptos network.
- Transaction status verification on the Aptos blockchain.
- JWT token verification.

## Usage in Avatar AI

The service is used to generate authorization tokens that 
grant access to the main Avatar AI API. These tokens are required 
for authenticated requests. Additionally, it is used to validate 
transactions that replenish the internal balance on the API, 
which is measured in a special currency called **Avatar coin (AICoin)**. 
This balance can be used to pay for the creation of characters and 
messages within the platform.

### Pricing Policy

The pricing structure for different services on the Avatar AI platform is as follows:

- Text message: 1 AICoin
- Audio message: 2 AICoin
- Video message: 5 AICoin
- Text-based character: 20 AICoin
- Audio-based character: 40 AICoin
- Video-based character: 100 AICoin

Users can spend their internal AICoin balance to pay for these services, 
including generating messages or creating characters, depending on the desired format.

### Exchange Rate

The exchange rate for AICoin is set at 1 AICoin = 0.01 Aptos. This rate applies when users replenish their internal balance through the platform.