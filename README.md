# rewards-api

URL: localhost:8080/rewards

Request: 

[
    {
        "customerId": "John Smith",
        "transactionAmout": 220,
        "transactionDate": "2022-02-16T18:45:50.408Z"
    },
    {
        "customerId": "Chris Johnson",
        "transactionAmout": 120,
        "transactionDate": "2022-03-16T18:45:50.408Z"
    }
]

Response: 

{
    "John Smith": {
        "FEBRUARY": 290
    },
    "Chris Johnson": {
        "MARCH": 90
    }
}
