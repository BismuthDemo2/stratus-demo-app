Stratus is a site for processing and viewing meteorological predictions.

It was originally created by Nick Gregory that we now use to show Bismuth's capabilities as it's a medium complexity app
spanning a data processing queue, backend API, and frontend.

We've created a handful of issues on this GitHub repo representing real features and bugs.
Feel free to modify the issues, adding details on what you'd like to see Bismuth do.

To get started, you'll need to link GitHub to Bismuth.
Log in to https://app.bismuth.cloud and follow this tutorial: https://www.loom.com/share/8ce05331a7944bcd9f63aeabc4be0c66

Then to assign Bismuth to an issue, just create a comment on the issue including "@BismuthCloud".
Bismuth will pick up the issue, create a comment to show you its progress and, after a few minutes, open a completed PR.
You can also view everything Bismuth is doing by going to https://app.bismuth.cloud.

Currently, Bismuth generates a complete PR in one go based on the issue title + description.
We're actively working on making it responsive to follow-up comments.

To see the changes Bismuth has made, you can run Stratus locally:

1. Clone the repo and checkout the PR's branch
1. Run `./dev.sh`
1. Run `./dev-data.sh` to load some initial data into the system. This will take a few minutes.

The frontend will then be available at http://localhost:3000

Finally, we've left a draft PR in this repo to better demonstrate some of the internal capabilities and reasoning that Bismuth does which puts us a step above our competitors.
Simply mark it as ready for review after installing the GitHub app and Bismuth will start analyzing the changes, leaving comments, and suggesting fixes for bugs it discovers.
