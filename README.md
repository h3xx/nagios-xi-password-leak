# Nagios XI Password Leak

This is a breakdown of an unpriveleged remote exploit for Nagios XI that causes
it to leak sensitive information through its HTTP REST API. Information such
as:

- Partial process list
- User names and passwords
- IP addresses and machine names
- Port numbers

## Scope, Impact

TODO

## Responsible Disclosure

The original disclosure was sent 2021-08-24. Details of that are [here](./disclosure/DISCLOSURE.md).
