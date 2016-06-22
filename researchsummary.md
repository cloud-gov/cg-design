# May 2016 Draft research summary

During this past round of research, the Cloud.gov design team spoke with 6 developers. The developers ranged from low-medium to expert levels of technical proficiency. Four of the six individuals we spoke to are current users of Cloud.gov.

In the future, it is important that the team interview additional user types including project managers, budget analysts, and CTOs.

## Top level observations

- Developers were most familiar with Heroku and AWS.
- Developers regularly pointed to Heroku as a "gold standard" for its ease of use.
	- Ease of use was generally defined as their ability to accomplish a task as quickly as possible.
- The current version of the Cloud.gov dashboard does not provide developers with the information or the tools they need to diagnose and to fix problems quickly. Addressing this issue should be our top priority.

## Recommendations

Based upon this round of research, we suggest that the team immediately focus on tools that will help users troubleshoot issues with their apps as easily as possible. Additionally, we recommend that in the long-term, we strive for feature parity between dashboard and API+CLI.

- Activity log (High)
	- Show activity such as pushes to GitHub repos, errors, and alerts if something goes wrong. (Outstanding question: One activity log vs multiple)
- Improve navigation (High)
	- Clear, predictable, reliable navigation.
- Make it easier to view and set global variables (Medium)

## Other observations

- Users had trouble finding the Deck. Users typically referred to the "Deck" as "Dashboard". Expected a "Sign in" or "Login" button in global nav to access said Dashboard.
- Lack of clarity around CF-specific language -- spaces, auditor, etc. We should consider providing some sort of helper text around any CF jargon, as most of our users are coming off of Heroku or AWS.
- Many items presented on the app are not interactable. We should consider adding interactions to much of the experience when possible.
- Users did not know the number of units used to measure memory or storage, and typically assumed they were in GB. No users knew what "Quota" percentage referred to.
- Users found the dashboard home to be stark, not very helpful.
- Some features of Cloud.gov aren't hooked in to the Console UI.
- Everything that has a UI on Cloud.gov should be linked, such as the logs.cloud.gov service.
- One non-current Cloud.gov user was forced to stand up personal servers in order to accomplish his goals, wanted to avoid "4-5 year wait".
- Many users preferred using a GUI for pretty much all configuration when possible. Some preferred to work from command line and only to jump in GUI when necessary. They often felt the CF CLI was not adequate, one users simply calling it "weird".
- Users experessed that it felt easy to make a mistake (i.e. to delete a space or app by accident).

## Quotes
- I'd like to see a "Snapshot of the entire app"
- "I think the biggest win would be fixing the information hierarchy"
- "I’ve used a lot of these things and I think Heroku does a really good job of making it easy"
- "What is VCAP info?"
