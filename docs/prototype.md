# Prototype

* A way to manage tournaments, series, games, teams and organizations
* It can be everything in a single application, just divided into manager and homepage
* No user-role integration
* Use Calculated.gg and Ballchasing.com as stat gathered for games
  * This most likely will be useful to do even on the final version
  * Upload games to this sites, gather states from them (calculated might have more accurate stats)
  * Provide links to each game url to show better stats/replays (for replays and visual stats, Ballchasing seems more complete)
* Use Next.js, MUI, Prisma2, Docker and Now for faster prototyping

## Moving Forward

Thinking a little ahead:

* We may want to split it into multiple apps
  * Viewer
    * For fans, casual viewers, participants
  * League/Tournament Manager
    * Organizers
    * Casters
    * Arbiter
  * Org/Team Manager
    * This is for org owners or team managers
* We may want to split the API similarly
* Based on technologies tested on prototyping, choose stack, tho spliting APIs and Apps might allow for some diversification, tho for production this might not be productive
* I'd like to use Rocket League's API if it's released eventually
* Maybe even integrating with Challonge can ease some development
