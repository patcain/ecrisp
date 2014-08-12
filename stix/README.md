**STIX Profiles and Examples**

This directory contains various 'threats' encoded in the STIX format.

Completed encodings:
* phishing/stix_phishing:		
  An encoding of an email phishng lure (both header and body) and collector address (both DNS and IP) marked to share with others.

In-Process encodings:
* scans/scanning:

  An encoding of a remote device scanning for open ssh servers.
* scans/scanning_user:

  An encoding of a remote device attempting to login as the root user onto a local machine.
* bots/CnC:

  An encoding to notify others of a new botnet C&C.
* bots/infected:

  An encoding to notify another party that their IP Address is surely infected.

Other 'threats' will be forthcoming as they are discovered or suggested.

***NOTE:** The STIX encodings in thiss directory will not validate with the public STIX schemas unless you correct the 'xml:lang="English"' to 'xml:lang="en"'. 