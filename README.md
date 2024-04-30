<picture>
 <source media="(prefers-color-scheme: dark)" srcset="https://www.ncaa.org/images/2021/9/29/March_Madness.jpg">
 <source media="(prefers-color-scheme: light)" srcset="https://www.ncaa.org/images/2021/9/29/March_Madness.jpg">
 <img alt="YOUR-ALT-TEXT" src="YOUR-DEFAULT-IMAGE" width="192" height="108">
</picture>

# marchmadness
This approach uses KenPom data for each team from 2008-2023 to predict each years March Madness results. It addresses discrepancies in team names between the KenPom and NCAA Tournament files, employs Recursive Feature Elimination (RFE) to identify 9 key features from KenPom data, focusing on the 2008 and 2009 datasets. Subsequently, a Random Forest model is trained and tested using data from 2008 to 2023. Finally, the model is applied to predict the results of the 2024 tournament and construct a complete bracket based on these predictions.
