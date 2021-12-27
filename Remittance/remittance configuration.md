# Remittance Configuration

 

| NUMBER | CONFIG SETTINGS | TEST OUTCOMES |
| --- | --- | --- |
| 1 | Trust Account lists Maintenance > Trusts items |Any remittance for this configuration should only include clients who use the selected trust |
| 2 | (Sequence id to be removed from UI) | (N/A) |
| 3 | Description | the limit and the empty field (100 positions) |
| 4 | Use the Run Date as the Ending Date selecting this option disables the Ending date of the date range |it disables the ending date selection |
| 5 | Beginning Date | date is less than end date; back dating |
| 6 | Ending Date must be >= to the beginning date and will be disabled if the Use the Run Date as Ending is on | the date must be greater than beginning date |
| 6.1 | | the payments on the remittance have a transaction date within beginning and ending date |
| 7 | Client range - then ending client must be >= the beginning client | client beginning and ending are in the correct order and error if reversed |
| 7.1 | | the clients included in the remittance are in the designated range |
| 8 | Beginning and Ending Client are lists of the Maintenance > Client items | all the Maintenance > Client items are listed in the drop-downs |
| 9 | Disbursement Release code is a list of the options of all codes and one for "All" codes | the list available here is the same as the list provided under Maintenance > Client - Accounting "Disbursement Release Code" |
| 9.1 | | the remittance only includes payments with the selected disbursement release code |
| 9.2 | | the remittance includes all payments regardless of disbursement release code if All is selected |
| 10 | Fee Basis Code is a list of all the Maintenance > Fee Basis items | all Maintenance > Fee Basis items are listed in the drop-down |
| 10.1 | | remittance only includes payments on cases with the selected Fee Basis Code |
| 11 | Number of Records per check defaults to 0 and max is 999, if 0 this means there is no limit | the field only allows numbers and a maximum of 9999 |
| 11.1 | | the limit set here is observed in the remittances under this configuration |
| 11.2 | | if 0 is the limit All otherwise qualifying payments are included in the remittance |
| 12 | Toggle for Over-ride default cash receipt hold-to-date? | ON causes the remittance to include all payments regardless of the hold period designated on the client. also the reverse. |
| 13 | Toggle for Over-ride client setting to bill for costs? | ON causes the remittance to not deduct costs if client is set to deduct. |
| 14 | Toggle for Over-ride client setting to bill for direct payments? | ON causes the remittance to not deduct direct payment (DD) fees if the client is set to deduct |
| 15 | (Toggle for Is this a State Farm Remittance? To be removed from UI) | (N/A) |