🌍 Spiritual & Religious Beliefs 
#MakeoverMonday – Week 27, 2025

This visualization explores how much of the population across different countries of the world identifies as religiously affiliated, having belief in life after death, belief in nature's spiritual energies, praying daily and belief in horoscopes. The circular orbit layout represents each region’s percentage share using filled vs. unfilled points — making comparisons intuitive and visually engaging.

📊 What’s Shown

% of population that is religiously affiliated

Clear distinction between affiliated (highlighted) and not affiliated (background)

Region-wise comparison in a single circular view

Clean interactivity with tooltip shown only for the highlighted portion

🎯 Design Highlights

Orbit Arrangement symbolizes global unity and diversity

Highlights only the filled portion to keep tooltips meaningful

Custom calculations used for mark segmentation and tooltip display

🧮 Key Calculated Logic

Used to show tooltip only for the filled portion:

IF MAX([Orbit - Colors Religiously Affiliated]) = 1 THEN
    "🌟 Religiously Affiliated: "
    + STR(ROUND(MAX([Are religiously affiliated]),0)) + "%"
END

🛠️ Tools Used

Tableau Public

📂 Dataset

Makeover Monday — Week 27, 2025
(Dataset link as published by Makeover Monday)

✨ Author

Ananya D
📌 Tableau Public: https://public.tableau.com/app/profile/ananya.dikshit/vizzes
