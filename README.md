# Extra Life Team Dash
A team dashboard for Extra Life fundraising. See an example here: https://extra-life-team-dash.herokuapp.com/team/29238

This relies on the consolidated team data that's compiled by this API: https://github.com/vokal/ExtraLifeTeamInfo

## Warning
This Node.js app was cobbled together sloppily by a mobile developer who wanted a quick leaderboard and some data for a prototype project. Do not use anything in here as an example of how anything should ever be done.

## Running on Heroku
There are better ways to do this, but I'm using Heroku as a low-cost host for this app.

1. Clone this repo.
2. [Create a Heroku account](https://signup.heroku.com), if you don't have one.
3. On the [apps list](https://dashboard.heroku.com/apps), click new, then Create New App.
4. Give the app a name and click the Create button.
5. Read the instructions under "Deploy using Heroku Git" on app Deploy tab. As of this writing, this page appears immediately after you create the app. Note that you'll be using an existing git repo, so follow the instructions in that section in this order, on the command line:
	1. Install the Heroku Toolbelt
	2. Add the heroku remote for the existing repository
	3. Push to heroku remote
6. Back in the app dashboard on Heroku, click the Open App button to launch the app.
7. Navigate to `/team/[teamID]` to see the team dashboard.

## Running locally
1. Clone or download the repo
2. At the project root, run `node index.js`
3. Browse to http://localhost:3000/team/29238
4. Change the team ID at the tail end of that URL to see your own team's leaderboard.
