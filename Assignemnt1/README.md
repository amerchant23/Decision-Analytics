# Decision-Analytics
MSDS 460 Decision Analytics Course 

The Diet Problem Revisited (Version 11)

**Developed by:** Thomas W. Miller  
**Revised:** September 17, 2024

## Overview

Introduced by Stigler (1945) and discussed by Dantzig (1990), the diet problem is a classic problem in constrained optimization often used to introduce linear programming concepts. The diet problem has been studied extensively through the years (van Dooren 2018).

## Purpose

This project aims to construct a personalized diet using current recommended dietary allowances from the U.S. Food and Drug Administration, updated to account for recent research on sodium intake and health (Mente, O'Donnell, and Yusuf 2021). 

Interested in learning more about nutrition and healthy living? Check out [Nutrients](https://www.mdpi.com/journal/nutrients), an open-access journal.

## Nutritional Constraints

The constraints for this linear programming problem consider seven components of nutrition and their daily values, as shown in the following table:

| Component   | Max/Min  | Daily Amount and Measure         |
|-------------|----------|----------------------------------|
| Sodium      | Maximum  | 5,000 milligrams (mg)           |
| Energy      | Minimum  | 2,000 Calories (kilocalories, kcal) |
| Protein     | Minimum  | 50 grams (g)                    |
| Vitamin D   | Minimum  | 20 micrograms (µg)              |
| Calcium   | Minimum  | 1,300 milligrams (mg)              |
| Iron   | Minimum  | 18 milligrams (mg)           |
| Potassium   | Minimum  | 4,700 milligrams (mg)              |

## References
References

Dantzig, George B. 1990. “The Diet Problem.” Informs. 20:4, 43–47. Available on Course Reserves.

Food and Drug Administration, Department of Health and Human Services. 2016. Food Labeling: Revision of the Nutrition and Supplemental Facts Labels. Available at https://s3.amazonaws.com/public-inspection.federalregister.gov/2016-11867.pdfLinks to an external site.

Fourer, Robert, David M. Gay, and Brian W. Kernighan. 2003. AMPL: A Modeling Language for Mathematical Programming (second edition). Belmont, CA: Brooks/Cole. [ISBN-13: 978-0-534-38809-6] Chapter 2, Diet and Other Input Models: Minimizing Costs, pages 27–42. Available onlineLinks to an external site..(https://ampl.com/wp-content/uploads/BOOK.pdf) Check out the Lex Fridman interview from July 2020: Brian Kernighan on UNIX, C, AWK, AMPL, and Go ProgrammingLinks to an external site..
Mente, Andrew, Martin O'Donnell, and Salim Yusuf. 2021, September. "Sodium Intake and Health: What Should We Recommend Based on the Current Evidence?" Nutrients, 13(9): 3232. Available online at https://www.mdpi.com/2072-6643/13/9/3232Links to an external site. . This is part of the September 2021 special issue of Nutrients: "Towards Better Dietary Guidelines: New Approaches Based on Recent Science."  

Stigler, George. 1945. “The Cost of Subsistence.” Journal of Farm Economics, 25:2, 303–314. Available online at https://math.berkeley.edu/~mgu/MA170/Diet.pdfLinks to an external site.

van Dooren, Corné. 2018, June. “A Review of the Use of Linear Programming to Optimize Diets, Nutritiously, Economically and Environmentally.” Frontiers in Nutrition, 4, Article 48. Available online at https://www.frontiersin.org/articles/10.3389/fnut.2018.00048/fullLinks to an external site.
