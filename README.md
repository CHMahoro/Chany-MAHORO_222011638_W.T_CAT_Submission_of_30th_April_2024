# Chany-MAHORO_222011638_W.T_CAT_Submission_of_30th_April_2024
Apology:  according to my project structure doesn't allow username as entrance for login we user email instead so that why
email:alex@gamil.com
password:1234
My project description:
The "Personalized Daily News  Digest" project integrates PHP, HTML, CSS, and JavaScript to provide users with a tailored news experience. Let's explore how each technology contributes to the project's functionality and delve into the descriptions of the five key database tables.

HTML: HTML structures the web pages where users interact with the news digest. It defines the layout, headings, paragraphs, and forms that facilitate user engagement. For instance, HTML creates the user interface elements like login forms and news article displays.

CSS: CSS styles the HTML elements, enhancing the visual appeal and user experience of the web pages. It controls the colors, fonts, spacing, and overall design aesthetics. By using CSS, the project ensures a consistent and visually appealing presentation of news content.

JavaScript: JavaScript adds interactivity to the project, enabling dynamic features such as real-time updates and user interactions. It facilitates actions like filtering news articles, saving preferences, and displaying notifications. JavaScript enhances user engagement and responsiveness within the news digest.

PHP: PHP serves as the backend language responsible for processing user requests, managing data interactions, and generating dynamic content. In this project, PHP handles user authentication, retrieves personalized news content, and updates user profiles based on preferences.

Database Tables:

1. UserProfile Table: The UserProfile table stores essential user details, including UserID, Username, Email, Preferences, ReadingHistory, and SubscriptionStatus. It plays a crucial role in personalizing the news digest for each user based on their reading habits and preferences.

2. NewsArticle Table: The NewsArticle table contains news articles with fields such as ArticleID, Title, Author, PublicationDate, Content, Tags, and Source. It houses the actual news content that is curated and delivered to users based on their preferences and interests.

3. DigestConfiguration Table: The DigestConfiguration table manages the delivery settings for each user's personalized news digest. It includes fields like DigestID, UserID, TimeOfDelivery, PreferredContentTypes, and LanguagePreferences, ensuring that users receive their daily news summaries at specified times with content tailored to their preferences. The table also includes a foreign key constraint linking UserID to the UserProfile table.

4. ReadingHistory Table: The ReadingHistory table tracks users' reading activities, storing information such as HistoryID, UserID, ArticleID, Timestamp, and ReadingDuration. It helps personalize the news digest by recording which articles users have read, how long they spent reading each article, and when they accessed the content. The table includes foreign key constraints linking UserID to the UserProfile table and ArticleID to the NewsArticle table.

5. NotificationLog Table: The NotificationLog table logs notifications sent to users, recording details such as LogID, UserID, NotificationType, Timestamp, and Status. It tracks the communication between the system and users regarding important updates or alerts. The table includes a foreign key constraint linking UserID to the UserProfile table.

In summary, the "Personalized Daily News Digest" project utilizes PHP, HTML, CSS, and JavaScript to create a dynamic and personalized news platform. The database tables, including UserProfile, NewsArticle, DigestConfiguration, ReadingHistory, and NotificationLog, play a crucial role in storing user information, news articles, preferences, delivery settings, reading history, and notifications, enabling the system to deliver tailored news content that aligns with each user's interests and preferences.
