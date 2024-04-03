# Executive Summary

In recent years, the field of data science has evolved beyond being a conventional discipline, emerging as a catalyst for innovation across diverse industries. This escalating interest and widespread adoption of data science globally underscore its transformative potential in reshaping industries, enabling informed decision-making, and addressing intricate challenges. In this context, we delve into the impact of data science within the Philippines. [1]

Our objective is to fully grasp the growth opportunities that data science offers within the Philippine context, particularly in terms of engagement across different hierarchical levels within the Filipino community. To achieve this, we conducted an analysis of posts from Facebook pages relevant to the Philippines, focusing on keywords such as "data science," "machine learning," and "artificial intelligence" from 2021 to the present. Our analysis entailed the utilization of hierarchical forecasting using both statistical and machine learning models, coupled with various reconciliation strategies. The aim was to forecast the trajectory of data science engagement across distinct levels within our hierarchical structure.

The outcome of our analysis indicated that the AutoARIMA model, combined with a Bottom-Up reconciliation strategy, yielded the most promising results. Employing these methods, we were able to craft compelling narratives based on the data. One particularly noteworthy insight pertains to the Education and Learning cluster, where we observed a discernible increase in interest and engagement. This signals substantial potential for nurturing data science initiatives and fostering organic growth within this sector. Furthermore, we identified an opportunity to promote data science in the Entertainment cluster, where engagement levels were comparatively lower.

For the enhancement of our study, we recommend expanding our scope by incorporating additional social media platforms and exploring diverse hierarchical structures. Such an expansion would facilitate a more comprehensive understanding of community engagement and provide fresh analytical perspectives.

Drawing from the insights gained through this project, we advocate for businesses to seize potential startup opportunities aimed at addressing unmet needs within the education sector. Lastly, we propose that data scientists align their work with the values and interests of the target communities. By doing so, engagement levels can be optimized, ensuring that their efforts resonate effectively within these multifaceted contexts.

# Problem Statement

How can we grasp the evolving appeal of data science in the Philippines for informed growth and promotion strategies in the next quarter?

# Motivation

Our study endeavors to address the pressing question of how to comprehensively understand the evolving appeal of data science in the Philippines, with a clear objective of informing strategic growth and promotion strategies for the upcoming quarter.

<img src=data_science_trend.png>

Through this endeavor, we aspire to facilitate a seamless alignment between the aspirations of the Filipino community and the dynamic realm of data science, ultimately unlocking strategic opportunities for sustainable growth and development.

<img src=demand_ds>

# About the Data

The dataset comprises Facebook page data relevant to the Philippines, spanning from January 2021 to August 2023. The dataset contains various attributes that capture information about different Facebook pages and their posts, with a focus on topics related to "data science," "machine learning," and "artificial intelligence."

<img src=dataset_fb.png>

This dataset, comprising 18,913 rows of data, was scraped from publicly accessible Facebook pages. It offers a comprehensive array of attributes, including page names, categories, post timestamps, types, and clustering labels. Additionally, it includes post messages and detailed engagement metrics, encompassing likes, comments, shares, as well as emotional reactions like Love, Wow, Haha, Sad, Angry, and Care. This resource-rich dataset is a valuable asset for researchers and analysts exploring data science, machine learning, and artificial intelligence trends on Facebook in the Philippines from January 2021 to August 2023.

<span style="font-size: 14px">
    <center><b>Table 1. Facebook Raw Data Key Attributes</b></center>
</span>

| Attribute              | Description                                                   |
|:-----------------------|:--------------------------------------------------------------|
| Page Name              | The name of the Facebook page.                                |
| Page Category          | The category or classification of the Facebook page.         |
| Post Created           | The timestamp of when a post was created.                     |
| Post Created Date      | The date when a post was created.                              |
| Type                   | The type of post (e.g., Photo, Native Video, Link).            |
| Cluster                | A clustering label; group of page categories.                               |
| Page Admin Top Country | The top country associated with the page admin.                |
| Message                | The content or message of the post.                           |
| Total Interactions     | The total number of interactions (likes, comments, shares, etc.) for each post. |
| Likes, Comments, Shares, Love, Wow, Haha, Sad, Angry, Care | The breakdown of specific interactions for each post. |

# Conclusion

Through this project, we explored the evolving landscape of data science interest and engagement within different levels in our hierarchy, with a particular focus on the changes following ChatGPT's release. Our investigation involved through experimentation using various statistical and machine learning models. Among these models, the `AutoARIMA` model with `Bottom-Up` reconciliation has the best category-level forecasting performance for our dataset. Using `AutoARIMA` as our best model with `Bottom-Up` reconciliation as our best strategy in our hierarchical forecasting framework, we gained a nuanced understanding of engagement levels across different communities. The forecasts we generated revealed compelling narratives.

<img src=conclusion_ds.png>

Our findings show an increase in interest and engagement potential in high-volume conversations within the Business and Education communities, hinting at substantial potential for nurturing data science initiatives and the cultivation of organic growth. On the other hand, we identified communities like the Entertainment community presenting a unique opportunity for promotion, given its comparatively lower engagement levels.

Our project transcends mere analysis. It empowers us to provide actionable insights, thereby bridging the gap between the increasing significance of data science and its untapped potential in the Philippines. Through this endeavor, we aim to contribute to the elevation of data science, leveraging its transformative power for promotion in a broader societal landscape.

