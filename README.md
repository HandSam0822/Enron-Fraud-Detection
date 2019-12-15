# Fraud_detection-Kaggle-competition
Getting 91% accurcy

Enron Fraud Dataset 安隆公司詐欺案資料集

安隆公司曾是一間能源公司，2001 年破產前是世界上最大的電力、天然氣及電信公司之一。  
擁有上千億資產的公司於 2002年竟然在短短幾周內宣告破產，才揭露其財報在多年以來均是造假的醜聞。  

本專案的目標為，透過高層經理人內部的 mail 來往的情報以及薪資、股票等財務特徵，  
訓練出一個機器學習模型來幫忙找到可疑的詐欺犯罪者是誰!    


有關財務的特徵:   
['salary', 'deferral_payments', 'total_payments', 'loan_advances', 'bonus',  
'restricted_stock_deferred', 'deferred_income', 'total_stock_value', 'expenses',   
'exercised_stock_options', 'other', 'long_term_incentive','restricted_stock', 'director_fees'] (單位皆為美元)。  

有關 email 的特徵: ['to_messages', 'email_address', 'from_poi_to_this_person',  
'from_messages', 'from_this_person_to_poi', 'shared_receipt_with_poi'] (除了 email_address，其餘皆為次數)  

