## Pitch
Sometimes you want coffee, but you don't want to just pick your drink. You want to pick your experience too. Get Joe Coffee finds the 3 closest cafes nearby, one of each type: Chain, Quick, & Sitdown.


## Inspiration
You ever begin a hackathon and realize just how tired you are? But, like, where are you? Where's a good coffee around here? I guess you could ask a Princeton student, but what if they don't appreciate coffee like you do? What if they recommend a Starbucks, god forbid. You want your coffee, your way, and you don't want to go far. Introducing Get Joe Coffee. 

## What it does
Get Joe Coffee finds the three nearest coffee-selling establishments nearby, one of each specific category -- Chain, Quick, or Sit-down. You'll immediately know where to go to get the cup of your choice. In the mood for mediocre consistency? There's a Starbucks down the road. Need to grab-and-go your joe before grinding out your lab report for class tomorrow? There's a speedy cafe to the right. What if you just want a place to hang for an hour or two while meeting a friend? Sip on your favorite drink at a sit-down spot two blocks that way! Save some energy, take a peek at what's nearby and decide!

## How we built it
We chose to build a web application so it could immediately be accessible to any device. On the backend, we took data from different Google APIs and leveraged GraphQL to provide our frontend with a singular endpoint. The client sends its current location to our Node server, which replies with the closest cafes of each type. The client displays these spots on the map. The website is designed to be fully responsive for any device screen size or orientation. The next steps would be to add routing to each of the spots and refine the UI. However, all of the required mechanisms on the back-end are in place. 

_Backend:_
Apollo-Server (GraphQL), Google Places API, Google Distance Matrix API

_Frontend:_
React.js, Apollo-Client (GraphQL), Google Maps API

## Challenges we ran into...
The largest challenge we ran into was hosting our web application on a domain. We had trouble hosting our Apollo Server. We also encountered some issues with connecting our frontend and backend. It was an access issue relating to CORS, fixed by simply changing "https" to "http" -- amazing.   

## Accomplishments that we're proud of!
We're most proud of our idea! We're excited to to continue developing it once we get back to school. 
We're also so proud of our problem-solving abilities during the day, and the ability to quickly decide what to prioritize.
We are also so proud of one of our team members for participating in his first Hackathon.

## What we learned!
We learned a lot about the technologies we used: React, Apollo, and Google APIs. As the day went on, we were able to better manage our workflow. 
