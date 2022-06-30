Run time: 30/06/2022 02:01:47

Json query: {"ExportFormat":"summary","ResultSetSize":500,"ResultSetOffset":1000,"TargetCollection":"cases","AndOr":"And","QueryGroups":[{"AndOr":"And","QueryRules":[{"RuleType":0,"Values":["135"],"Columns":["AviationOperation.RegulationFlightConductedUnder"],"Operator":"is"},{"RuleType":0,"Values":["2002-01-01"],"Columns":["Event.EventDate"],"Operator":"is on or after"},{"RuleType":0,"Values":["2021-12-31"],"Columns":["Event.EventDate"],"Operator":"is on or before"},{"RuleType":0,"Values":["Aviation"],"Columns":["Event.Mode"],"Operator":"is"},{"RuleType":0,"Values":["AIR"],"Columns":["Aircraft.AircraftCategory"],"Operator":"is"},{"RuleType":0,"Values":["false"],"Columns":["Aircraft.AmateurBuilt"],"Operator":"is"},{"RuleType":0,"Values":["ACC"],"Columns":["Event.EventType"],"Operator":"is"}]}],"SortColumn":null,"SortDescending":true,"SessionId":795049}

Query text: [
	(RegulationFlightConductedUnder) is (135)
	And
	(EventDate) is on or after (2002-01-01)
	And
	(EventDate) is on or before (2021-12-31)
	And
	(Mode) is (Aviation)
	And
	(AircraftCategory) is (AIR)
	And
	(AmateurBuilt) is (false)
	And
	(EventType) is (ACC)
]

