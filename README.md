# AI-BASED-RECOMMENDATION-SYSTEM


## 📌 Project Overview
This project is a **Java-based recommendation system** built using **Apache Mahout**.  
It suggests items (e.g., products, movies, etc.) to users based on **collaborative filtering** and **user similarity**.

The program uses:
- **User-item preference data** stored in a CSV file.
- **Mahout’s Pearson Correlation Similarity** to measure user similarity.
- **Nearest Neighbor algorithm** to find similar users.
- **Recommendation engine** to suggest new items.

---

2. Download Dependencies

Download the following .jar files and place them in the lib/ folder:

mahout-core-0.9.jar

slf4j-api-1.7.25.jar

slf4j-simple-1.7.25.jar

3. Prepare Data

Create a file data/user_prefs.csv with sample ratings:
userID,itemID,preferenceValue
1,101,5.0
1,102,3.0
1,103,2.5
2,101,2.0
2,102,2.5
2,103,5.0
2,104,2.0
3,101,2.5
3,104,4.0
3,105,4.5
4,101,5.0
4,103,3.0
4,104,4.5
4,105,4.0

4. Compile

Run this inside the project root:
javac -cp ".;lib/*" -d out src/RecommenderExample.java 

5. Run
java -cp ".;out;lib/*" RecommenderExample

---
📊 Example Output
<img width="840" height="210" alt="Screenshot 2025-09-29 153732" src="https://github.com/user-attachments/assets/9587b40f-2b42-4ca7-95f7-7c5831e4f364" />

