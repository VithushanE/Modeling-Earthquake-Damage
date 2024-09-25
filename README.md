# Modeling-Earthquake-Damage
### Predicting Building Damage from the 2015 Gorkha Earthquake in Nepal

In this competition, the objective was to predict the level of damage to buildings caused by the 2015 Gorkha earthquake in Nepal. The provided test dataset had an unlabeled target variable, so I aimed to build a model using the training dataset to accurately predict this target. 

The process involved several key steps: 

1. **Data Integration**: Combining multiple datasets to create a comprehensive training set.
2. **Data Cleaning**: Rigorous data cleaning ensured high-quality data, addressing any inconsistencies or missing values.
3. **Feature Selection**: Identifying and selecting relevant features that would contribute to effective modeling.
4. **Model Training and Evaluation**: Given that the target variable represented a multiclass classification problem, I initially experimented with Decision Trees. 

I subsequently applied various ensemble methods, including Random Forest, LightGBM, XGBoost, and CatBoost. Ultimately, the Random Forest model emerged as the best performer, demonstrating strong predictive accuracy in assessing building damage levels.

For more details, you can refer to the original competition page [here](https://www.drivendata.org/competitions/57/nepal-earthquake/page/134/).
