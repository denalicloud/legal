# BACKUP POLICY

## General

 In the following description, we differentiate between backup for hosting accounts and backup for hosted vps servers. Here below the exact backup policy that is followed for backup purposes.

### Hosting accounts

 Hosting accounts are client's hosted data on shared servers. It is possible for the client to activate the backup of web data, by accessing to the internet hosting control panel, in backup section. In that area, the customer can set backup frequency and retain. This backup is made to a box which belongs to a different server but may be located in the same datacenter. Activating this backup must be done actively by customer. By default we dont activate it on behalf of customer. It's customer responsibility.

 The hosting server is also automatically backupped in its whole by a backup procedure. This procedure takes snapshots of the whole server daily and keeps them for 7 days. This snapshot is hosted on a different machine but may be located in the same datacenter. The recovery of this backup is a procedure that is reserved to Denali's team in case of disaster. The customer has no power on such a recovery.

 Please bear in mind that generally speaking we don't make backup of email accounts and data for privacy reasons. However backup snapshots may contain emails data depending on its kind and this sometimes cannot be avoided for snapshot integrity reasons.

### Dedicated VPSs

 Dedicated VPS of VM series, include the snapshot backup as below described, while for the VB series the snapshot backup is optional and can be requested for an additional price.

 In case the client of VM series (by default) or VB series (for additioanl price) benefits of such a service, he will get a daily snapshot of the whole server, kept for 7 days. Customer can always restore this backup by the internet control panel facility. The snapshots are hosted on a different server which may be in the same datacenter.

 In case the customer would need a higher level of redundancy, for example to a different datacenter or a mirror of a server itself, he would contact Denali for getting an advise and a quote.

