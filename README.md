# Data Ecosystem Automation

RPA Automation for all the TBS Policy Instruments: https://www.tbs-sct.canada.ca/pol/hierarch-eng.aspx (except 12 from different sources)

This is a small RPA Automation using UiPath.
The LIST of English and French Policies is found in the OBJECTS folders “\.Objects\PolicyInstruments.xlsx” as well as the log file from the automation “\.Objects\Runtime_Log.txt”.

There are 2 'Write CSV' components found within the workflow that are currently saving the .CSV files to my file path: "F:\UiPath_Workspace\TBS_Policy_Instrument_Data". In the interim, please change the write file path until automation is migrated to the Cloud with orchestration.
