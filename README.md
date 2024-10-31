Using the api provided by Hivemappe, 
you can generatt the daily uploaded kms chart
for any user by providing the three word username 
then if there's data available, 
the json data will be returned in the text box. 
After that by pressing the generate button a chart will
visualise the data in a chart.

Due to some restorations in Cross-Origin Resource Sharing (CORS)
I was unable to directly generate a graph from the retrieved API data
and I've had to utilise the Cors-anywhere demo that's provided by 
https://github.com/Rob--W/cors-anywhere
To avoid spamming and missuse, a demo version is available for public use
which is limited to 50 queries per hour and the user is required to request access 
by following the instructions in the link below:

https://cors-anywhere.herokuapp.com/corsdemo

the html wile will not function without requesting access.
