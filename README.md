# Billy-Portfolio
My Modest Portfolio



# [Project 1: Blytz Megaplex](https://github.com/billywibowo7/Blytz-Megaplex)
by Billy Wibowo (2201762326)

This is my submission for Human and Computer Interaction Quiz.

- Blytz Megaplex is a dummy cinema and it is developing a website that will provide an explanation about Blytz Megaplex, 
current partners of Blytz Megaplex, hoverable Blytz Megaplex facility pictures, and list of now showing movies.
Beside that, this website will also provide a feedback form for their customers in order to give feedback about the development team
of Blytz Megaplex.

- The Blytz Megaplex website has 2 pages consist of homepage and feedback page created with html and css. 
This website design must be simple and easy-understanding because it targets customers from all ages. It also has interactive feature such as
the image is changed when they are hover and the all of the button are clickable and visible. 


| Homepage | Feedback |
|:--------:|:--------:|
|<img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/homepageblytz.png?raw=true" alt="Homepage"> | <img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/feedbackblytz.png?raw=true" alt="Feedback"> |







# [Project 2: RX-Player](https://github.com/billywibowo7/RX-player)
by Eric Bintang Timotius (2201764054)
   Billy Wibowo          (2201762326)
   Verio Joshua          (2201764054)


- RX-Player is a group project for Human and Computer Interaction final assignment.

- RX player is a digital music player company formed in December 2019 and located in Jakarta, Indonesia. The main purpose of the RX player is to provide millions of high-quality songs from any of the countries all around the world. RX player also provides all kinds of genres. Songs in RX players are always updated every day. The user can also be the creator that can upload their song to the RX player and share that song privately or publicly. This project is using HTML, JavaScript, and CSS.



| About Us | Registration | Membership |
|:--------:|:------------:|:----------:|
|<img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/rxplayerAboutUs.png?raw=true" alt="About Us"> | <img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/resgistration.png?raw=true" alt="Registration"> | <img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/membership.png?raw=true" alt="Membership"> |

| Music by Genre | Top 10 Music |
|:--------------:|:------------:|
|<img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/musicbyGenre.png?raw=true" alt="Music by Genre"> | <img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/top10music.png?raw=true" alt="Top 10 Music"> |




# [Project 3: Classification and Clustering in Machine Learning (Big Data Processing)](https://github.com/billywibowo7/Big-Data-Processing)
by Billy Wibowo (2201762326)



- Classification in Machine Learning: This program is to create a predictive model that will classify whether a planet is likely habitable or not from given data "Planet_Training.csv" and "Planet_Testing.csv". The goal of this program is to make classification model and test it to "Planet_Testing.csv"

First, is Load Data from given file “Planet_Training.csv” and “Planet_Testing.csv” using SparkSession
Second is to select important features that will be used for training. In this we should pick three important features (My selection is Temperature, Water, and Atmosphere Color)
Third, we should remove any mising values in the data
Fourth is to transform raw data so that can be suitable for training
Fifth step is to normalize the data using StandardScaler package
Sixth, Generate a model from the data using LogisticRegression package with 10 as the max iteration
And last but not least, after the model is generated, you can test the model to predict whether the planet will be habitable or not using BinaryClassificationEvaluator package to print the accuracy of your model. Get the model with minimum accuracy 90% or higher

Image from first step until last step


<img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/classification1.png?raw=true"> <img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/classification2.png?raw=true"> <img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/classification3.png?raw=true"> 


- CLustering in Machine Learning: This program is to make a clustering model that will have 2 cluster, grizzly bear cluster and non-grizzly bear cluster with given files  “BearTraining.csv” and “BearTesting.csv”

1.	Load Data
 Load the data from “BearTraining.csv” and “BearTesting.csv” using SparkSession.
2.	Select Features
After load the data, select three important features that will be used for training. My selection is Front Claws, Pupillary Distance, and Ear Shape) 
3.	Data Preprocessing
This step is to remove any missing values in the data.
4.	Transform Data
In this step, transform the raw data so that it is suitable for training. For example, recode the ‘Ear Shape’ column value to be either 0, 1, or 2.
5.	Normalization
After data preprocessing, normalize the data using the StandardScaler package
6.	Generate Model
Next, generate a model from the data using the KMeans package to generate the model into 2 cluster.
7.	Visualization
After the model is generated, visualize the model using the pyplot package. (Also to add x-label, y-label, and title for the plot.)
8.	Model Testing and Evaluation
Then, test the model to check predict whether the data will be in grizzly bear cluster or in the non-grizzly bear cluster and print the accuracy of your model and get the model with minimum accuracy 80% or higher.


<img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/clustering1.png?raw=true"> <img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/clustering2.png?raw=true"> <img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/clustering3.png?raw=true">



