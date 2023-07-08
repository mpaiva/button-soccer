# Project: Button Soccer NFT
By Marcelo Paiva - July 8, 2023

## Description

Button football or button soccer is an association football simulation game played on a tabletop, using concave buttons or special-made disks to represent players on the pitch (field), often with a larger rectangular block as the goalkeeper piece.

Board dimensions, markings, and rules of play are modeled to simulate standard football. It is popular in Brazil, as well as various countries in Europe, including Hungary, Georgia and Slovenia.

The goal is to fabricate button soccer teams to start a league to unite parents and children in this craftsmanship adventure.

Each team owner will receive a team of 10 players and 1 goal-keeper crafted by hand in acrylic. Along with the physical soccer team, the owners will also receive a digital certificate of ownership as a non-fungible token (NFT).

A QR code will be visible underneath each player. This code is the unique ID for the player's NFT Certificate.

## Execution Plan

1. **Fabrication of Button Soccer Teams:** Create the button soccer teams by hand. Ensure each team consists of 10 players and 1 goalkeeper. Attach a QR code underneath each player.
2. **Creation of Digital Certificates:** Each digital certificate should be unique and tied to a specific player. The certificate should include key information such as the team name, player's name, player's position, and unique ID (matching the QR code).
3. **Minting of NFTs:** Use a blockchain platform that supports NFTs, such as Ethereum, to mint the NFTs for each player. The NFT should be linked to the digital certificate of ownership.
4. **Distribution to Owners:** Once the button soccer teams are ready and the NFTs are minted, distribute them to the owners. The owners can then scan the QR code to access their digital certificate and NFT.
5. **Community Building:** Start a league and organize matches and tournaments. This will help build a community around the button soccer teams and increase the value of the NFTs.
6. **Marketplace for Trading:** Develop an online platform or marketplace where owners can trade players and teams. This adds another layer of engagement and could potentially increase the value of the NFTs.

## UX Design Brief for NFT Button Soccer App

### Overview

The NFT Button Soccer App aims to provide an engaging and user-friendly platform for team owners, league organizers, and referees to manage their button soccer teams and leagues. The app should allow users to view and manage their teams and players, track player stats, schedule and participate in tournaments, and trade players and teams.

## User Groups

This app will primarily serve four user groups. These user groups have overlapping but distinct needs and will interact with the app and each other in different ways. Therefore, the app will need to offer tailored experiences for each group. This will involve personalized dashboards, notifications, and functionalities for each user type.

1. **Team Owners:** These are the individuals who own the teams. They will have the capability to manage their team and player rosters, view player stats, participate in tournaments, and potentially trade players or teams. They can also designate a Team Captain for each match.

2. **Team Captains:** These are individuals designated by the Team Owner to lead the team during a match. They have access to their team and player stats to strategize gameplay. In many cases, the Team Captain and Team Owner will be the same individual, but a Team Owner may also designate someone else to be the Team Captain for a match.

3. **League Organizers:** League Organizers administer button soccer leagues and tournaments. They should be able to schedule tournaments, manage team registrations, oversee the league standings and track team and player stats. They may also assign and nominate people to fulfill the role of a Referee, manage any disputes or rule violations.

4. **Referees:** Referees will have the authority to log the outcomes of matches, which will include match results, player stats, and any noteworthy incidents during the game.

These user groups have overlapping but distinct needs and will interact with the app and each other in different ways. Therefore, the app will need to offer tailored experiences for each group. This will involve personalized dashboards, notifications, and functionalities for each user type.

### Features and Functionality

1. **Team and Player Management:** Users should be able to view and manage their teams and players. This includes viewing player stats and tracking their performance over time.
2. **Tournament Scheduling:** League organizers should be able to schedule tournaments and manage team registrations.
3. **Match Logging:** Referees should be able to log match results and player stats.
4. **Trading Marketplace:** Users should be able to trade players and teams with other users. This could include a bidding system for trades.
5. **NFT Integration:** The app should integrate with the blockchain to support NFT ownership and trading.

### Technology Stack

The app should be developed as a mobile app for iOS and Android, with potential for a web version. It should use a blockchain platform that supports NFTs, such as Ethereum, for the NFT functionality. A peer-to-peer architecture could be used for the trading marketplace to enable direct trades between users.

## Key Indicators
The following information may be useful to track and display to certain user groups:

### For All Users (General Stats):

