# Day2Ops Probes

This pack creates an EVPN host flapping monitoring probe for EOS and Junos leafs and is relevant for deployments using Day2Ops mode.

The probe monitors MAC addresses learned alternately from local and VTEP interfaces and raises an anomaly when flapping is sustained.

## Components

| Component | Name | Description |
| ----------- | ------ | ------------- |
| Probe | dc-evpn-host-flapping | Monitors EVPN MAC flapping and raises a sustained-flapping anomaly per leaf |
