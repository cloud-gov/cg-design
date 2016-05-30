# May 2016 Draft research summary

During this past round of research, the Cloud.gov design team spoke with 6 people. All were developers, ranging from low-medium level of technical proficiency to expert level of technical proficiency. Two of the individuals we spoke to were not current users of Cloud.gov.

## Top level observations

- Developers were most familiar with Heroku and AWS.
- Developers regularly pointed to Heroku as a "gold standard" for its ease of use.
	- Ease of use was generally defined as their ability to get in and get out of a task as quickly as possible.
- The current version of Cloud.gov does not provide developers with the information or the tools they need to diagnose and fix problems quickly. Addressing this issue should be our top priority.

## Recommendations

Based upon this round of research, I suggest that we focus on tools that will help users troubleshoot issues with their applications as easily as possible. 

The team should first focus on building an activity log to show actions such as pushes to GitHub repos, errors, and alerts if something goes wrong. (Note: we can consider pro-active notifications in the future, but we should consider this activity log to be prerequisite.)

Additionally, we should consider making it easier to view and set global variables. These two points of focus should help us make the lives of our users much easier.

## Other observations

- Users had trouble finding the Deck. Users typically referred to "Deck" as "Dashboard". Expected a "Sign in" or "Login" button in global nav to access said Dashboard.
- Lack of clarity around CF-specific language -- spaces, auditor, etc. We should consider providing some sort of helper text around any CF jargon, as most of our users are coming off of Heroku or AWS.
- Many items presented on the app are not interactable. We should consider adding interactions to much of the experience when possible.
- Users didn't know the number of units for memory or storage, typically assumed GB. Didn't know what "Quota" percentage referred to.
- Users found the initial login screen to not be stark, not very helpful.
- Some features of Cloud.gov aren't hooked in to the Console UI. Everything that has a UI on Cloud.gov should be linked, such as the logs.cloud.gov service.
- One non-current Cloud.gov user was forced to stand up personal servers in order to accomplish his goals, wanted to avoid "4-5 year wait".
- Many users preferred using a GUI for pretty much all configuration when possible. Some preferred to work from command line and only to jump in GUI when necessary. They often felt the CF CLI was not adequate, one users simply calling it "weird".

## Quotes
- I'd like to see a "Snapshot of the entire app"
- "I think the biggest win would be fixing the information hierarchy"
- "I’ve used a lot of these things and I think Heroku does a really good job of making it easy"
- "What is VCAP info?"