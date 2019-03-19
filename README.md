# About

This repository should serve as a getting started template to learn the fundamentals about web tracking and analysis. It is a learning material within PM_LU_38 - Web Analytics & KPIs, a learning unit at CODE University of Applied Sciences in Berlin. The course it taught by @Bolland

# Setup

-  Register on Github.com if you haven't
-  [Fork](https://help.github.com/en/articles/fork-a-repo) this repository to your own Github account
-  Create a [Google Analytics](https://analytics.google.com/) account
-  Retrieve your Google Analytics tracking code as explained [here](https://support.google.com/analytics/answer/1008080?visit_id=636885962702722888-2249578001&rd=1)
-  Edit the `/js/google-analytics.js` file to include your individual Google Analytics tracking code
-  [Commit and push](https://stackoverflow.com/questions/2745076/what-are-the-differences-between-git-commit-and-git-push) your changes to your repository
-  Enable your repository to use Github Pages (as explained [here](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/#enabling-github-pages-to-publish-your-site-from-master-or-gh-pages))
-  Your page should now run on your Github Pages and send tracking data to Google Analytics

# Folder structure

You'll find enumerated folders ('0-initial-setup', '1-event-tracking', etc.) that contain similar files and build upon each other.

## 0-initial-setup

This folder contains two basic pages with buttons and implements the Google Analytics tracking code in the "oldfashioned" way.

## 1-event-tracking

This folder contains the same pages but adds basic event tracking to the buttons. Events triggered by clicking those buttons should appear in your Google Analytics view.
