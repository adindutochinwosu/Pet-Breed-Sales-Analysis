# Pet-Sales-Analysis
This Project consolidates dog and cat breed data into an Excel workbook with separate sheets for sales averages and summaries. Analyze breed popularity, compute average prices, determine temperament modes, and create pivot charts with slicers for enhanced data interaction.

## TASK
##### TASK 1: I have a structured data of dog and cat breeds. I want you to do the following:
Consolidate dog and cat breeds list in 1 Excel file. Create 1 worksheet for cats and another worksheet for dogs.
1.	Add a column to both worksheets called “Average Sales” and compute the average sales for each cat and dog breed.
2.	Add another worksheet called “Summary”
3.	Display total count of cats per fur type.
4.	Display total count of dogs per group1 category.
5.	Using Excel functions, display the following breeds. Display the top and bottom breeds with 1-10 Popularity:
    - Top 10 cat breeds based on popularity
    - Top 10 dog breeds based on popularity
    - Bottom 10 cat breeds based on popularity
    - Bottom 10 dog breeds based on popularity

Note that there can be multiple breeds with the same popularity, output can be more than 10 breeds.

6.	Compute for the average price of:
a.	Top 10 and bottom 10 cat breeds and
b.	Top 10 and bottom 10 dog breeds
Round off to the nearest 2 decimal places only.

7.	Find the mode based on the temperament of:
    - Cat breeds
    - Dog breeds

8.	Print the following:
a.	Total count of cats which have an 
b.	affectionate temperament
c.	Total count of dogs which have an affectionate temperament

9.	Create/ formulate 2 more summaries based on your own analysis.

### Variables
##### Dog Breed
- Breed Name
- Group1
- Group2
- Male Weight (Kg)
- Temperament
- Average Pup Price
- Intelligence
- Watch Dog
- Popularity
- Quantity Sold
- Average Sales

##### Cat Breed
- Breed Name
- Lap Cat
- Fur
- Male Weight(Kg)
- Temperament
- Average Kitten Price
- Popularity
- Quantity Sold
- Average Sales

##### TASK 2: Given the structured and consolidated data of dog and cat breeds, I want you to do the following:
1.	Create a pivot chart for cat breeds and display the following:
    - Total count of cat breeds per fur type.
    - Total count of cat breeds with and without “affectionate” temperament”
    - Add a slicer based on lap cat column
2.	Create a pivot chart for dog breeds and display the following:
    - Total count of dog breeds per Group 2
    - Total count of dogs with and without “affectionate” temperament
    - Add a slicer based on group 1 column
3.	Add more slicers or filters based on your own analysis

## TOOLS USED
- Microsoft Excel
- Power Query
## METHODOLOGY
- Data Collection
- Data Preprocessing
- Data Cleaning
- Data Visualization
- Data Reporting
- Presentation
## FINDINGS
This data provides a comprehensive overview of pet statistics, focusing on dogs and cats, including counts based on fur type and breed groups, popularity rankings, price ranges, and temperament-based categorizations.

