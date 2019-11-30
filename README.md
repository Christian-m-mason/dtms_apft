# dtms_apft

Data visualization for DTMS APFT Data

1. Visit [DTMS](https://dtms.army.mil/DTMS/Default.aspx)
2. Select "Reporting" > "Report Center" > "Report List"
3. Select the "Grid Reports" tab and the "Soldier Roster Report", "Unit APFT Roster Report" and the "Height/Weight Report"

Direct Links to export reports (Requires DTMS Access)

- [Soldier Roster Report](https://dtms.army.mil/DTMS/GridReporting/DisplayReport?type=nFocus.Modules.Reporting.Mvc.Reports.SoldierRosterReport%2C%20nFocus.Modules.Army.GridReportPlugins%2C%20Version%3D1.0.0.0%2C%20Culture%3Dneutral%2C%20PublicKeyToken%3Dnull)

- [Unit APFT Roster Report](https://dtms.army.mil/DTMS/GridReporting/DisplayReport?type=nFocus.Modules.Reporting.Mvc.Reports.ClassApftRosterReport%2C%20nFocus.Modules.Army.GridReportPlugins%2C%20Version%3D1.0.0.0%2C%20Culture%3Dneutral%2C%20PublicKeyToken%3Dnull)

- [Height/Weight Report](https://dtms.army.mil/DTMS/GridReporting/DisplayReport?type=nFocus.Modules.Reporting.Mvc.Reports.HeightWeightReport%2C%20nFocus.Modules.Army.GridReportPlugins%2C%20Version%3D1.0.0.0%2C%20Culture%3Dneutral%2C%20PublicKeyToken%3Dnull)

4. Generate the reports and export the information to Excel
5. Load the file into dtms_acft to provide information about the unit's ACFT scores, ABCP compliance data, and who needs to take an ACFT.
6. dtms_apft will process the data client-side and present the information in a manner that provides situational awareness.
