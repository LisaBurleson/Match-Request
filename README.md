# Match-Request
Match visiting players to local players or other visiting players

wailea tennis club - match request (MR)

wants a digital way to record MR, wants search, needs something easy to use.

Use Case:
1. Create Match Request
2. Search Match Request
3. Edit Match Request
4. what else does the user need to do?
	
Background:
- Match requests are made by players visiting the islands, the pro shop 
- will try to match other visitors or locals to their skill level and times.
- Match request have a specific lifetime. Vistors can come back to the island several times over time.
	
Features:
- initial view should show...active match requests?
- there should be some mechanism to auto-match active match requests
- there should be an auto fill as much as possible in capability when creating a MR 
- should have a google map link
- capture who created the match request
- app should have easy startup and shutdown, windows service?
- player information should be encrypted
- users are authenticated
	
Architecture:
- Docker?
- Node?
	
Technology:
- Vue.js
- graphql?
- mysql/postres
- eleaticsearch?
