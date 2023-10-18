# pkg.one
Need a domain name to host the documentation for your open source project? pkg.one can, just follow our [Fair Use Terms](./fair-use-terms.md) to get a short, nice domain name for your documentation.

# How to Apply
As mentioned in the text, you need to submit an Issue to this repo to request the creation or change of your pkg.one domain name, subject to our fair use terms.

They usually come through quickly.

# How to verify a domain
You need to add a file called `.verify` in your website directory and provide it in the following format.
```
template:
Pacific Standard Time||Subdomain||Domain name that requires CNAME

example:
20231018||example||example.github.io
```

This operation needs to be updated when new domain names are requested and when domain names are changed.

If you are requesting domain name deletion, follow the template below to create a verification file.
```
template:
Pacific Standard Time||Subdomain

example:
20231018||example
```

# How to report
Found a pkg.one subdomain that violates the fair use terms? Let us know in Issues.