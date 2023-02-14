# How to run

```node express_booter.js [MethodRequest] [Objetive] [time] [rate]```

To run the above code, you will need to open the terminal or command prompt in the directory where the code is saved and then type the following command:

Where:
`[MethodRequest]` is the HTTP request method, such as `GET` or `POST`.

`[Objetive]` is the URL that you want to send the request to.

`[time]` is the amount of time the script should run.

`[rate]` is the rate of requests per second that you want to send.

For example, if the file name is script.js, the MethodRequest is `GET`, the Objetive is `https://www.example.com`, the time is "60" seconds and the rate is "10" requests per second, the command would be:

```node express_booter.js GET https://www.example.com 60 10```

This will run the script for 60 seconds, sending 10 GET requests per second to the specified URL.

