# Tasks
- Fix register and login issue.
- Add current Eth price on profile page.

## Issues

### Email Verification

The current implementation of email verification with Gmail will not work as Google consider it as an unsafe method and have disable it.
It should be replaced with an OAuth implementation.

*I have commented out email verification as I feel this is out of scope for the test as it requires signing up for OAuth api key.*

### Setup - Environment Variables

It might be helpful to have a setup where different environment variables are loaded
depending on the build environment, development and production for example.

### UI/UX

There are minor issues with the UI all over the site as well as the overall user experience of the site. Also the design of the site is lacking polished as it looks rather amateur.
More work can be done on this area.

### TechStack - Centralized Database & Security
The current techstack especially the use of SQL database to store user wallet details such as the private key is questionable as
a centralized database is prone to hacks and leaks. Security is very hard and unless the company put significant resources into the security aspect, this is a major cause of concern.

While I understand the idea here is to make it easy for non-tech savvy user to get involved with cryptocurreny, I believe there are
better ways to deal with this issue.

## Bugs

### Profile - Loading Modal 

There are some conditions issues for the loading as it never stops.

*I have commented out the loading as there seems to be some deeper issues with the conditions.*


