🌴 Archipelago Adventure 🌴
Welcome to Archipelago Adventure, a web-based educational game that invites players to explore iconic places across the Indonesian archipelago, maintain their character's wellbeing, do activities and complete achievements.


  🕹️ Gameplay Rules 
Character & Difficulty Setup
- 	Choose 1 of 3 characters and input a name.
- 	Select a difficulty mode:
Easy	   : 3 hearts, access to all maps except Mount Bromo.
Medium	 : 2 hearts, Mount Bromo and Borobudur Temple are locked.
Hard	   : 1 heart, only Lake Toba map is unlocked.
- 	Missing Maps can be unlocked through specific activities

  Player Status Management 
Players must maintain four key status bars:
Hunger 	- Manage by eating food at various locations
Energy 	- Replenish by sleeping or resting
Hygiene 	- Maintain through bathing activities
Happiness - Boost by exploring and completing fun activities
Life Satisfaction Score	: Calculated from the balance of these four stats, visited areas, completed achievements, leveling exp, and unlocked items.

- Heart System:
Each stat hitting 0 costs one heart.
If all hearts are lost, the character dies and the game ends.
Warning and critical alerts notify the player when hearts are low.

- Stats decrease over time:
Decrease by 1% every 30 seconds.
Some actions (like hiking or eating) cause additional decreases/increases.
Status bars gradually decrease over time and are affected by your actions.


  🗺️ 	Exploration 
Navigate through different Indonesian landscapes:
Main Map 	 - Central hub connecting all locations
Lake Toba	 - Fishing and water activities
Kuta Beach	 - Beachside fun and relaxation
Mount Bromo 	 - Hiking and nature exploration
Borobudur Temple  - Cultural experiences
Each location offers unique activities and interaction
- Trap System	: Hidden traps cause 20% energy damage. They relocate every 15 seconds to random spots. Once triggered, traps are disabled for 5 seconds to allow escape.
- Collision System	: Players can't move through obstacles like trees, rocks, or buildings. Collisions cause a shake effect.
- Mini-map System	: Each area includes a minimap view to assist in navigation.


🏆 	Activities & Achievements 
Perform various activities at each location like:
- Fishing, boating, sightseeing
- Hiking, camping, cooking
- Shopping, photography, journaling
- Cultural activities like lantern flying
  
- Unlock items and achievements as you explore
- Over 40+ interactive activities, each with its own popup and effects on stats and EXP.

- Achievements & Unlockables:
Complete milestones to earn achievements.
Unlock activities using certain items (e.g., a tent to enable camping).
View achievements in the ID Card located in the title bar interface (flip to see achievements).


🔒 	Locked Actions and Their Requirements: 
- Fishing	                  : Fishing Rod, Bait, Bucket
- Capture the Moment 	      : Camera
- Hiking Journaling	        : Journal
- Hiking	                  : Shoes
- Observe Nature	          : Binocular
- Observing Borobudur       : Binocular
- Build a Campfire	        : Wood, Matches
- Learn Coral Ecosystem	    : Fauna Book
- Observe Small Marine Life	: Magnifying Glass
- Tanning	                  : Towel
- Build Sandcastles	        : Sand Bucket, Sandal
- Rest & Eat Food	          : Food, Drink
- Gather Spring Water	      : Bottle


  🔑 	How to Unlock Items:
Many of these actions require specific items to be unlocked first. Here's how you can unlock the necessary items:
- Fishing Rod	        : Buy from the shop at Lake Toba.
- Bait	              : Buy from the shop Lake Toba.
- Bucket	            : Buy from the shop Lake Toba.
- Journal	            : Buy from the shop at Borobudur Temple.
- Binocular	          : Buy from the shop at Lake Toba.
- Wood	              : Collect Firewood  from Mount Bromo map.
- Fauna Book	        : Unlocked by visiting the museum at Borobudur Temple map.
- Magnifying Glass	  : Buy from the shop Borobudur Temple map.
- Towel	              : Unlocked by bathing at Lake Toba map.
- Sand Bucket	        : Buy from the shop at Kuta Beach map 
- Sandal	            : Buy Sandals from the shop at Kuta Beach map.
- Food                : Unlocked by cooking food at Mount Bromo Map. 
- Drink	              : Buy from the shop at Borobudur Temple map or gather spring water at Mount Bromo Map.
- Bottle	            : Unlocked by eating at Lake Toba Map.


  ⌛ 	Time System 
- Game features a day cycle with dynamic time
- Time affects status bar 
- Starts synced with real time, then switches to 1 in-game minute per 1 real-world second.
- Includes greetings like “Good Morning” and “Good Night”.
- Fast Forward mode available for quicker activities.
- There is also calendar feature where it is based on real world day, date, month and year.


  💵 	Money 
