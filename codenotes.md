# Code Notes for Chirper App

## 06/10/2022

Starting the project by looking at the possible components. There are three views: Dashboard, Tweet View, and New Tweet View. All three would be located in the App component. All three share the same Navigation. The others: Tweet, New Tweet, Tweet Container, Tweet List. So the components are:

- **App**
- **Navigation**
- **Tweets List**-- _Gets_ the tweets, GET_LIST_OF_TWEETS
- **Tweet Container**-- _Gets_ a specific tweet from a list of tweets; _get_ replies to a specific tweet from a list of tweets.
- **Tweet**-- _Get_ specific tweet from a list of tweets; _get_ the authedUser (user that is currently logged in) so use can _toggle_ the likes on each tweet; _get_ the authedUser so the use can _reply_ to a tweet. Tweets: used by Dashboard, Tweet Page, Tweet components. (Store State)
- **New Tweet**-- _Get_ the authedUser so user can _create_ a new tweet; _set_ the text of the new tweet. Text of new tweet: used by this component. (Component State)
