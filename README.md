# CovidTracker
Work with me to build a covid19 (coronavirus) tracking app with fantastic privacy!  It also offers high usage efficiency.

Here's the strategy:

Each tracker app maintains a database of where I have been, probably for the last 14 days.  Each tracker app pings in once per day (maybe twice) to see if I have crossed paths with any reported infections.

When a person is identified as infected, with their permission their data is uploaded to the "infected paths" server.  There is no need for that server to contain any information that identifies the patient.  There is no need for the database to reveal anybody's paths at all.  (CDC agents may also want access to a patient's data logs.  They would be able to use these logs to decect contamination with those who don't have  the app.)

The once per day query would look something like this:  A rectangle of where "I" have been in the last 14 days is sent to the server for validation.  If its clear, checkin is done.  If its not, then the smaller rectangle representing each day is sent in for validation.  This may clear a person.  If this is not sufficient, further handshaking (possibly the server sending a list of contact points/times) will determine whether I have crossed paths with a known infection.  If I have crossed path with an infection, I am advised to get tested.

This monitoring approach will not be effective in the heat of this virus, but will become particularly valuabie when the virus is mostly contained.  Hopefully it would allow the world to feel comfortable to get out of seclusion and back to living more quickly.
   
This project would be public, and free.  I believe I have the necessary connections to get the Canadian government to flog it to their citizenry.

Hey, if you have particular interest in making this thing happen, consider giving me, Bruce Fast, a phone call at 867-332-1005.