- Query and Data Visualization: DezzDryth Online is an online game which is currently being popular in South East Asia. Since the popularity are going high, make some analysis on the data they have. Below is the DezzDryth Online ERD to analyze: 

<img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/erd.jpg?raw=true">


1.	Load Data from CSV to Spark
Using SparkSession, read the following files (“MsNPC.csv”, “MsPlayer.csv”, “MsWeapon.csv”, “MsWeaponType.csv”, “TransactionHeader.csv”, “TransactionDetail.csv”).

<img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/visualization1.png?raw=true">

2.	Query Analysis and Visualization
Gain some sales insight about the data. Below are some statements you need to answer. Use SparkSQL to answer the question and pyplot package to visualize the answer.
a.	Show the percentage of weapon type sold for weapon type that is sold in 2019 using pie plot.

<img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/visualization2.png?raw=true">

b.	Show the total number of players who bought axe weapon type per month in 2019 using line plot. Multiple transaction within the same month will be counted as 1.

<img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/visualization3.png?raw=true">

c.	Show the frequency of special weapon being distributed to female players in 2019 using bar plot. The player will receive special weapon if their monthly spending reached this following condition: 
Special Weapon	Monthly Spending
Storm Breaker	1000000 - 1499999
Nightfall	1500000 – 1999999
Extinction	> 2000000

<img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/visualization4.png?raw=true"> <img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/visualization5.png?raw=true"> 

d.	Show total number of players per month in 2019 who bought at least 3 different weapon type in a month using line plot.

<img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/visualization6.png?raw=true"> <img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/visualization7.png?raw=true">

e.	Show the frequency of NPC's popularity who has done at least transaction with 5 different player using bar plot. The popularity is determined based on the total income made by the NPC as follows:
Popularity	Total Income
Very Popular	>= 15,000,000
Popular	>= 7,500,000 – 14,999,999
Quite Popular	>= 2,500,000 – 7,499,999
Not Popular	< 2,500,000

<img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/visualization8.png?raw=true">




# [Project 4: RA Laundry](https://github.com/billywibowo7/RA-Laundry)
by Steven Odolf Yuwono        (2201758045)
	Rudy Prabowo Halim         (2201750074)
	Jonathan Herbert Saginto 	(2201786566)
	Billy Wibowo               (2201762326)	

- RA’Laundry is a laundry store that handled laundry services. RA’Laundry manage transactions like service and purchase transactions. Service transaction is a transaction that happened when customer wants to laundry their clothes, while Purchase transaction is a transaction that happened when the store wants to restock their material (equipment/supplies) from a vendor.

- Our tasks as database administrator in RA’Laundry are to create a database system that can store data and maintain the service transactions and purchase transactions. According to the requirement that has been requested.


RA Laundry's Database Entity Relationship Diagram (ERD)

<img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/RA%20Laundry/erd.png?raw=true">




# [Project 5: Rawit Pay a.k.a R-Pay (Software Engineering)
by Alvin Fernando         (2201755200)
Billy Wibowo              (2201762326)
Eric Bintang Timotius     (2201764054)
Ferdinand Wibowo          (2201741826)
Jason Wiratama Goenawan   (2201745401)
Verio Joshua              (2201750313)
Vincent                   (2201738421)



R-Pay is an e-wallet application such as OVO, DANA, Gopay, and others that also provide cashback to its users. But the difference between R-Pay and others is that here we provide cashback, not solely we use money like other e-wallets, but we give cashback to users in a way that users have to see an ad (advertisement) of about 30 seconds that cannot be discarded about a working sponsor the same as R-Pay. After that, the user gets cashback from us, here we have a win-win situation between us, the user, and our sponsor. Our target customers are people of productive age, namely those aged 15 - 64 years who often spend their money and have kept up with the times. And we hope that not only big city people will use this e-wallet but we will also target people in small cities as customers by providing several promos in several small cities.


Below is the example of the prototype design of R-Pay from our group


| Logo |
| :--: |
|<img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/Logo.png?raw=true" height="500" width="500"> |

| Login Page | Profile Page | Home Page |
|:----------:|:------------:|:---------:|
|<img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/loginpage.png?raw=true"> | <img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/profilepage.png?raw=true"> | <img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/homepage.png?raw=true"> |

| Bill | Top Up | Profile Update |
|:----:|:------:|:--------------:|
|<img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/bill.png?raw=true"> | <img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/topup.png?raw=true"> | <img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/updateprofile.png?raw=true"> |

| Claim Voucher |
| :-----------: |
|<img src="https://github.com/billywibowo7/Billy-Portfolio/blob/master-branch/images/claimvoucher.png?raw=true"> |



