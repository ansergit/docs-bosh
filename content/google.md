---
title: Google Cloud Platform
---

# Google Cloud Platform

The `google` CPI can be used with [Google Cloud Platform](https://cloud.google.com/).

 * Release: [cloudfoundry-incubator/bosh-google-cpi-release](https://github.com/cloudfoundry-incubator/bosh-google-cpi-release)
 * Issues: [GitHub Issues](https://github.com/cloudfoundry-incubator/bosh-google-cpi-release/issues)
 * Slack: [cloudfoundry#bosh-gce-cpi](https://cloudfoundry.slack.com/messages/bosh-gce-cpi)


## Concepts

The following table maps BOSH concepts to their respective IaaS concept.

| BOSH              | Google Cloud Platform |
| ----------------- | --------------------- |
| Availability Zone | [Zone](https://cloud.google.com/compute/docs/regions-zones/) |
| Instance          | [Virtual Machine Instance](https://cloud.google.com/compute/docs/instances/) |
| Network Subnet    | [VPC Subnet](https://cloud.google.com/vpc/docs/vpc#vpc_networks_and_subnets) |
| Virtual IP        | [Static External IP](https://cloud.google.com/compute/docs/ip-addresses/#reservedaddress) |
| Persistent Disk   | [Persistent Disks](https://cloud.google.com/persistent-disk/) |
| Disk Snapshot     | [Persistent Disk Snapshots](https://cloud.google.com/compute/docs/disks/create-snapshots) |
| Stemcell          |  |


## Feature Support


### Network

| Network Type | Support |
| ------------ | ------- |
| Manual       | Single network per instance |
| Dynamic      | Single network per instance |
| VIP          | Single network per instance |


### Miscellaneous

| Feature   | Support |
| --------- | ------- |
| Multi-CPI | Not Supported |