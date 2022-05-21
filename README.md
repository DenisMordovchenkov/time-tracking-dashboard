# Frontend Mentor - Time tracking dashboard solution


In this challenge I used pure javascript, css and html.
The layout is semantic, adaptive. Mobile-first.

Requests to the json file were made using fetch and async await.


The logic is as follows: a listener of the DOMContentLoaded event is hung on the page, in which an asynchronous request to the data file occurs, in our case this is data.json.

And then we map on the received data by passing them to the class created in advance. In the class, in turn, using two methods createMarkup and ChangeView, a markup is created where the data from the promise is substituted.

By default, statistics for the month are displayed, passed by the default parameter to the class. And to output statistics for a day or a week, a selection of style classes is made on which the event listener is hung by click.In the loop, the сhangeView method is called, which changes the statistics data for each card

You can try demo here https://time-tracking-dashboard-cyan.vercel.app/
