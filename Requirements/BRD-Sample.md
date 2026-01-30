# Business Requirement Document (BRD)

## Project Background
The RT Treasurer requires a system to simplify the recording of cash inflow and cash outflow.
There are monthly contributions for cleanliness and security with different billing amounts
depending on the condition of each land plot.

## Neighborhood Conditions

### 1. Land Plots
- Total land plots: 90
- Details:
  - Block A1 – A20
  - Block B1 – B20
  - Block C1 – C20
  - Block D1 – D20
  - Block E1 – E10
- Block E plots have an area of 200 m²
- Other blocks have an area of 100 m²
- Each plot condition:
  - Occupied
  - Unoccupied
  - Vacant land / under construction

### 2. RT Monthly Contributions
- Contributions are calculated based on land size per 100 m²

#### a. Occupied Plot
- Cleanliness Fee: IDR 100,000
- Security Fee: IDR 100,000

#### b. Unoccupied Plot
- Cleanliness Fee: IDR 100,000
- Security Fee: IDR 50,000

#### c. Vacant / Under Construction Plot
- Cleanliness Fee: IDR 50,000
- Security Fee: IDR 50,000

- All landowners in Block E own two additional plots in other blocks:
  - One occupied plot (rented)
  - One vacant or under-construction plot

## Business Objectives
- Provide monthly summary reports of cash inflow and cash outflow
- Provide detailed monthly reports showing:
  - Residents who have paid
  - Residents who have not paid
  - Residents with outstanding payments for multiple months

## Scope

### In Scope
- Land Plot Data
- Resident Data
- Contribution Master Data
- Cash Inflow and Outflow Transactions
- Reporting

### Out of Scope
- Financial posting

## Stakeholders
- Treasurer (User)
- Head of RT (Approver / Viewer)
- Residents
