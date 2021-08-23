# Test Plan
## Table:High level Test Plan
|Test ID	| Description |	Exp I/P	| Exp O/P	| Actual Out | Type Of Test|
|-------|-------------|---------|---------|------------|-------------|
|H_01| If User enters correct password and username - Checking the password and username |	Data| Success - Program continues |	Success - Program continues |	Scenario based|
|H_02|If User enters wrong password and username - Checking the password and username |	Data | Fails - Program exit |	Fails - Program exit| Scenario based|

## Table:Low Level Test Plan
|Test ID|H ID|Description	|Exp IN	|Exp OUT|Actual Out|Type Of Test|
|-------|----|------------|-------|-------|----------|------------|
|L_01 | H_01 | Add new student Details|Data|	Add student |	Add student|Requirement based|
|L_03 | H-01 | Search student details by ID	|Data| Searches student deatils |	Searches student deatils |	Requirement based|
|L_03 | H-01 | Search student details by Course	|Data| Search student deatils|	Searches student deatils |	Requirement based|
|L_04 |	H_01 | View all students list|Data| List of student details| List of student details	| Requirement based|
|L_05	| H_01 | Updating login password | Data|Change of paassword |	change of password|	Requirement based|
|L_02 |	H_01 | Delete student details by ID |Data|	Delete's student detail| Delete's student detail	| Requirement based|
|L_06 |	H_01 | User wants to exit? |Data|	Exit |	Exit |	Requirement based|
