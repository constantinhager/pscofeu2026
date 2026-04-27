# Secret’s out 🤫 There's a better way to access Multi-Tenant

## Abstract

Until recently, handling secrets or certificates has been unavoidable when automating across tenants. This complexity has created security risks, operational overhead, and compliance headaches.

Now, finally, Microsoft has GA’d Federated Identity Credentials, making it possible to explicitly trust identities from external tenants.
In this session, I will demonstrate how to achieve truly secret-free multi-tenant automation using PowerShell to obtain access tokens for any tenant on-the-fly.
Managing the permissions is surprisingly straightforward and we have used this in production to access and collect data from ~30 tenants.

After this session, you will have a basic understanding of how to set up a production-ready framework that eliminates the need for secrets while maintaining scalability. You will walk away with PowerShell code examples and a clear understanding of how and when to implement this pattern in your own environments.