##### Cats and Dogs by Fur Type and Group:
- Cats: Counted by fur types (Bald: 2, Long: 20, Medium: 14, Short: 30).
  ![image](https://github.com/user-attachments/assets/d9131c31-443a-4919-948e-0eaa5412d6c7)

- Dogs: Counted by group categories (e.g., Herding: 37, Hound: 34, Sporting: 40, Working: 49).
  ![image](https://github.com/user-attachments/assets/4ae8810d-5ad0-4caa-86c8-c7542ad84c0f)


##### Popularity and Price Rankings:
- Top dog breeds by popularity include the Norwegian Lundehund, Sloughi, and Foxhound, with respective popularity scores of 190, 188, and 187.
- Top cat breeds include the American Wirehair, Korat, and LaPerm, with scores of 41, 40, and 39.
- Highest-priced dog breeds are the Dogo Argentino ($39,000), French Bulldog ($3,000), and Tibetan Mastiff ($3,000).
- Highest-priced cat breeds are the Extra-Toes Cat (Hemingway Polydactyl) ($2,000), Exotic Shorthair ($1,750), and British Shorthair ($1,750).
- Lowest-priced breeds maintain a price of about $100 for bottom-ranked cats and vary from $0 (Entlebucher) to $400 (American Hairless Terrier) for dogs.
![image](https://github.com/user-attachments/assets/5a45de75-3321-4684-9f4a-c1c163ded5ce) ![image](https://github.com/user-attachments/assets/96addce3-cc04-47c3-8748-8d17bb02167c)


##### Temperament and Intelligence Rankings:
- Dog temperaments are generally described as active, alert, faithful, instinctual, and intelligent.
  ![image](https://github.com/user-attachments/assets/49f1ba0e-29ee-4b3e-8873-d882affd4a01)

- Cat temperaments are often active, curious, easygoing, playful, and calm.
  ![image](https://github.com/user-attachments/assets/d3f36935-4f35-4925-9d31-074400f39464)

- Top intelligent dog breeds include the Afghan Hound, Basenji, and English Bulldog, with intelligence scores ranging from 79 to 77.

##### Sales Statistics:
- The Irish Water Spaniel tops dog sales with 74,172 units, while the Foxhound has the least with 4 units.
  ![image](https://github.com/user-attachments/assets/a6d4a2a2-2736-4869-9abc-12d009d07827) ![image](https://github.com/user-attachments/assets/c1ad66d8-d630-4ca9-9aa4-015539917361)

- Tuxedo cats have the highest sales among cats (210 units), with Abyssinian having the least (4 units).
![image](https://github.com/user-attachments/assets/bf7b3a9e-c962-4408-962f-5d04bf0f756a) ![image](https://github.com/user-attachments/assets/296b6d9a-5e7a-4e84-9389-97e02bd65d05)


This summary captures essential quantitative and qualitative aspects concerning the popularity, pricing, and traits of various cat and dog breeds, reflecting their market dynamics and consumer preferences.

From the provided data, several additional insights can be drawn that delve into market trends, breed-specific characteristics, and potential consumer behaviours. Here are some key insights:

#### 1. Market Trends:
- ###### High Price and Low Sales Correlation:
  Breeds with the highest prices, like the Dogo Argentino and French Bulldog for dogs, and Extra-Toes Cat for cats, might have lower sales volumes due to affordability issues, which can be inferred from the 
  general sales data of other breeds.
- ###### Popularity vs. Affordability:
  More affordable breeds may have higher popularity and sales numbers, suggesting that price is a significant factor in pet choice.
#### 2. Breed-Specific Insights:
- ###### Temperament and Popularity:
  Breeds with temperaments that include traits like 'trainable' and 'intelligent' for dogs, and 'playful' and 'calm' for cats, tend to have higher popularity rankings, suggesting 
  that these are desirable traits for pet owners.
- ###### Specialized Breeds:
  Breeds like the Norwegian Lundehund and the American Wirehair, which are less common and possibly have unique characteristics, maintain a high popularity ranking despite possibly lower 
  visibility or availability.
#### 3. Consumer Behavior:
- ###### Luxury vs. Budget Consumers:
  The significant price range among the top and bottom 10 breeds of dogs and cats indicates a market split between luxury and budget consumers.
- ###### Cultural and Regional Preferences:
  Certain breeds may be more popular in specific regions due to cultural preferences or regional adaptability, which could explain drastic differences in sales and popularity.
#### 4 Health and Maintenance:
- ###### Cost of Care:
  High-maintenance breeds (e.g., long-haired cats and large dogs) might not only have higher initial prices but potentially higher lifelong care costs, affecting their popularity and sales.
- ###### Health Issues:
  Breeds known for specific health issues (like the English Bulldog) might see impacts on their popularity and sales, especially as awareness of such issues grows.
#### 5 Seasonal and Periodic Trends:
- ###### Sales Fluctuations:
  The sales data could be analyzed for seasonal trends, such as an increase in puppy and kitten purchases during specific times of the year (like holidays).
#### 6 Breeding and Ethical Considerations:
- ###### Ethical Breeding Practices:
  The popularity and price of certain breeds might influence breeding practices, potentially leading to ethical concerns about overbreeding or breeding for extreme traits.

These additional insights can help stakeholders in the pet industry—ranging from breeders to retailers and pet care providers—to better understand market dynamics, optimize their offerings, and address consumer needs effectively.
## CONCLUSION
Short-fur cats are the most common among cat breeds, with a total count of 30 breeds. This might indicate that short fur is a desirable trait for breeders and owners, possibly due to lower maintenance and grooming requirements.

Long-fur cats also have a significant representation with 20 breeds. This suggests that while long fur might require more maintenance, it remains a popular trait, possibly due to aesthetic appeal and the variety of breeds available.

Medium-fur cats are less common than short and long-fur cats, with 14 breeds. This intermediate category might be less defined or less in demand compared to the more distinct short and long fur types.

Bald cats are the least common, with only 2 breeds. This could be due to the niche appeal of hairless cats, specific breeding challenges, or health considerations associated with baldness in cats.

The higher counts of short and long-fur cats suggest a stronger market demand and breeding focus on these types. Breeders might prioritize these traits to meet consumer preferences, which could be influenced by factors like grooming ease, appearance, and health.

The low count of bald and medium-fur cats indicates potential niche markets. Enthusiasts of these types might be willing to pay a premium or seek specific breeders, suggesting a targeted opportunity for breeders specializing in these less common types.

Overall, the data reflects consumer preferences and breeding trends within the cat market, highlighting the dominance of short and long-fur breeds and the specialized appeal of bald and medium-fur cats.
## RECOMMENDATION
#### For Breeders:
- Focus on short-fur and long-fur breeds, which are in higher demand. Breeding these types could meet market preferences and maximize sales potential.
- Consider specializing in bald and medium-fur cats to cater to niche markets. This could create a unique selling proposition and attract dedicated enthusiasts.
- Ensure comprehensive health screenings and maintenance advice for long-fur and bald breeds, as these types may require more specialized care.
#### For Pet Retailers:
- Stock a diverse range of short-fur and long-fur cat breeds to meet the majority of customer demands.
- Highlight the benefits of owning short-fur cats, such as lower grooming needs, to appeal to first-time pet owners or those looking for low-maintenance pets.
- Create targeted marketing campaigns for bald and medium-fur cats, emphasizing their unique traits and appeal to attract niche buyers.
#### For Marketers:
- Develop educational content about the care requirements and benefits of each fur type to help potential buyers make informed decisions.
- Use social media and online platforms to showcase the variety and beauty of different fur types, especially focusing on the more popular short and long-fur breeds.
- Promote the uniqueness of bald and medium-fur cats through storytelling and testimonials from current owners to generate interest and awareness.
#### For Pet Owners:
- Educate yourself about the specific care needs of different fur types. For instance, short-fur cats generally require less grooming, while long-fur cats might need regular brushing to prevent matting.
- Consider adopting from shelters where a variety of fur types are available, and take advantage of the guidance provided by shelter staff regarding care and maintenance.
- If interested in a niche breed like a bald or medium-fur cat, connect with breeders or owners through online communities to understand their unique characteristics and care requirements.

Overall, understanding the distribution and specific characteristics of cat breeds by fur type can help various stakeholders in the pet industry better meet consumer needs and preferences.
