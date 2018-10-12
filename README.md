# BeSafe
The motive is to spread awareness regarding in disaster measures in an interactive manner so that the user prepares well in advance for the crucial moments decisive in his life and death, where before anyone else he could prove to be a rescuer to himself. When the unfortunate situation presents itself the app presents the user with some life saving tools in sequential manner which maintains his connectivity to the outside world ensuring his safety.

The idea revolves around three central features : The Assistant, V-Scale(Vulnerability scale) & Q-Bot(Query/Questionnaire bot)

The Assistant: Assistant works in two modes: Setup Mode, Assist Mode    

Setup Mode: It is basically pre disaster setup to handle scenarios when the disaster occurs. In it we will have several       
functionalities as mentioned: one functionality is that user would be able to set contacts of some close relatives to be notified of their location and wellness status at the time of disaster, also he will be granting several permissions to activities to be undertaken automatically when triggered by a homescreen button at the time of disaster. Activities such as setting cellphone in power saver mode, sending SOS, Location acessibility(if online), location snapshot(last location :if offline). In setup mode a checklist of current status of disaster handling kit would also be there.

Assist Mode: This mode comes into action as soon as the user presses the button on his homescreen. This in turn triggers the pre set commands in the setup mode and launches an interface with several activities on the screen presenting the user with various options such as : siren button, rescue operation feed, map(rescue outreach, vulnerability plot depicting safe and affected routes/regions), local help forum, Q-bot(as a Query Bot). 

V-Map : The V-Map will be a real time map formed by plotting a vulnerability score of all the regions. The score of a particular area which ranges from 1-10 shows the proneness of a region to disasters and itwill be calculated using the weather forecast and historical data. This data can be fetched using [openweathermap API](https://openweathermap.org/api). Further this feature can be expanded by including the infrastructure data which can be filled by the users. This data can be helpful for both floods and earthquakes and once the vulnerability score of a region reaches a threshold all the users within the area will be notified of an incoming calamity.

Qbot: Query/Questionaire mode is the part of the app where we will access the database consisting of life hacks hosted on Azure for the help of the user.

Pre Disaster: The app will present users with some interesting scenarios as questions from time to time related to disaster management which will help spread awareness and make users well-prepared for any kind of disasters. There will be a rating from 1 to 10 based on their preparation levels to tackle a disaster situation. This rating will improve as the user resolves the scenario questions posed and most importantly this provides users with options to set actions or suggestions that the assistant automatically takes care of in Disaster mode. 

During a disaster: This mode will become Questionare mode during the disaster, where all our users can access th FAQs and data in an organised and user-friendly manner. 
