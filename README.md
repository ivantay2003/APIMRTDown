# MRT Status API
<br><br>
This api will filter out Singapore MRT down time in  twitter and reddit social media if anyone is complaining. Examples of complain in Twitter which this will service will detect :<br>
Twitter <br>
"mrt breakdown bugis waited very long" 
<br>
"no train in clementi fault smrt"

<br><br>

## Method of calling (GET method)
<br><br>
Twitter<br>
host/api/v1/getMRTTwitter/
<br><br>

Redit <br>
host/api/v1/getMRTRedit/
<br><br>

If there are no message, the JSON return is 
<br>
{
"status": 200,
"message": "null"
}

<br><br><br>

If there is a mrt down that is feedback in twitter , the JSON return is 
<br>
{
"date": "Thu Jan 03 09:16:20 +0000 2019",
"text": "tampines west #sbstransit delay testing ignore",
"id": 1080754726231101400,
"screen_name": "ivan_tay",
"name": "tampines",
"line0": "EWL",
"line1": "",
"line2": "",
"line3": "",
"line4": "DTL",
"line5": "",
"line6": "",
"line7": ""
}

<br><br>

The legends EWL or DTL are different MRT lines. There are DTL , CL , WEL and NSL currently
<br><br><br><br>
Plese contact me at my [Linkedin](https://www.linkedin.com/in/ivantay/) if you want to try this service.

