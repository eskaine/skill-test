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
