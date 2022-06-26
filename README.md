# Learning-Github-Actions

Goal is to do **Automated AppStore Submits** of the DJ App.

1. A new DEV version of the DJ App gets built and submitted to App Stores every night at TODO time. But only if there was some new code added since last App Store submission.
1. ^ This should also be doable outside of the fixed nightly schedule, by merging of any Pull Request that has the label `trigger-new-app-store-submit-of-dev`.
1. A new UAT version of the DJ App ... TODO.
1. Also enable manual submission from the local machine by a single command.