1. **Top Players and Teams:** Ranking of players and teams based on performance, popularity, or value.
2. **Upcoming Matches:** Details of upcoming matches or tournaments.
3. **Market Trends:** Trends in the marketplace, such as the most traded players, average player value, etc. 

### Team Owner Views Team and Player Stats:
A team owner opens the app to view their teams and players. They can see each player's stats and track their performance over time. They decide to trade one of their players to improve their team.

#### Player Stats Metadata

The NFT metadata for each player could include:

1. **Player Name:** The name of the player.
2. **Team Name:** The name of the team to which the player belongs.
3. **Position:** The player's position in the team.
4. **Skill Level:** The player's skill level, potentially determined by game performance.
5. **Number of Games Played:** The total number of games the player has participated in.
6. **Number of Wins:** The total number of games the player's team has won.
7. **Number of Goals:** The total number of goals the player has scored.
8. **Unique ID:** A unique identifier for the player. This should match the ID on the physical player piece.
9. **Player Growth:** The change in the player's performance over time, indicating their development and potential.
10. **Team Performance:** The overall performance of the team, such as win-loss ratio, average goals per game, or number of clean sheets.
11. **Player Value:** The current market value of the player based on their performance and demand in the marketplace.


#### Team Stats metadata
Additional stats that could be offered to different users include:

1. **Team ID:** A unique identifier for the team. This could be a combination of the owner's name/ID and a sequential number (e.g., "johnsmith01").
2. **Creation Date:** The date the team was formed.
3. **Owner:** The current owner of the team.
4. **Current Value:** The current estimated market value of the team based on the collective value of all players and their performance.
5. **Total Matches:** The total number of matches the team has played.
6. **Wins/Losses/Draws:** The team's record of wins, losses, and draws.
7. **Total Goals Scored:** The total number of goals scored by the team.
8. **Total Goals Conceded:** The total number of goals conceded by the team.
9. **Clean Sheets:** The number of matches where the team didn't concede any goals.
10. **Top Scorer:** The player from the team who has scored the most goals.
11. **Most Valuable Player (MVP):** The player from the team with the highest performance rating.
12. **Trophies/Achievements:** Any trophies or achievements the team has earned in tournaments or leagues.
13. **QR Codes:** The individual QR codes of each player in the team.
14. **Historical Performance Graph:** A graph or chart showing the team's performance over time.
15. **Team Logo:** A digital representation of the team's logo.

#### League Stats

1. **Participation Stats:** The number of teams participating in the league or tournament, the number of matches played, etc.
2. **Audience Engagement:** The number of spectators or viewers for the matches, the level of engagement on social media platforms, etc.
3. **Tournament Performance:** Overview of each tournament, including the number of matches, goals scored, and audience engagement.
4. **Dispute Stats:** Number of disputes in each match, the nature of disputes, how many were resolved, etc.
5. **Rule Violations:** Stats related to rule violations by teams or players during the matches.
6. **Performance Reviews:** Feedback or reviews from teams and league organizers about the referee's performance.

Each of these attributes can provide valuable information about the team and make the Team NFT more interesting and valuable to potential buyers. Please note that the value of certain attributes such as "Current Value," "Wins/Losses/Draws," and "Total Goals Scored" would need to be updated over time to reflect the team's ongoing performance.

## Use Cases

### Team Owner Participates in Tournament:
A team owner registers their team for an upcoming tournament. They participate in the tournament by playing matches against other teams. The results of these matches are logged by referees and the team's stats are updated.

### Team Owner Designates Team Captain:
A team owner opens the app to view their teams and players. They decide to designate one of the team members or an external person as the Team Captain for an upcoming match. This change is updated in the team's profile.

### Team Captain Views Team and Player Stats:
A Team Captain opens the app to view the team they are leading and the respective players. They can see each player's stats and use this information to strategize for an upcoming game.

### Team Captain Leads in a Tournament:
A Team Captain leads their team in an upcoming tournament. They participate in the tournament by playing matches against other teams. The results of these matches are logged by referees and the team's stats are updated.

### Team Owner and Team Captain Discuss Strategy:
The Team Owner and Team Captain use the app's communication features to discuss the upcoming game and strategy. They review player stats together and decide on the formation and game plan.

### Team Captain Provides Feedback:
After a match, the Team Captain provides feedback on the team's performance via the app. This could include individual player feedback, which might be useful for the Team Owner and the players for future matches.

