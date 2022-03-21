# ordinantibes
Automates schedule of activities in an organization based on its members' availabilities.

## Name explanation

**Ordinantibes** is the contraction of *ordinateur*, the French word for computer, and Antibes, a town on the French riviera, where I currently live.

## Objectives

- Ease the scheduling of activities inside an organization, especially when there are people involved in more than one activity
- Provide pleasant user experience with a simple, intuitive, comprehensive web application interface
- Replace useless, tiring and boring text message, email or chat series to agree on a suitable time for all participants of an event
- Replace Excel sheets, Doodle, etc. for scheduling

## Concepts
- User: a physical human being using Ordinantibes
- Event: an optional activity a user can attend
- Profile: page showing all details about a user, e.g. first and last names, email address, phone number, birth date, roles, teams, roles and so on
- Duty: a mandatory activity a user must attend, usually a recurrent one
- Scheduling: process of defining which users attend an event or a duty, when and how often
- Login: process in which a user inputs credentials so Ordinantibes can check their identity and the user can use the application
- Logout: process of disconnecting from the application, be it manual or automatic
- Session: period between user login to Ordinantibes and logout
- Notification: a way to inform a user about details of an event or a duty of interest
- Reminder: special kind of notification to allow a user to remember an event or duty of interest is coming soon
- Role: Level of privilege a user has on an event or a duty, e.g. view, subscribe, modify, create, delete an event, invite a user, and so on

## Expected features

- User profile creation, view, modification and deletion
- Password less user login, with time-bound renewable token
- Automatic logout when session expired
- Declare unavailabilities for an event or a duty you are concerned about
- Role, event, team and user management
- Smart scheduling of meetings or activities based on declared unavailabilities of members of a team or participants to an activity
- Reminder setup and automatic sending of reminders when a user is about to attend an event or fulfill a duty
- Event export to Google, Microsoft, Apple or ICS calendar format
- Email, group messaging or SMS automatic notification triggered upon every event change

## Constraints
- No more than one session per device per user at a time


## Credits

Jérémy Domarin, 2022