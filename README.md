# RECOMMENDATION-SYSTEM-FOR-E-COMMERCE-PLATFORM-INTEGRATING-PRODUCT-TITLE-DESCRIPTION-AND-IMAGE
## Introduction
 In this problem, we introduce a recommendation system consisting of two main components: retrieval and re-ranking. The recommendation system is based on three criteria: product title, product description, and product image. Our system leverages these criteria to improve the accuracy of product recommendations. Using precision at K (P@K) as the evaluation criterion, we attempt to determine the optimal weight configuration for each criterion. The goal is to identify and meet the needs of users to explore related products on the e-commerce platform. Additionally, we also compare the results with using a large language model to summarize the product description, condensing the main content. The results we achieved demonstrate the positive performance of the method in improving the accuracy of the recommendation system. 

## Input - Output of this problem
![DS300 -  Input-output](https://github.com/duyngoc-adn/RECOMMENDATION-SYSTEM-FOR-E-COMMERCE-PLATFORM-INTEGRATING-PRODUCT-TITLE-DESCRIPTION-AND-IMAGE/assets/73750674/e42a1a34-308d-44fd-9c6b-c773035c7819)

## Experiment settings
![QuyTrinhThucNghiem](https://github.com/duyngoc-adn/RECOMMENDATION-SYSTEM-FOR-E-COMMERCE-PLATFORM-INTEGRATING-PRODUCT-TITLE-DESCRIPTION-AND-IMAGE/assets/73750674/3e6bea36-3fb2-4bc9-bef4-b71412bd4df5)
Our experimental process was conducted in 4 steps: summarizing description features using Gemini, aiming to compare results between summarizing description features for better results than the original description or not; embedding title, description, and image data into vectors; then calculating cosine similarity between the computed vectors, and finally sorting them and evaluating them on the P@5 measure.

## Results

### The results of the experiment without summarizing descriptions and with weighting.
![before](https://github.com/duyngoc-adn/RECOMMENDATION-SYSTEM-FOR-E-COMMERCE-PLATFORM-INTEGRATING-PRODUCT-TITLE-DESCRIPTION-AND-IMAGE/assets/73750674/25129429-74d6-4329-8a31-0f7c4041842e)

### The results of the experiment with summarized descriptions and weighting.
![After](https://github.com/duyngoc-adn/RECOMMENDATION-SYSTEM-FOR-E-COMMERCE-PLATFORM-INTEGRATING-PRODUCT-TITLE-DESCRIPTION-AND-IMAGE/assets/73750674/c8d9c483-8a38-4266-937d-2911de4348dd)

## Contact
### Authors:
Ngoc Dinh Duy Cao, Tinh Pham Phuc Do, Nguyen Dinh Van, Tin Van Huynh

Faculty of Information Science and Engineering, University of Information Technology, Ho Chi Minh City, Vietnam

Vietnam National University, Ho Chi Minh City, Vietnam

{20522020, 20521661, 20520657}@gm.uit.edu.vn and tinhv@uit.edu.vn

