# 🐦 Simple Twitter Clone

A simple Twitter-like application built with JavaScript, HTML, and CSS. This project was part of my learning journey while working towards the Scrimba Frontend Developer Certification. 🚀

## 🌟 Features

- 📢 **Post Tweets** – Users can compose and share tweets.
- ❤️ **Like Tweets** – Toggle likes on tweets.
- 🔁 **Retweet Functionality** – Retweet posts with a single click.
- 💬 **Reply to Tweets** – Users can respond to tweets.
- 🎨 **Dynamic UI Updates** – The feed updates in real-time.

## 🛠️ Technologies Used

- HTML
- CSS
- JavaScript (ES6+)
- UUID (for unique tweet IDs)

## 📂 Project Structure

- `index.html` – The main structure of the web app.
- `style.css` – Styles for the UI.
- `script.js` – Core JavaScript logic for interactivity.
- `data.js` – Stores the sample tweet data.

## 📜 Function Explanations

### `handleLikeClick(tweetId)`
- Finds the tweet by its `uuid`.
- Toggles the `isLiked` property.
- Updates the like count accordingly.
- Calls `render()` to update the UI.

### `handleRetweetClick(tweetId)`
- Finds the tweet by its `uuid`.
- Toggles the `isRetweeted` property.
- Updates the retweet count accordingly.
- Calls `render()` to refresh the feed.

### `handleReplyClick(replyId)`
- Toggles the visibility of the reply section for a specific tweet.

### `handleTweetBtnClick()`
- Retrieves the input value from the tweet box.
- Creates a new tweet object and prepends it to `tweetsData`.
- Clears the input field.
- Calls `render()` to display the new tweet.

### `getFeedHtml()`
- Iterates over `tweetsData` to generate HTML for each tweet.
- Includes likes, retweets, and replies dynamically.
- Returns the final HTML string.

### `render()`
- Inserts the generated HTML into the DOM to update the feed.



## 🙌 Acknowledgements

A huge thank you to the **Scrimba** community for their amazing courses and support! 🎉 This project was a great learning experience in JavaScript and front-end development.



