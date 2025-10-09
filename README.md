**Airbnb Hotel Booking Analysis**

📘 **Overview**

This project presents a comprehensive analysis of Airbnb listings aimed at understanding the factors that influence property pricing. It explores how attributes like property type, location, cleanliness, and host behavior affect rental rates and guest satisfaction. The insights derived serve as a foundation for future predictive modeling, enabling accurate and data-driven pricing strategies.

🎯 **Problem Statement**

Setting the right price for Airbnb listings is a critical challenge for hosts. Prices vary depending on property characteristics, location, cleanliness, and guest interaction quality. This project investigates how these factors collectively influence pricing and availability, helping hosts optimize their listings, attract more guests, and ensure a better user experience for travelers.

🧠 **Objectives**

Analyze Airbnb dataset to identify key factors affecting price and availability.

Examine the impact of property and host features on guest ratings.

Provide actionable insights for hosts to enhance booking performance.

Build a foundation for future predictive pricing models.

👥 **End Users**

Airbnb Hosts – To optimize pricing based on listing features and reviews.

Travelers – To assess whether a listing is fairly priced.

Airbnb Analysts – To enhance automated pricing suggestions.

Researchers/Students – To explore the relationship between property features and rental pricing.

⚙️**Technologies Used**
Tool	Purpose
Python	Core programming language
Pandas, NumPy	Data cleaning and preprocessing
Matplotlib, Seaborn	Data visualization and feature analysis
Google Colab	Cloud-based environment for implementation
Julius AI	Assisted data understanding and cleaning
ChatGPT	Helped interpret visualizations and craft inferences
📊 **Key Insights**
🏘️ **Listing Type Distribution**

Entire homes/apartments (44,163) dominate Airbnb listings (~98% with private rooms).

Private rooms (37,494) cater to budget travelers.

Shared rooms (1,646) have minimal demand.

Hotel rooms (108) show Airbnb’s focus on homely stays over traditional hotels.

✅ **Host Verification Impact**

Negligible difference between verified (3.28) and unverified (3.27) hosts.

Ratings are influenced by property factors, not verification status.

Verification serves security purposes, not satisfaction enhancement.

📈 **Host Listings vs Availability**

Weak positive correlation (r ≈ 0.14) between host listing count and availability.

Other factors likely drive availability variability.

Host listing count alone has limited predictive power.

🚀 **Future Scope**

Develop machine learning models to predict optimal listing prices.

Enhance data quality with location and seasonal demand data.

Integrate automated dashboards for hosts to visualize insights.

🖥️ **How to Run**

Clone this repository:

git clone https://github.com/ga-arsh/VOIS_AICTE_Oct2025_GangaMaya.git


Open in Google Colab or Jupyter Notebook.

Install required packages:

pip install pandas numpy matplotlib seaborn


Run the notebook cells sequentially to reproduce analysis and visualizations.

🧩** Dataset**

The dataset includes property-level and host-level information such as:

Listing type, number of bedrooms, bathrooms

Ratings for cleanliness, accuracy, communication, value

Host verification status and total listings

Pricing and availability details

**Source:** Manually scraped Airbnb data collected for academic analysis.  

👩‍💻 Author

Ganga Maya