- Start with 100,000 IDR
- Earn money by working (example: becoming a tour guide or cashier)
- Spend money on items like:
Fishing rods, buckets, bait
Binoculars, sandals, food
- Economy System:
Player actions like buying items or doing activities impact wallet balance.
Money can also help unlock items required for activities.


  🎮 	Controls 
- Keyboard Arrows: Move your character
- Action Menu: Interact with location-specific activities
- Fast Travel: Return to main map from any location
- Fast Forward: Speed up activity time
- Challenges:
Manage your status bars carefully - if any reach zero:
Lose one heart (depends on the difficulty mode that you choose)
Get reset to default status if you have remaining hearts
Game over if you lose all hearts
Balance your activities to maintain all status levels


  ⚒️ Technical Implementation 
Core Features
- Dynamic map navigation with smooth movements
- The Area System have 4 Explorable Maps: Lake Toba, Kuta Beach, Mount Bromo, Borobudur Temple. Each map has unique locations triggering context-specific actions (e.g., "Eat/Sleep/Bath" at Home in Lake Toba).
- Difficulty System (easy gives you 3 hearts, medium gives you 2 hearts and hard mode gives you only 1 heart) you need to survive with given hearts.
- Responsive design for multiple screen sizes
- Popups for activities, doing activities can unlock items and achievements.
- Score System (calculated from stats balance, unique activities performed,  unlocked items, and visited areas).
- Inventory system (you can check all your locked and unlocked items inside backpack).
- Stats bar includes (hunger, energy, hygiene, happiness)  where you need to keep it balanced to survive by doing activities.
- Time system (Time clock with greetings (example: "Good Morning", “Good Afternoon”, “Good Night”, stats decrease over time too). There is also a calendar feature where it is based on real world day, date, month and year.
- Persistent player data (name, appearance). 
- Minimap shows the entire map so you know where you’re going, and each location has minimap
- Fast Forward mode to speed up time during certain actions.
- Character System:
Player name appears above the avatar.
Alert if you don't enter your name.
Character emerges from a hole at game start and returns to hole upon death.

B. 	Game Systems
Activity System	    : Timed actions with status effects.
Inventory System	  : Locked and unlocked items can be seen in a backpack.
Location System	    : Unique activities will show up per map area.
Economy System	    : Earn and spend money.
Scoring System	    : Life Satisfaction Score calculated from stats balance, unique activities performed,  unlocked items, and visited areas. Level (exp) starts from level 1, you can gain (exp) from doing activities.
Challenge System 	  : We have 3 difficulty modes : easy, medium, hard, if hard the game will be harder to play and there will be more challenges.


  🎶 Audio Features 
- Background music
- Main sound
- Volume bar slider which you can adjust in the Game Page.

- 
D. 	How to Play
1. Create your character by choosing a name and appearance.
2. Explore the main map using arrow keys or on-screen controls.
3. isit locations and do activities/actions to unlock maps.
4. Interact with location-specific activities.
5. Manage your status bars to stay healthy by doing actions
6. Earn money to buy new items. Unlock activities and achievements from items that you collect. 
7. Discover all the activities each location has to offer.


📝 	Notes
The game emphasizes:
- Cultural appreciation of Indonesian landmarks
- Balance between exploration and self-care
- Economic management through earning and spending
- Discovery through interaction with diverse environments
- Transition Zones (Entering these areas and shows actions) :
Default Map:
- Lake Toba	    : In the lake area bottom right of the default map.  
- Kuta Beach	  : The corner of the map where there is a palm tree.
- Mount Bromo	  : Mountain Area of the map.
- Borobudur Temple	: Temple on the right side of the Mountain.
Lake Toba Map: 
- Home	        : At the left corner of the Lake Toba map. 
- Bites Shop	  : Around the right side from Home.
- Dockside Shop : Bottom-right from Bites Shop. 
- Fishing Dock 	: Far bottom-right below the Dockside Shop where there is a brigde.
  
Mount Bromo Map: 
- Mountain Peak	    : At the peak of the mountain.
- Mountain slope	  : Around the trees. 
- Campground 	      : On the ground area.
  
Borobudur Temple Map: 
- Shop	            : Below the temple.
- Temple	          : Top part of the map.
- Ceremony Grounds	: Beside the temple.
  
Kuta Beach Map: 
- Seaside Shop	  : Above the sand area.
- Sand Area	      : Area where there are seashells.
- Beach Shore	    : Where the starfish is located.


F.	Contributors 🧑‍💻
Britney Jessica Saslim /115790
Felicia Aulia Suherman /136309
Josiah Maximus Suryadi /108749
Michelle Olivia Herijanto /114755