### League Organizer Schedules Tournament: 
A league organizer schedules a new button soccer tournament. They set the date, time, and rules for the tournament. They then open registrations for teams to participate.

### Referee Logs Match Results:
A referee officiates a button soccer match. After the match, they log the result and the players' stats in the app. These stats are then reflected in the teams' and players' records.

### User Trades Player:
A user decides to trade one of their players. They list the player in the trading marketplace with a set price. Another user sees the player and decides to purchase them. The trade is facilitated by the app using the underlying blockchain technology to transfer the NFT ownership.

----

## UX Design Deliverables

### Week 1 - 2: User Research and Analysis
**Deliverables:**
1. **User Personas:** Detailed profiles representing different user types.
2. **User Journey Maps:** Visual representation of the users' interactions with the app.

### Week 3 - 4: Information Architecture and Wireframing
**Deliverables:**
1. **Information Architecture:** Sitemap or flowchart showing the organization of the app.
2. **Low-Fidelity Wireframes:** Basic sketches showing the layout of the main screens.

### Week 5 - 6: Prototyping and Visual Design
**Deliverables:**
1. **High-Fidelity Prototypes:** Detailed screen designs with full interactivity.
2. **Visual Design:** UI style guide including color scheme, typography, iconography, etc.

### Week 7 - 8: User Testing and Iteration
**Deliverables:**
1. **Usability Testing Report:** A detailed report of the findings from the usability testing.
2. **Revised Prototypes:** Updated screen designs based on the feedback from the testing.

### Week 9 - 10: Handoff to Developers
**Deliverables:**
1. **Design Specification Document:** A detailed document outlining the design and functionality of the app.
2. **Design Assets:** All the necessary assets such as icons, images and fonts needed for the development of the app.

## UX Case Study: Designing the NFT Button Soccer App

### Introduction

The NFT Button Soccer App was envisioned as a platform that would unite parents and children in the craftsmanship adventure of button soccer. The goal was to provide a comprehensive system to manage teams, players, and leagues, complete with NFT-backed player certificates, and a marketplace for trading.

*Image: Placeholder for project overview*   
**Caption:** Overview of the NFT Button Soccer App project highlighting key goals and features.

### Research

We started the project by conducting user interviews and surveys to understand the needs and motivations of our target users - team owners, league organizers, and referees.

*Image: Placeholder for user research process*   
**Caption:** Team conducting user research through interviews and surveys.

We then analyzed the data to create user personas that represented the different user types. These personas helped us understand the motivations, goals, and pain points of our users.

*Image: Placeholder for user personas*   
**Caption:** The user personas created based on the research data.

### Design Process

Based on our research, we defined user journeys and created the information architecture of the app.

*Image: Placeholder for information architecture*   
**Caption:** The information architecture of the app, highlighting key sections and user flows.

We then started sketching wireframes for the main screens of the app, keeping our user personas and their needs in mind.

*Image: Placeholder for wireframes*   
**Caption:** Initial low-fidelity wireframes of the app screens.

After several iterations and feedback sessions, we moved on to creating high-fidelity prototypes and the visual design.

*Image: Placeholder for high-fidelity prototypes*   
**Caption:** High-fidelity prototype of the app showcasing key screens.

*Image: Placeholder for visual design*   
**Caption:** Visual design elements of the app, including color scheme, typography, and iconography.

### Testing & Iteration

We conducted usability testing with a group of target users to validate our design. The feedback helped us identify areas of improvement and iterate on our design.

*Image: Placeholder for user testing*   
**Caption:** Conducting usability testing to gather feedback and improve the design.

### Implementation

The final step was preparing the design for handoff to the developers. We created a design specification document and assets, and conducted a walkthrough with the developers.

*Image: Placeholder for design handoff*   
**Caption:** Design handoff meeting with the developers.

### Conclusion

The NFT Button Soccer App was a challenging and rewarding project that allowed us to explore the intersection of gaming, craftsmanship, and blockchain technology. We learned a lot about creating an engaging and user-friendly platform that caters to a diverse set of user needs.

*Image: Placeholder for final app screens*   
**Caption:** Screenshots of the final app showcasing the implementation of our design.

**Inspiration:** For this project, we were greatly inspired by existing sports management apps, NFT marketplaces, and button soccer communities. We also drew a lot of inspiration from material design principles, which guided us in creating an intuitive and accessible interface.
