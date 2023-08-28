# Customer Scoring/Churn Scoring/Campaign Response Scoring

จากข้อมูลที่ได้รับมาประกอบไปด้วยข้อมูล

![CSV](/Topic_3_Scoring/assets/images/CSV.png)

ตรวจพบว่ามีข้อมูลที่เป็น Null จึงทำการตัดออก

![CSV_NULL](/Topic_3_Scoring/assets/images/CSV_NULL.png)


![AGG_CSV](/Topic_3_Scoring/assets/images/AGG_CSV.png)

จากค่า SD ที่ได้เพื่อที่จะหา Churn จึงตัดสินใจเลือกข้อมูลสำหรับเข้าโมเดล ได้แก่
- Tenure
- CityTier
- WarehouseToHome	
- HourSpendOnApp	
- NumberOfDeviceRegistered	
- SatisfactionScore	
- NumberOfAddress	
- Complain	
- OrderAmountHikeFromlastYear	
- CouponUsed	
- OrderCount	
- DaySinceLastOrder

ทำการทดสอบกับโมเดล ดังนี้
* Logistic regression
* Random Forest Classifier
* K Nearest Neighbors Classifier
* XGBoost Classifier

![MODEL](/Topic_3_Scoring/assets/images/MODEL.png)

### SMOTE

![SMOTE_MODEL](/Topic_3_Scoring/assets/images/SMOTE_MODEL.png)

### Oversampling

![OVERSAMPLING_MODEL](/Topic_3_Scoring/assets/images/OVERSAMPLING_MODEL.png)

### Undersampling

![UNDERSAMPLING_MODEL](/Topic_3_Scoring/assets/images/UNDERSAMPLING_MODEL.png)

