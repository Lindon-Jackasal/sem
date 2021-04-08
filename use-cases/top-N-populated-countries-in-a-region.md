# USE CASE: 8 Produce a Report on the Top N Populated Countries in a Region where N is provided by the User.

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *organization worker* I want *to produce a report on the top N populated countries in a region where N is provided by the user* so that *I can support the reporting of the top N countries in a region where N is provided by the user.*

### Scope

Organization.

### Level

Primary task.

### Preconditions

Database contains country data.

### Success End Condition

A report is available for the organization to provide information on the top N populated countries in a region where N is provided by the user.

### Failed End Condition

No report is produced.

### Primary Actor

Organization worker.

### Trigger

A request for this specific report is sent to the organization.

## MAIN SUCCESS SCENARIO

1. Organization requests information on the top N populated countries in a region where N is provided by the user.
2. Organization worker triggers the report generation to extract the top N populated countries in a region where N is provided by the user.
3. Organization worker provides report to organization.

## EXTENSIONS

2. **Data does not exist**:
    1. Organization worker informs the organization no data exist.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0