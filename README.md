## Teehouse Full-Stack Project: Twitter API App

## Goals and objectives are copywrite of Treehouse.com and will be deleted when the project is complete.

#### To successfully complete this project I will accomplish the following:

#### Initial Steps :raised_hands:

- [ ] Download the sample HTML and CSS files to see how the page should look after rendering your Twitter profile information.
- [ ] Create a new Twitter application. This will generate the keys and access tokens you need to let your server communicate with Twitter. You can find instructions about this process in the project resources. Please note that the url to create a Twitter dev account is now https://apps.twitter.com/
- [ ] Study the Twitter REST API docs to find which methods will provide the information you need to fill out the templates, based on the sample layout. The docs are linked in the project resources.
- [ ] Search for some examples of authentication with Twitter in Node. You might not have written any authentication before, and you will benefit from exposing yourself to these ideas before your start. The project resources link to an example using several methods, including TwitterJSClient.

#### Goals :exclamation:

- [ ] Create a Twitter app through Twitter’s developer portal and get the needed API keys. Every service has a slightly different way of handling API keys and authentication. Check the project resources for some guides on getting your keys from Twitter.
- [ ] Make a template using Jade, Handlebars, or another JavaScript template engine for the main page. The template should have spaces for:
 - [ ]  :zap: your 5 most recent tweets :zap:
 - [ ]  :zap: your 5 most recent friends :zap:
 - [ ]  :zap: your 4 most recent privat messages :zap:
    * It should alos include your personal Twitter name and profile image at the top of the screen.
    * Styling is not the important part of this project. Craft your template markup to take advantage of the CSS we've provide you. Knowing how to work with someone else's styles is a very important skill as a full-stack developer. Pay attention to class names, inheritance and so on. Try to avoid element types that are not used in the provided HTML and CSS files.
- [ ] Each rendered result must include all of the information seen in the sample layout:
 - [ ] :zap: tweets :zap:
 - [ ] :zap: message content :zap:
 - [ ] :zap: # of retweets :zap:
 - [ ] :zap: # of likes :zap:
 - [ ] :zap: date tweeted :zap:
 - [ ] :zap:friends :zap:
 - [ ] :zap: profile image :zap:
 - [ ] :zap: real name :zap:
 - [ ] :zap: screenname :zap:
 - [ ] :zap: messages :zap:
 - [ ] :zap: message body :zap:
 - [ ] :zap: date message was sent :zap:
 - [ ] :zap: time the message was sent :zap:
- [ ] Using Node and Express, request the data you need from Twitter’s API, render it in your template, and send it to the client. You’ll need to set up at least one Express route to manage this process. Please set up your project **without the use Express generator.**
- [ ] Make sure the application actually renders your correct Twitter information by running it on your local machine, and comparing it to your recent Twitter activity.
- [ ] It is very important that you do **NOT** upload any of your personal API keys / secrets / passwords to Github or other publicly accessible place. You should remove them from your application BEFORE you push to Github or submit. See project resources for links about how to deploy your application live with your keys safely.
- [ ] Put your project in a new GitHub repository on your GitHub account
- [ ] You should also check for issues with your JavaScript code using JSHint, linked in the Project Resources.

#### Extra Credit

- [ ] Add a section to the bottom of your page that allows a user to post a new tweet.
- [ ] If you add a post tweet feature, show new tweets on the page without refreshing.
- [ ] Add an error page to your application, so that if anything goes wrong with your routes the user will see a friendly message rendered, instead of the default error code.
- [ ] Include your personal background image from Twitter as a background for the page header.
