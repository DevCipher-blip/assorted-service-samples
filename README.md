# Independent service samples

## Choose a sample, then its environment

This repository groups separate examples rather than one deployable application. Explore [notification-app/](notification-app/), [aviyel/](aviyel/), and [TradeCore/](TradeCore/) independently; each sample has its own assumptions and dependencies.

The notification example includes a browser client. The other folders demonstrate service-oriented Python work. For a portfolio walkthrough, choose one folder, explain a request through its implementation, and run that folder's tests instead of treating a root-level dependency installation as a shared environment.

For persistent Django sessions, supply `DJANGO_SECRET_KEY` (or `SECRET_KEY`) in the process environment. Local development uses a fresh temporary signing key when neither is set.





## code-samples

Installing instrictions
