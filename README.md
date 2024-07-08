#### [View original Project](https://github.com/w3c-ccg/did.actor)

# UNTP Pilots Test Data

This project if a fork of the did.actor projet which was used to seccessfully demonstrate supply-chain use cases in the past.
This version is geared towards the UNTP model and its current pilots.

## Parties

The format definition of a party according to the UNTP can be found here. This consists of actors in the supply-chain playing a specific role which can be subcategorized as an issuer or a consumer. A consumer will most likely conduct verification of credentials. 

These parties are responsible for creating extensions to the UNTP core specificaiton in order to meet their respective buisness goals. The type of party will directly affect where they get their requirements from, wether its by a buisness process of regulation compliance. Example of party type includes regulators, governement organizations, private companies, producers, assessment firms, etc... As the UNTP matures this list might get clearly defined or left abigous to enable these parties to adopt this specification as they see fit.

### Regulators

Regulators are mostly responsible for issuing DigitalConformityCredentials based on existing processes.

- [BC Gov Director of Petroleum Land](parties/regulators/DIRECTOR-OF-PETROLEUM-LANDS/README.md)
- [BC Gov Chief Permitting Officer](parties/regulators/CHIEF-PERMITTING-OFFICER/README.md)

### Producers

Producers are mostly responsible for issuing DigitalProductPassport conforming to various sutainability claims, which are available as DigitalConformityCredential.

- [Pacific Canbriam Energy Limited](parties/producers/PACIFIC-CANBRIAM-ENERGY-LIMITED/README.md)
- [Teck Coal Limited](parties/producers/TECK-COAL-LIMITED/README.md)

## Credentials

Credentials will be issued by an issuer and verified by a consumer. In the context of UNTP, they serve to carry meaningful sustainability data.

- [MinesActPermit](credentials/MinesActPermit/README.md)
- [TenureTitle](credentials/TenureTitle/README.md)

## Registries

Registries represent a source of data that can be used to store trusted information. Registries could include trust registries for issuers, context files, status credentials or any other type of publicly available credentials.

- [Orgbook](registries/orgbook/README.md)
- [Status](registries/status/README.md)