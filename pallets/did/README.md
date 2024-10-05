Storage: The DIDs map stores a DID document, which includes the account ID, public key, and any associated services.
Events: We emit events when DIDs are created.
Errors: Handles cases where a DID already exists or a requested DID doesn't exist.
Dispatchable Calls:
create_did: Registers a new DID for a user.
get_did: Retrieves the DID associated with a user.

We will go and register the did in the runtime.
