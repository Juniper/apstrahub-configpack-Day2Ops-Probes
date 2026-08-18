# Day2Ops Probes

This pack creates an EVPN host flapping monitoring probe for EOS and Junos leafs.

The probe monitors MAC addresses learned alternately from local and VTEP interfaces and raises an anomaly when flapping is sustained.

## Components

| Component | Name | Description |
| ----------- | ------ | ------------- |
| Probe | dc-evpn-host-flapping | Monitors EVPN MAC flapping and raises a sustained-flapping anomaly per leaf |
