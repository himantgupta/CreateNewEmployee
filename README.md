# CreateNewEmployee
POST REST - create new  employee if doesnt exist . Dynamo DB + Lambda + API Gateway
End point : https://vsdc77v5ph.execute-api.us-west-2.amazonaws.com/prod/createemployee  .

JSON format in request body
{
		"employeeId": 1, 
		"employeeStatus": "Active",
		"employeeFName" :"Himant",
		"employeeMName" :"N/A", 
		"employeeLName": "Gupta", 
		"employeeBDay":"11-Oct-1996", 
		"employeeJoinDate": "10-Jan-2016"
	}



