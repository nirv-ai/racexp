# HECCYA Model for Systems, Services and Applications

- focusing on zero-trust immutable infrastructure and applications
- **H**ardware (metal/cloud)
- **E**nvironment (ram/disk)
- **C**omponent (service/application/api)
- **C**ommunication (east-west/north-south)
- **Y**ielding (provision/transform)
- **A**rchitecture (design/topology)

## The 5Dubs

- Whos, Whats, Whens, Wheres, Whys
- who are the actors and communicators
  - what are they doing and how are they saying it
- What is the world?
  - internal, external, global, local, controlled, insecure, captive, released
- When is the time?
  - perf, slas, concurrency, parallelism
- Where is the data?
  - in flight, at rest, disk, ram
- Why do we exist
  - entry, exits, triggers

## Considerations

- what is the user flow for each use case?
- what is the data pipeline?
  - data sources, data serialization, data format, intermediate storage of raw data, and storage of the final transformed data
- what is the system process workflow?
  - how do system components work together in response to the user flow
