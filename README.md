Name: Álvaro Maza Montesinos
PID: 17655072
Link of submission: https://lucent-semifreddo-222d61.netlify.app/

Notes:

The put and delete requests URLS should have the form of https://httpbin.org/put/123 or https://httpbin.org/delete/123
where 123 is the id, but this was not possible because of CORS policies, so I wrote them as 
https://httpbin.org/put?id=123 and https://httpbin.org/delete?id=123 to try to add a little bit of logic.
With the same reasoning, in the payload of the PUT request, I included all the fields except ID, and in the DELETE request 
I did not put any fields, since you would be erasing the post with ID 123 (you dont care about the fields).
For the POST and GET request I follow what we saw in class (fields in payload for POST request, fields in URL with ? in GET request).

For the webcomponent part, I took the liberty to style the button for fun, I hope this is not incompatible with what is stated in the HW
guidelines (button-count behaves as shown in video (8 points)).

Lastly, to deploy the React app, I used a different Netlify URL. I know we should not reference other links in the main page,
but i was not sure on how to deploy a react app without it being the index.html, so i did it that way. I will anyways send the 
extracredit.html and extracredit.jsx as how it should have been if it was not an index.html.

Thanks for taking the time to read these clarifications, have a good day :).