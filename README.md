# MakoPulse Agent releases

Signed Windows builds of the MakoPulse RMM agent. Release files only — the
source lives in a private repository.

Every build here is signed by **Mako Logics LLC** through Azure Trusted Signing.

An installed agent will not accept a build from this page unless all of the
following are true, checked on the PC itself:

- a person approved that exact version and SHA-256 with a passkey;
- the downloaded bytes hash to the approved SHA-256;
- Windows reports the Authenticode signature as valid and the signer as Mako Logics LLC;
- the version is newer than the one already running.

A publicly readable download is deliberate: the PC needs no credential to fetch
an update, and nothing here is secret. What protects the update is the signature
and the approval, not the address.
