These CloudWatch (CW) Agent templates monitor Windows Event Logs (Application, Security, System) and specify a named CW Log Group for each log type.
There are templates for XML and text versions as well as variants that include instance metrics for each.
I have recently added a template that outputs Windows Event Logs using both formats (text, XML) to their respective CW Log Groups.
Please review each template and adjust values to fit your needs.

The named CW Log Groups for XML formatted events are:
"XmlWinEventLogApplication"
"XmlWinEventLogSecurity"
"XmlWinEventLogSystem"

The named CW Log Groups for textformatted events are:
"WinEventLogApplication"
"WinEventLogSecurity"
"WinEventLogSystem"