# Movie-Recommendation-System

<img width="458" alt="Screenshot 2022-09-04 at 3 21 23 PM" src="https://user-images.githubusercontent.com/71970250/188307731-2817fad0-330e-4774-929f-969ea485a42c.png">

--> <b> <i> DATASET : </i> </b>

This dataset is taken from https://www.kaggle.com/code/ibtesama/getting-started-with-a-movie-recommendation-system/data

--> <b> <i> METHODOLOGY : </i> </b>

The selected features used in this project are :
<i>

● Genre

● Keywords

● Tagline

● Cast

● Director
</i>

The rest of the features used are : budget, original_language, original_title, overview, popularity, production_companies, production_countries,release_date, revenue, runtime, status, title, vote_average, vote_count.

The textual data was then converted into feature vectors(numerical values) with the help of <b> <i> TfidfVectorizer </i> </b> so that we can use <b> <i> cosine similarity </i> </b> on the numerical data which is imported from <b> <i> sklearn module.</i> </b>

--> <b> <i> OUTPUT : </i> </b>

The user enters the movie name and therefore he gets the resultant output :

<img width="432" alt="Screenshot 2022-09-04 at 3 30 41 PM" src="https://user-images.githubusercontent.com/71970250/188308007-c3b79504-ca09-4438-ba2a-486831126766.png">
