# nfsp-dnslink

Automated setting of a [DNSLink](https://dnslink.io) TXT record to
your [NearlyFreeSpeech](https://www.nearlyfreespeech.net/) domain name.
Useful for static website publishing or mirroring on IPFS, specifically
Git post-receive hook.

# Dependencies

```perl
WebService::NFSN;
```

# How to use it

Fill out the `$Username`, `$Apikey` and `$AccountId` variable
in the script with values from your account.
Then, general usage is as follows:

```bash
nfsp_dnslink [IPFS CID] [DOMAIN] (optional subdomain)
```
