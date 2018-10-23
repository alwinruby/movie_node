# Node.JS app for Analysing Films

The application Movie Analyst aggregates and displays a list of the latest movie reviews by famous critics across the web. Users can view the latest movie reviews, learn about the critics that review them, and also see the publications that Movie Analyst has partnered with. Website administrators, who will have a separate website, can see and edit these pages, but also have access to reviews-in-progress so that they can prepare and approve reviews ahead of time.

Instead of building two separate backends for the user facing side and the admin application, this app will expose an API with four endpoints. The user facing app will have access to the movies, reviewers and publications endpoints, while the admin app will additionally have access to the pending endpoint which will return movie reviews that are not ready to be publicly accessible.
