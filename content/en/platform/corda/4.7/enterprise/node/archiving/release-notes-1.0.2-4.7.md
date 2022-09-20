---
date: '2020-12-10T12:00:00Z'
menu:
  corda-enterprise-4-7:
    identifier: archive-service-4-7-release-notes
    parent: corda-enterprise-4-7-corda-nodes-archive-service
    name: "Release Notes"
title: Release notes
weight: 160
---

# Archive Service release notes

## Archive Service 1.0.2

The Archive Service is a standalone service that operates on a different release cadence to the Corda platform.

## Fixed issues

In this release:

* Improved Archiving support of tokens when they are moved between more than one party and then redeemed.
* Logging of the Archiving tool has been increased to aid in troubleshooting.
* The Archiving client can now connect to nodes which are set up to use RPC SSL connection settings.
* Tables are now ordered by table name length in descending order to prevent foreign key constraints from being violated when deleting rows.
