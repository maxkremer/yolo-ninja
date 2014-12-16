#Trialfire: Next Gen Web Analytics, Backed By Stormpath

Trialfire’s new visual editor for marketing analytics allows anyone to “pin” parts of a web page, such as a signup button, and track the event data automatically in multiple analytics systems: Google Analytics, Mixpanel, Kissmetrics, and more.

“You don’t have to be technical. You just connect your site and place your pins,” explains Max Kremer, Co-founder of Trialfire. Trialfire takes development out of the equation when it comes to setting up detailed click-tracking or analytics. “You can just click through your site and magically track whatever you want.”

[image - stormpath website w/trialfire loaded]

With a long list of customer requirements, and some high-profile beta customers like the Discovery Channel, Trialfire needed a way to save some coding time, skip the tedious user management programming, and move on to more complex, and disruptive, software design. 

##The End of Custom Instrumentation

Trialfire was born out of Kremer’s first startup:

“My Co-founder Mike used to always bug me about getting data to see how engaged users were. We have free trials, are they working or are they not working? How deep are users getting? It was hard to tell because, so it’s much more complex to get the right analytics out of a web app.”
It wasn’t just a problem for startups. Historically, if any company wanted better insight than just page views, a developer has to insert custom code, instrument each button and link, and connect them back to analytics systems like Google Analytics by hand. 
When the company was acquired by Autodesk, Kremer saw the same analytics problems amplified as Sales, Marketing, and Product teams tried to coordinate on a cohesive set of events.

###Weeks Of Development Time Saved

Built on a Java-based backend, with Solr for indexing, Akka for message processing and a very lightweight AngularJS frontend, Trialfire uses Stormpath to handle registration, login and password security and workflows.

“Initially the idea was to not do all of that boilerplate user stuff. ”

Trialfire needed a quick, straightforward solution for user account handling. Integrating the Stormpath API for a hosted authentication service and user store saved Max several weeks of development time. 

“We needed people to sign up. A user database or table or collection or however you happen to store your users. You need to do all the password stuff. You need to send verification emails. If I can use a service to do all that for me, then perfect. Especially if that service gives me other capabilities that I don’t have.”

[image - trialfire signup screen]

Trialfire integrated Stormpath’s API for its simplicity, but also its extensibility. Adding Google+ or Facebook authentication is a quick change to the Stormpath SDK. 

Stormpath’s advanced password security also saves the Trialfire team maintenance work. 

“Having to manage security is a drain because it means that we have to write automated tests, perform manual testing and ensure we conform to various security standards. In addition to the above you have to worry about threats to security such has hackers. Offloading these concerns to Stormpath allows us to breath easy AND frees up resources to work on core product.”
