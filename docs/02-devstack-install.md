# DevStack Installation

## Deployment context

This OpenStack lab is deployed with DevStack in a single-node architecture.

## Execution user

All DevStack operations are executed with the `stack` user.

## Network interfaces detected

- `enp0s3`: `10.0.2.15/24` (NAT)
- `enp0s8`: `192.168.150.3/24` (lab/local access)

## Selected HOST_IP

The `HOST_IP` value used in `local.conf` is:

`192.168.150.3`

## Services enabled

- Horizon
- Neutron server
- Neutron agent
- DHCP agent
- L3 agent
- Metadata agent
- Open vSwitch

## Notes

- NAT is kept for internet access
- The secondary interface is used for local/lab access
- This is a laboratory deployment, not a production cluster
