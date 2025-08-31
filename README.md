# Analyzing Offensive Capabilities at the 2022 FIFA World Cup ⚽

This project applies **statistical modeling in R** to analyze team offensive capabilities at the **2022 FIFA World Cup**. Using logistic regression and beta regression models, we evaluate metrics such as **expected goals (xG)**, **expected successful passes (xP)**, and **expected assisted goals (xAG)**. The analysis leverages **event-level data from StatsBomb** to provide team and player insights.

## 🔹 Project Overview
- Built **logistic regression models** for expected goals (xG) and expected passes (xP)  
- Developed a **beta regression model** for expected assisted goals (xAG)  
- Used **StatsBomb event-level data** via the `StatsBombR` package in R  
- Created an **R Markdown report** documenting the methodology and findings  
- Designed a **slideshow presentation** summarizing the research question, models, and results  

## 🔹 Key Findings
- **Overperformers**: Portugal (+4.9 goals above xG) and Netherlands (+4.54 goals) scored far more than expected
- **Underperformers**: Brazil (–4.01 goals below xG) struggled despite elite attacking talent
- **Passing (xP)**: Spain overperformed the most, completing 119 more passes than expected, with heavy midfield concentration
- **Assists (xAG)**: France and England were the top overperformers due to clinical finishing from Mbappé and Kane:content
- **Tactical Insight**: Strong midfield play (e.g., Argentina with Messi, Croatia with Modrić) correlates with offensive efficiency

## 🔹 Technologies Used
- R  
- RMarkdown  
- Libraries: `StatsBombR`, `tidyverse`, `dplyr`, `ggplot2`, `glm`  

## 🔹 Repository Contents
- **`all_codes_file.Rmd`** → Full R Markdown source code and analysis  
- **`FIFA 2022.pptx`** → Slideshow presentation with visuals and results  
- (Optional) Knitted HTML/PDF report generated from the R Markdown  

## 🔹 How to Run
```bash
# 1. Clone this repository
git clone https://github.com/rahiqraees/FIFA-WorldCup-Analysis.git

# 2. Open the R Markdown file to reproduce results
Rscript -e "rmarkdown::render('all_codes_file.Rmd')"

# 3. View the generated HTML/PDF report OR open the included slideshow for a summary
