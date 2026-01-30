# NHS Winter Pressures Flow Analysis

## Overview
An operational analysis of bed occupancy and A&E performance during winter pressure periods.

## Problem Statement
High bed occupancy and delayed discharges restrict patient flow, contributing to long A&E waits and operational strain during winter months.

## Stakeholders
- NHS England
- Trust operational teams
- ICS urgent care leads
- Patients and public

## Key Questions
- Which trusts exceeded safe bed occupancy thresholds?
- Is high occupancy associated with poorer A&E performance?
- Where are the key system bottlenecks?

## Data Sources
- **Urgent and Emergency Care SitReps – Monthly Averages** (NHS England)  
- **Time period:** Selected winter month  
- **Coverage and limitations:** Monthly averages smooth daily volatility.

## Approach
- Data ingestion and cleaning
- Identification of trusts exceeding 95% occupancy
- Correlation analysis between occupancy and A&E waits
- System flow interpretation

## Key Findings
- Many trusts operate above safe occupancy levels
- Higher occupancy correlates with poorer A&E performance
- Discharge delays appear to be a key constraint

## Visual Outputs
- Bed occupancy distribution charts  
- A&E performance comparisons  
- Occupancy vs wait-time scatter plots

## Delivery Considerations
- Correlation does not imply causation
- External demand factors not modelled
- Snapshot analysis limits trend insight

## Recommendations
- Prioritise discharge capacity ahead of winter
- Use occupancy as a leading escalation indicator
- Strengthen system-level flow monitoring

## Impact
Improved patient flow would reduce A&E waits, improve safety, and increase system resilience during peak demand.

## Tools Used
Python pandas numpy matplotlib seaborn VSCode

## How to Run
1. Clone the repository  
2. Install dependencies  
3. Add SitRep data to `data/raw`  
4. Run `python run.py`

## Next Steps
- Add daily SitRep analysis
- Include delayed discharge metrics
- Model capacity and flow scenarios
