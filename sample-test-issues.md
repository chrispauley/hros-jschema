## HROS 4.1 Sample Data Validation Test Result
As of 1/20/2018 there are sample errors in the 4.1 development branches.


### Assessments.
No errors found.

### Benefits
No errors found.

### Compensation
No errors found.

### Interviewing
Errors found.

AsynchronousOrderMontageVideoInterview_ReturnInformation.json
AsynchronousOrderMontageVideoInterviewWithQuestions_ReturnInformation.json
AsynchronousOrderMontageVideoInterviewWithQuestions.json
AsynchronouswOrderMontageVideoInterview.json
```
/language
Invalid enumeration value: En-US
```

InterviewPositionMontageAlternateScenario.json
```
/language
Invalid enumeration value: En-US
/position
Missing required property: interviewFormatArray
```

InterviewPositionMontageAlternateScenario2.json
InterviewPositionMontageAlternateScenarioReturnInformation.json
```
/language
Invalid enumeration value: En-US
```

StatusNotificationHirevue.json
```
/interviewId
/positionId
Invalid instance type: integer. Expected: object
```

StatusNotificationInterviewExpiredMontage.json
StatusNotificationInterviewStartedMontage.json
StatusNotificationInterviewSubmittedMontage.json
```
/language
Invalid enumeration value: En-US
```


### Recruiting
Errors found.

The following are empty files, no json:
PositionOpening_UC3_hiring_manager_approval.json
PositionOpening_UC5_submission_to_staffing_supplier.json
PositionOpening_UC6_hris_to_lms.json
PositionOpening_UC7_hris_to_ap.json
PositionOpening_UC8_recruiting_system_to_pes.json
PositionOpening_UC9_candidate_position_opening_match.json


### Screening
Errors found.

ALaCarteCatalog.json
PackageCatalog.json
property "catalog" is not defined in your specification.


OrderType.json
Invalid instance type: string. Expected: object/aLaCarteItems/0/screeningInstructions


SubjectType.json
Your schema identifies "organization" or "person"
This file does not have a top property matching "person".

Filenames should have the extension ".json"
Subject_IndividualScreening
Subject_OrganizationScreening
Also. Noun data is included in the sample but not defined as a noun in your schema.


### Timecard
Errors Found.
All files failed. PersonId's are not valid IdentifierTypes.

approvals.json
/approvers/0/person/id

balances_1.json
/approvers/0/person/id
Missing required property: quantity/items/0/balances/0
Missing required property: amount


### Wellness
Errors found.

activity_response_daily.json
Invalid instance type: string. Expected: object/activities/0/id
Invalid instance type: array. Expected: object/activities/0/source
Invalid instance type: string. Expected: object/activities/1/id
Invalid instance type: string. Expected: object/activities/2/id
Invalid instance type: string. Expected: object/activities/3/id


### Common
Inconsistent sample files, naming, and structure.
Need to discuss in TSC.
