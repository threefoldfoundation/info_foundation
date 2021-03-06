![](img/grid_banner.jpg)

## Certified Farmer Requirements 

- Farmers will only be rewarded as certified if following requirements are met.

### Requirements Generic

- sign terms and conditions document with threefold_dubai
- terms & conditions contract: farmer agrees that 
  - Threefold operates as a DAO and as such is not responsible for anything which happens on the TFGrid
  - For 2021. H1 2022, [Grid pricing](cloudunits_pricing) is defined by wisdom_council but this will probably change and become part of the DAO.
  - TFTech as subcontractor for threefold_dubai delivers software support for the tfgrid_primitives (only defect support and certified builds).
  - All information required to be a farmer can be found on our knowledgebase: https://info.threefold.io/
  - TFT rewards (farming) is the result of the blockchain as operated by consensus3 concept. If SLA is not achieved TFT will NOT be rewarded that month.
  - TFT rewards are done in line with [farming reward document](farming_reward).
  - Measurement of SLA (see below) done by consensus3 engine.
  - Agreement about vesting already farmed TFT for farmers of TFGrid 2.0 see [vesting_overview](vesting_overview).

### Requirements Network

- 99.5% uptime
- 2 IP feeds (*)
- at least 1 class C ipv4 addr for network farmers.
- enough bandwidth to allow the utilization of the storage/archive (see below)
- good enough latency (low latency = performance of network)
- [install your network in line with Threefold Requirements](tfgrid_networking)

(*) = in case of datacenter or commercial deployment

### Requirements Service Level

The TF_Farmer needs to agree to a set of minimal service level agreements to do with

- minimal bandwidth as required for the workloads as hosted on the farm
- maximum network latency
- more than 1 internet connection (*)
- protection for fire & water damage (*)
- enough IPv4 addresses (*)
- enough access to power (*)
- redundant power systems (*)

(*) = in case of datacenter or commercial deployment

### Bandwidth Requirement for archive/storage usecase.

A storage usecase needs a lot of bandwidth to allow the storage nodes to be fillend and also to allow its customers to download the information.

Its the obligation of the farmer to make sure that enough bandwidth is available. We will measure this by doing random upload & download tests to the storage systems. 

It should always be possible to have at least 1 mbit/sec per Zero_DB (which is a storage container running on 1 harddisk or ssd).


### Remarks Farming Requirements

#### Reputation & Monitoring Engine

The TFGrid has a reputation engine and a monitoring engine to measure uptime & other SLA requirements, see consensus3.

Factors the TFGrid Reputation_engine will look at (Q4 2021, latest Q1 2022) 

- Available Bandwidth
- Latency
- Utilization
- Uptime (nodes & network)

 