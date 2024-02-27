

# Anti-fraud Risk in Transaction

- keywords: Python; Lightgbm; Xgboost



The data for this project was sourced from a coursework on anti-fraud risk identification, providing basic account information, operational behavior, and transaction behavior of risky accounts. [# dataset link]



The dataset consists of three tables: _base, _op, and _trans, which include features like categorical encoding with order, categorical encoding without order, and continuous encoding. These data were used to analyze account characteristics, for feature mining and to establish a supervised machine learning model to effectively identify accounts with high-risk transactions.



This project primarily used methods such as data analysis, feature engineering, and machine learning modeling to identify high-risk transactions. Firstly, the data, including basic account information, operational behavior, and transaction behavior, was analyzed, and feature engineering was performed. Subsequently, models like CatBoost, LightGBM, and XGBoost were trained and optimized. Through evaluation and comparison of the models, it was determined that the LightGBM model performed the best, achieving the highest AUC and F1-score, making it the most suitable for solving this problem.



本项目的数据来源于一个关于反欺诈风险识别的课程作业，提供了风险账户的基础信息、操作行为信息和交易行为信息。训练数据集包括三张表：_base、_op 和_trans，其中包含了有大小关系的类别编码、无大小关系的类别编码和连续型编码等特征。这些数据被用于分析账户开户特征、设备操作特征、交易频次、交易时间、交易金额、地域分布等维度进行特征挖掘，并建立了有监督的机器学习模型，以有效甄别存在高风险交易的账户。

项目主要采用了数据分析、特征工程和机器学习建模等方法来识别高风险交易。首先，对账户基本信息、操作行为和交易行为等数据进行了异常分析，并进行了特征衍生。接着，使用了 CatBoost、LightGBM 和 XGBoost 等模型进行训练和优化。通过对模型的评估和比较，最终确定了使用 LightGBM 模型效果最好，具有最高的 AUC 和 F1-score。