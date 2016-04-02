# Kaggle_Airbnb_final_Top_20-
This is the final model I used in the Kaggle Airbnb competition

1. Clean the data, find outliers, fill NA
2. Feature engineering, Add Day_in_week, 
3. Use Session data, I selected 10 most important features in Session ["user_id","unknown","booking_request","click","data","message_post","modify","partner_callback","submit","view"], and aggregate into the training and testing data. 
4. Test and tune model, I tried several models and XGBoost performs best. 
 
