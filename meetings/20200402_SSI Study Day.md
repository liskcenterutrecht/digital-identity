# Resources

- Reading list: https://github.com/liskcenterutrecht/digital-identity/blob/master/research/reading-list.md
- Youtube playlist: https://www.youtube.com/playlist?list=PLh9plCWotp9lKPuxSj6Ugj1SYdzW_2stF
- Conference grid: https://calendar.google.com/calendar?cid=NnJ2ZWJvNTQxODlmYm1yZHM5OGVraG10ZG9AZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ

# Notes date: 2 April 2020

# Made during study sessions
- Shared whiteboard: https://www.webwhiteboard.com/board/65aaypyt

# Shared links during study sessions
- https://www.unic.ac.cy/iff/blockchain-certificates/
- https://sablier.finance/
- https://docs.google.com/document/d/1ExvfbiNvwowG7UK9ULxmFVLXfyCYMd85VRV0KjwFMWM/edit
- https://waag.org/nl/article/de-staat-van-het-internet-2020
- https://tweakers.net/reviews/7768/half-life-alyx-zo-goed-als-we-hoopten.html
- https://github.com/rabobank-blockchain
- https://github.com/rabobank-blockchain/vp-toolkit
- https://smilo.io/ blockchain Caspars teammate works with for KLM challenge

### Notes by Marnix' presentation about vp-toolkit
- npm install
- hard code yourPrivateKey = master key
- use for context: always the w3.org credentials
- at type you can write: 'diploma' or 'passport' etc
- issuer did address must be the same as the one that is signing the credential
- credentialSubject: the id must be the same as the did that is in the holder id wallet
- You can add info below givenName. Like, diploma etc.
- the id of the credentialStatus could be: 'lisk-identity-chain'
- when creating this credential, a derived key from the masterkey is used.
- create the credential with: npm run flow

Things to look into:
- Would it be possible to use a lisk address as did? The uniresolver.io doesn't list lisk.
- If you are an issuer, you don't want to rely on a central party like uniresolver.io. You rather run a universal resolver node yourself.

## Follow up:
1. plan session to complete user story document. > next session Monday 6 April 13.00-14.00 h online.
2. talk to BlockDam about their DAO.
3. go through the Lisk code of Jonathan (what is his repo?).
4. go through Rabo vp-tools workshop.
5. plan session about comparing the different SSI platforms.
6. decide on the goal of the project: use lisk-SDK or use a system that is becoming more a industry standard (hyperledger).
