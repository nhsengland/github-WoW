# Escalation Procedure

In the event of an individual breaking the code of conduct you should inform the organisation owner in order that action can be taken. 

### Assume accidental publications are compromised

Whilst secrets and sentive data should never be made public, we must assume that this will happen at some point.  See the [Open Source Policy](https://github.com/nhsx/open-source-policy/edit/main/open-source-policy.md) for guidance around what code should be made open and what should remain closed. Once a secret or other sensitive data has been published, you must assume that it is compromised no matter how quickly you are able to remove it.

- If you accidentally publish a secret, you must revoke it and immediately provision new keys to the system.  You should also let the organisation owner know of the breach and any asset owners of compromised resources.
- If data has been leaked, **contact <england.ig-corporate@nhs.net> immediately**. 

### Deal with security vulnerabilities

If you discover a vulnerability as part of your usual development and test cycle, or it was reported to you through a private vulnerability disclosure process, the risk of attack is low. You should deal with the vulnerability as a normal bugfix cycle, and release after the code is committed.

If someone has publicly disclosed the vulnerability, you should consider whether you need to make an emergency fix. You should also review the vulnerable parts of the system to check for inconsistencies to determine whether the vulnerability has been exploited.

If you’re given private information about a vulnerability that affects others, it might be appropriate to make the fix privately, deploy from a private repository and merge back into the public one when safe to do so. This will avoid putting other teams or systems at risk by leaking the information before it is made public.

You should never close an open repository. Once the code is public, it’s likely that users will make their own copies. By closing the code, you may draw attention to the issue and it may not be resolved as quickly.
