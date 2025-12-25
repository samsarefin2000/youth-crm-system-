# CRM Data Dictionary

## youth_master.csv
- youth_id: Unique identifier for each youth (Primary Key)
- status: Active | Follow-up | Inactive
- priority: High | Medium | Low

## conversation_log.csv
- interaction_id: Unique interaction record
- youth_id: Links to youth_master
- interaction_type: Call | Email | Session | In-person

## needs_support.csv
- primary_need: Main area of support
- outcome_status: Open | In Progress | Resolved
