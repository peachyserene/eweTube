# EweTube

Finally! a social media platform just for ewe!

# Starting the JSON server

run "npm install"
run "npm start" to open up the html page. It is under [http://localhost:3000]
run "npm run server" to open up [http://localhost:7001/videos]

## Setting this up

If youre curious how I set this up:

1. I ran "json-server --watch db.json --port 7001" in the terminal. 7001 was a random number.
2. Then I edited the package.json file. In the "scripts" section I added
   "server": "json-server --watch db.json --port 7001"
   So any time we used "run server" our custom server location would run.

Never really took the time to understand how these were all working togeather , but now Im glad I know it a little better. Happy to walk you through it so you can understand it also. --Peachy

# Video Embed iframe Template

  <!-- <div className="video-responsive">
    <iframe
      width="853"
      height="480"
      src={`https://www.youtube.com`}
      frameBorder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowFullScreen
      title="Embedded youtube"
    />
  </div> -->

#Logo
<img width="419" alt="Screen Shot 2022-05-27 at 2 22 29 PM (1)" src="https://user-images.githubusercontent.com/102488171/171209726-a80b5b45-7a9f-42f1-9f9b-95df47fb9655.png">

<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/tDQw21ntR64" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

# holding json file data

,
{
"id": 6,
"title": "Shearing A Suffolk Ram ... With Scissors! Plus Treating Scald In Sheep/May 2022",
"link": "https://www.youtube.com/embed/d2HW3W4MomU",
"description": "Today at Ewetopia Farms, we had to bring our big Suffolk ram in from the fields because he was limping. We treated him for scald and then set him up in the barn to recuperate. To make him more comfortable, I decided to treat him to a spa day as well which involved hand shearing him with scissors!",
"channel": "https://www.youtube.com/c/EwetopiaFarms",
"likes": 0,
"comments": []
},
{
"id": 7,
"title": "What are they doing to the SHEEP?! |🐑🧶🧀🇵🇹 | PORTUGAL FARM LIFE S4-E19",
"link": "https://www.youtube.com/embed/eG1UnqrkKIc",
"description": "Its that time of the year where we shear the sheep. I document the process and hang out with some of the local farmers to see how they do things here. We also visit the annual Soalheira Cheese Festival. It runs for a couple of days and they showcase the local farmers products. They have all sorts of stalls, events and music to keep you entertained. We hope you enjoy this episode 🐑🧶🧀",
"channel": "https://www.youtube.com/c/OKportugal",
"likes": 0,
"comments": []
},
{
"id": 8,
"title": "I tried herding sheep, and the sheep won.",
"link": "https://www.youtube.com/embed/T4tcZAduiVk",
"description": "Cammy Wilson from @The Sheep Game invited me to try sheep herding: with a whistle, with his dog Meg, and with a quad bike. Turns out sheep are tricky to deal with. ■ CAMMY: https://www.youtube.com/TheSheepGame/",
"channel": "https://www.youtube.com/c/tomscottplus",
"likes": 0,
"comments": []
},
{
"id": 9,
"title": "Parasite resistant sheep are king on building a profitable grazing operation.",
"link": "https://www.youtube.com/embed/r0FMP793saQ",
"description": " Parasite resistant sheep are king on building a profitable grazing operation. No other farm animal can measure up to the low cost of raising a parasite resistant sheep flock. No inputs required except mineral and a guard dog to protect them. When an animal can average twins each year on pasture, that is an unfair advantage to your benefit while growing your flock. If you want to keep your farm profitable every year, check out my 3 grazing books that I wrote on our website: http://greenpasturesfarm.net/books/",
"channel": "https://www.youtube.com/channel/UCi8jM5w49UezskDWBGyKq5g",
"likes": 0,
"comments": []
},
{
"id": 10,
"title": "Rescued Sheep Makes Himself Part Of The Family | The Dodo",
"link": "https://www.youtube.com/embed/IBiwXH7ooIw",
"description": "Rescued sheep loves to watch TV with his brother",
"channel": "https://www.youtube.com/user/TheDodoSite",
"likes": 0,
"comments": []
},
{
"id": 11,
"title": "Ewe've Been | SHAUN THE SHEEP",
"link": "https://www.youtube.com/embed/ZnVCfN0kT0M",
"description": "Tolong support kami agar lebih semangat dalam membagikan video seru dengan cara subscribe channel kami disini : https://goo.gl/bSiDjD",
"channel": "https://www.youtube.com/channel/UC5Cc7WvO4URdzcgjHPlnuDw",
"likes": 0,
"comments": []
},
{
"id": 12,
"title": "Carolina Ewe Sheep Dairy",
"link": "https://www.youtube.com/embed/P9hjw_TLKps",
"description": "A quick view of the sights and sounds of our Farm.",
"channel": "https://www.youtube.com/user/carolinaewe",
"likes": 0,
"comments": []
},
{
"id": 13,
"title": "Armadale Stock Ewe Lambs 2017",
"link": "https://www.youtube.com/embed/fzc8qXZVZUQ",
"description": "Armadale Farm replacement ewe lambs just after they were weaned and making their onto clean grass after silage. 256 lambs in the bunch.",
"channel": "https://www.youtube.com/user/jypish",
"likes": 0,
"comments": []
},
{
"id": 14,
"title": "Onto The Next Mob! | Shearing Merino Ewes | Australian Sheep Farming",
"link": "https://www.youtube.com/embed/W3l0PAi9N8M",
"description": "Shearing the last of all our ewes today! Just young sheep left which is great. Hope you enjoy.",
"channel": "https://www.youtube.com/channel/UCpcvhIgBPN6Cd20pbcadawA",
"likes": 0,
"comments": []
},
{
"id": 15,
"title": "giant Dorper sheep - South African",
"link": "https://www.youtube.com/embed/FWW8EDeoLQs",
"description": "On this channel you can find super cool videos... videos from farms all over the world, I hope you like it",
"channel": "https://www.youtube.com/channel/UCNuZrpIuGeAWJbfKaTPfCRA",
"likes": 0,
"comments": []
},
{
"id": 16,
"title": "Black belly sheep in Barbados, June 2011",
"link": "https://www.youtube.com/embed/jK7bQlqO7zs",
"description": "we came across these black belly 'sheep' in Barbados while our driver Leroy was taking us around the east coast",
"channel": "https://www.youtube.com/user/luvmyfrenchie",
"likes": 0,
"comments": []
},
{
"id": 17,
"title": "Hebe, Greyface Dartmoor ewe lamb for sale, Moorparks, Devon.",
"link": "https://www.youtube.com/embed/GjBHQVBV1HM",
"description": "Hebe is one of this years (2021) Greyface Dartmoor ewe lambs for sale. Hebe will not be registered as she has too much black on her knees.",
"channel": "https://www.youtube.com/channel/UCwy8Y8KKp6hsi2VcMz7g_tA",
"likes": 0,
"comments": []
},
{
"id": 18,
"title": "Cladoir sheep hand shorn demonstration & Malcolm Noonan shears a ewe",
"link": "https://www.youtube.com/embed/rWYHARWZLaQ",
"description": "This was in June 2021 when the Cladoir project was launched at the Connemara National Park. A first time for everything. Irish politician Green Party member, Malcolm Noonan - Minister of State Heritage Environment and Electoral Reform. He also learns about counting sheep teeth to age a sheep.",
"channel": "https://www.youtube.com/c/ZwartblesIreland1",
"likes": 0,
"comments": []
},
{
"id": 19,
"title": "Suffolk-cross Mule ewe lambs",
"link": "https://www.youtube.com/embed/lprXC6jJ49U",
"description": "Suffolk-cross Mule ewe lambs on the farm of Richard and Sarah Woodmartin.",
"channel": "https://www.youtube.com/c/AgrilandIreland",
"likes": 0,
"comments": []
},
{
"id": 20,
"title": "Suffolk Ewes",
"link": "https://www.youtube.com/embed/aGSwCrJGz4I",
"description": "Mixed age Suffolk ewes. Auctions + 21/2/17",
"channel": "https://www.youtube.com/channel/UC9grc6E6jhc4mXPHfoFb06w",
"likes": 0,
"comments": []
},
{
"id": 21,
"title": "A Sheep Song for Ewe",
"link": "https://www.youtube.com/embed/4o8rM-X4IvE",
"description": " A Sheep Song for Ewe. Sheep, lambs, rams, ewes, farm, ballad, humor.",
"channel": "https://www.youtube.com/c/MichaelThornleyWildlifeFoundation",
"likes": 0,
"comments": []
},
{
"id": 22,
"title": "Ewe Dall sheep & her lamb near Windy Point- Seward Highway, Alaska.",
"link": "https://www.youtube.com/embed/7eDnu7cWV0o",
"description": "Windy Point is the only place in the world where Dall sheep can be seen close to sea level. Turnagain Arm is a waterway into the northwestern part of the Gulf of Alaska. It is one of two narrow branches at the north end of Cook Inlet, the other being Knik Arm. The Seward Highway follows a portion of the southern edge of the Chugach State Park along Turnagain Arm. Turnagain Arm boasts the second highest tides in North America after the Bay of Fundy. These tides, which can reach 40 feet and come in so quickly that they produce a wave known as a bore tide. The Seward Highway stretches 125 miles from Seward to Anchorage. Life Magazine named this stretch of road one of the most beautiful scenic drives in the world.",
"channel": "https://www.youtube.com/user/TravelGuideBook",
"likes": 0,
"comments": []
},
{
"id": 23,
"title": "GOT SHEEP? Ewe and Ram Genetic Considerations",
"link": "https://www.youtube.com/embed/TxKHZ0v2DSQ",
"description": "Managing genetic risks in your flock.Link to the tools www.uwyoextension.org/ranchtools",
"channel": "https://www.youtube.com/channel/UCCYWyqR7Je_UsSWeq0aTSyQ",
"likes": 0,
"comments": []
},
{
"id": 24,
"title": "John T Wedlock - Australian White Ewe Lambs",
"link": "https://www.youtube.com/embed/HOepMynGhaI",
"description": "",
"channel": "https://www.youtube.com/channel/UCb4W5IPonOJNEnjkM3wJjYw",
"likes": 0,
"comments": []
},
{
"id": 25,
"title": "HERDING Corriedale Ewe SHEEP into Stockyard on Small Farm with Honda ATC110 at Rusted Iron Ranch",
"link": "https://www.youtube.com/embed/Drmj1RfD3JY",
"description": "Welcome to Rusted Iron Ranch! Today we move my mates sheep with the help of the Honda ATC110 into the stockyards so they can moved to another farm.",
"channel": "https://www.youtube.com/c/RustedIronRanch",
"likes": 0,
"comments": []
}
