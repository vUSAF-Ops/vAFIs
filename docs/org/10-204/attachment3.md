# Attachment 3 -- Planning Factors

## Mobility Planning

Due to the number of variables involved in every air mobility operation, the planning factors presented are not universally applicable. Instead, they provide "order of magnitude" approximations in the context of a generic scenario. The use of detailed computer simulation models is encouraged for extensive calculations.

### Airlift Formulas

Number of Cargo Missions Required

    = Requirement/Average Payload

Number of Passenger (PAX) Missions Required

    = Total Pax -- Pax on Cargo Missions / Pax Capability per Pax Mission

    NOTE: Pax on Cargo Missions = Number of Pax seats available on each cargo mission x Number of Cargo Missions.

Total Missions Required

    = Cargo missions + Pax missions

### Air Refueling Formulas

Offload Required (per receiver)

    = (dist / TAS x fuel flow) -- total fuel + dest resv

    dist = total distance from takeoff to landing

    TAS = average airspeed of receiver leg (use Block Speeds table for mobility aircraft or applicable flight manual airspeeds for combat aircraft.)

    fuel flow = fuel burn rate in lbs/hr

    total fuel = total fuel on board at takeoff

    dest resv = required fuel reserves at destination

Offload Available (per tanker)

    = total fuel -- (dist / TAS x fuel flow) -- dest resv

Tankers required = offload required/ offload available

|        **Type**        | **Mach**  | **500     NM**  | **1000     NM**  | **1500      NM**  | **2000     NM**  | **2500     NM**  | **3000     NM**  | **3500     NM**  | **4000     NM**  | **4500     NM**  | **5000     NM**  | **5500     NM**  |
|:----------------------------: |:---------------: |:---------------------: |:----------------------: |:-----------------------: |:----------------------: |:----------------------: |:----------------------: |:----------------------: |:----------------------: |:----------------------: |:----------------------: |:----------------------: |
|     C-130                     |     .49          |     242                |     266                 |     272                  |     273                 |     272                 |     271                 |                         |                         |                         |                         |                         |
|     C-17                      |     .76          |     335                |     384                 |     400                  |     405                 |     406                 |     406                 |     409                 |     412                 |                         |                         |                         |
|     C-5                       |     .77          |     341                |     393                 |     410                  |     415                 |     416                 |     416                 |     420                 |     422                 |     424                 |     426                 |     428                 |
|     KC-10                     |     .81          |     354                |     410                 |     428                  |     435                 |     436                 |     437                 |     440                 |     443                 |     446                 |     447                 |     449                 |
|     KC-135                    |     .79          |     348                |     401                 |     419                  |     425                 |     426                 |     426                 |     430                 |     433                 |     435                 |     437                 |     438                 |
|     Aircraft Block Speeds     |                  |                        |                         |                          |                         |                         |                         |                         |                         |                         |                         |                         |

|  **Acft Type**   | **Fuel Burn lbs/hr**  | **Acft Type**  | **Fuel Burn lbs/hr**  | **Acft Type**  | **Fuel Burn lbs/hr**  |
|:----------------------: |:---------------------------: |:--------------------: |:---------------------------: |:--------------------: |:---------------------------: |
|     C-130               |     5,100                    |     A-10              |     4,100                    |     VC-10             |                              |
|     C-17                |     19,500                   |     F-15C             |     10,500                   |     A-6               |     5,800                    |
|     C-5                 |     23,000                   |     F-15E             |     12,500                   |     F-18              |                              |
|     KC-10               |     17,500                   |     F-16              |     5,800                    |     F-2               |                              |
|     KC-135              |     10,500                   |     F-22              |     13,000                   |     GR-4              |                              |
|     Fuel Burn Rates     |                              |                       |                              |                       |                              |

|     **Aircraft**      | **T/O Wt**  | **T/O Fuel**  | **Max Offload**  |                 |                 |                 |
|:---------------------------: |:-----------------: |:-------------------: |:----------------------: |---------------- |---------------- |---------------- |
|                              |                    |                      |     500 NM              |     1000 NM     |     1500 NM     |     2500 NM     |
|     KC-135R                  |     322,500        |     180,000          |     100,000             |     75,000      |     55,000      |     11,000      |
|     KC-10                    |     590,000        |     330,000          |     230,000             |     195,000     |     155,000     |     75,000      |
|     VC-10                    |                    |                      |                         |                 |                 |                 |
|     Offload Capabilities     |                    |                      |                         |                 |                 |                 |

| **Aircraft Type**  | **Pallet Positions**  | **Cargo (Short Tons)**  | **Passengers**  |
|:------------------------: |:---------------------------: |:-----------------------------: |:---------------------: |
|     C-9                   |     -                        |     -                          |     40                 |
|     C-130                 |     6                        |     17                         |     90                 |
|     C-17                  |     18                       |     65                         |     101                |
|     C-5                   |     36                       |     89                         |     73                 |
|     KC-10                 |     22                       |     60                         |     75[^1]                 |
|     KC-135                |     6                        |     18                         |     53[^2]                 |
|     A-330                 |     -                        |     -                          |     240                |
|     A-300-600             |     15                       |     79                         |     -                  |
|     B-747                 |     34                       |     113                        |     315                |
|     B-757                 |     15                       |     38                         |     125                |
|     B-767                 |     24                       |     67                         |     190                |
|     B-777                 |     -                        |     -                          |     246                |
|     DC-10-30              |     30                       |     79                         |     242                |
|     MD-11                 |     34                       |     98                         |     267                |
|     Aircraft Payloads[^3][^4]     |                              |                                |                        |

|        **Aircraft Type**        | **Min Runway (ft)**  | **Min Taxiway (ft)**  |
|:-------------------------------------: |:--------------------------: |:---------------------------: |
|     C-9                                |     5000x90                 |     40                       |
|     C-130                              |     3000x60                 |     30                       |
|     C-17                               |     3500x90                 |     50                       |
|     C-5                                |     6000x147                |     75                       |
|     KC-10                              |     7000x148                |     75                       |
|     KC-135                             |     7000x147                |     75                       |
|     B-747                              |     6600x90                 |     75                       |
|     B-757                              |     4750x90                 |     75                       |
|     B-767                              |     6000x150                |     75                       |
|     DC-10                              |     6100x90                 |     75                       |
|     MD-11                              |     7000x150                |     75                       |
|     Aircraft Airfield Restrictions     |                             |                              |

[^1]: 16 Pax with 22 Pallets, 75 Pax with 16 Pallets
[^2]: 26 Pax with 6 Pallets
[^3]: Cargo and passenger payloads (except for the C-5) are exclusive of one another
[^4]: Weights are based on 400 lbs per passenger, which includes baggage and gear
