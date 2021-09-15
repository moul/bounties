# Active Bounties

If you see active bounties on github.com/gnolang/bounties, it is still active!

### 3. Retrospective on CosmosHub software contracts from the ICF and related entities
  * Investigation into case studies (motivated by recent gravity bridge discussions).
  * Proposal for legal clauses to add to software projects funded by such entities.
  * A plan to create an oversign committee funded by the Cosmos Hub.
  * 1000 ATOMs from @jaekwon, but first get approval for plan.
  * Unspecified amount of GNOTs, amount pending plan for general tasks (coming soon).

### 4. Port JOESON to Go
  * github.com/jaekwon/joescript
  * The intent is to create an independent left-recursive PEG parser for Gno.
  * Optional: port Joescript or Javascript.
  * 1000 ATOMs from @jaekwon
  * More GNOTs than from #3.

### 5. Make script for Backup Keys
  * We can't know that there hasn't been a leak of private keys via some unknown mechanism.
  * A large scale theft is almost inconceivable, but possible for all one knows.
  * Such a large scale theft is the only existential risk to cosmos/crypto.
  * Create a simple English document and Go code for the following procedures:
    - create a backup secp256k1 AND ed25519 pubkeys on an airgapped offline computer.
    - use gnokey.
    - use custom entropy (e.g. dice-rolls).
    - ask everyone on Cosmos to publish both backup pubkeys by sending a transaction with memo to a null address bech32(20 zero bytes).
  * Use the same bip39/bip32 construction for the secp256k1 privkey/pubkey.
  * Use only sha256() for the ed25519 privkey/pubkey but otherwise no KDF function (may need to modify gno/pkgs & gnokey.
  * Include instructions for building this binary from a verified build of Go.
  * 1000 ATOMs from @jaekwon
  * Same number of GNOTs as #4.

# Completed Bounties

### 1. Get CosmosHub 1,2,3 blockchain data
  * Must upload raw blockchain data to S3 link or similar
  * Link may be private, contact for private transfer (we will publish for public separately)
  * Also coordinate on ION governance telegram chat for updates t.me/IONGovernanceWorkingGroup
  * 1000 OSMO from @jaekwon
  * COMPLETE: sunny referred to [interchain link](https://archive.interchain.io/).
  * [SUMMARY](bounties/001_cosmoshub_blockchain_data/README.md).
  
### 2. Derive governance history using script on CosmosHub 1,2,3,4 data
  * Must share github or gitlab link to script repo
  * Also coordinate on ION governance telegram chat for updates t.me/IONGovernanceWorkingGroup
  * 5000 OSMO from @jaekwon
  * Unspecified amount of GNOTs, amount pending plan for general tasks (coming soon).
  * [SUMMARY](bounties/001_cosmoshub_blockchain_data/README.md).

# Instructions

 * Use the github.com/gnolang/bounties issues for primary communication and coordination.
 * Please submit all information as links to files or repos via issues here.
 * Please add to bounties by making a PR request to this file.
 * Please submit attributions/credits for all work; we will figure out how to split the bounty together.
 * Please help keep bounty contribution data organized on gnolang/bounties/issues; all necessary work will be rewarded.