# Recommendations

Following the insights presented in this project, we have several recommendations for the improvement of this study, its implications for businesses, and the guidance it offers to data scientists:

<img src=reco_ds.png>

1. To enhance the robustness of this study, we can broaden our scope by including additional social media platforms and exploring different hierarchical structures. This expansion allows for a more comprehensive understanding of community engagement and offer fresh perspectives on hierarchical structures for analysis.
2. Beyond mere mentions, we can explore the sentiment of these messages. This approach will provide a more nuanced perspective, allowing us to gain clearer insights into how various communities perceive data science.
3. In terms of business implications, our forecasts reveal potential startup opportunities that can address the unmet needs within the education sector. This insight could be leveraged to identify and capitalize on gaps in needs of the education sector.
4. From a data scientist's standpoint, our forecasts empower us to align our work with the values and interests of our target communities. By doing so, we can optimize engagement levels and ensure that our efforts resonate effectively within these diverse contexts.

These recommendations not only enrich our understanding of this study but also provide valuable insights for businesses seeking growth opportunities and data scientists striving to make a meaningful impact within their target communities.

# References

**Data Science**

[1] International Labour Organization & Australian Aid. (2020). The Future of Work in the Philippines: Assessing the impact of technological changes on occupations and sectors. Retrieved from https://www.ilo.org/wcmsp5/groups/public/---asia/---ro-bangkok/---ilo-manila/documents/publication/wcms_762207.pdf

[2] Parmezan, Antonio & Alves de Souza, Vinícius & Batista, Gustavo. (2019). Evaluation of statistical and machine learning models for time series prediction: Identifying the state-of-the-art and the best conditions for the use of each model. Information Sciences. 10.1016/j.ins.2019.01.076. Retrieved from https://www.researchgate.net/publication/330742498_Evaluation_of_statistical_and_machine_learning_models_for_time_series_prediction_Identifying_the_state-of-the-art_and_the_best_conditions_for_the_use_of_each_model

**Time-Series Analysys**

[3] Olivares, K., Garza, F., Luo, D., et. al. (July 2022). HierarchicalForecast: A Reference Framework for Hierarchical Forecasting in Python. Retrieved from https://arxiv.org/abs/2207.03517

[4] Hyndman, R.J., & Athanasopoulos, G. (2021). “Forecasting: principles and practice, 3rd edition: Chapter 11: Forecasting hierarchical and grouped series.”. OTexts: Melbourne, Australia. OTexts.com/fpp3 Accessed on July 2022. Retrieved from https://otexts.com/fpp3/hierarchical.html

[5] Orcutt, G.H., Watts, H.W., & Edwards, J.B.(1968). Data aggregation and information loss. The American Economic Review, 58 , 773{787). Retrieved from https://www.jstor.org/stable/1815532

[6] Munim, Ziaul. (2022). State-space TBATS model for container freight rate forecasting with improved accuracy. Maritime Transport Research. 3. 100057. 10.1016/j.martra.2022.100057. Retrieved from https://www.researchgate.net/publication/359200514_State-space_TBATS_model_for_container_freight_rate_forecasting_with_improved_accuracy

[7] Orcutt, G.H., Watts, H.W., & Edwards, J.B.(1968). “Data aggregation and information loss”. The American Economic Review, 58 , 773{787). Retrieved from https://www.jstor.org/stable/1815532

[8] Wickramasuriya, S. L., Athanasopoulos, G., & Hyndman, R. J. (2019). “Optimal forecast reconciliation for hierarchical and grouped time series through trace minimization”. Journal of the American Statistical Association, 114 , 804–819. doi:10.1080/01621459.2018.1448825.. - Wickramasuriya, S.L., Turlach, B.A. & Hyndman, R.J. (2020). “Optimal non-negative forecast reconciliation”. Stat Comput 30, 1167–1182, https://doi.org/10.1007/s11222-020-09930-0.

[9] Rob J. Hyndman, Yeasmin Khandakar (2008). “Automatic Time Series Forecasting: The forecast package for R”. Retrieved from https://www.jstatsoft.org/article/view/v027i03

[10] Hyndman, Rob, et al (2008). “Forecasting with exponential smoothing: the state space approach”. Retrieved from https://robjhyndman.com/expsmooth/

[11] Puwasala Gamakumara Ph. D. dissertation. Monash University, Econometrics and Business Statistics (2020). “Probabilistic Forecast Reconciliation”. Retrieved from https://bridges.monash.edu/articles/thesis/Probabilistic_Forecast_Reconciliation_Theory_and_Applications/11869533

[12] Panagiotelis A., Gamakumara P. Athanasopoulos G., and Hyndman R. J. (2022). “Probabilistic forecast reconciliation: Properties, evaluation and score optimisation”. European Journal of Operational Research. Retrieved from https://www.sciencedirect.com/science/article/abs/pii/S0377221722006087

[13] Makridakis, Spyros & Hibon, Michele. (2000). The M3-Competition: Results, Conclusions and Implications. International Journal of Forecasting. 16. 451-476. 10.1016/S0169-2070(00)00057-1. 

[14] Hyndman, R., Koehler, A. (November 2005). Another look at measures of forecast accuracy. Retrieved from https://www.robjhyndman.com/papers/mase.pdf
