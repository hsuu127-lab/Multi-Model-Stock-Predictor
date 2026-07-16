# Multi-Model-Stock-Predictor
這是一個針對台積電（2330.TW）明日漲跌方向進行預測的端到端量化研究與機器學習專案。本專案建構了一套資料清洗、時序防洩漏對齊、特徵工程管道，並採用「動態滑動窗口（Rolling Window）」機制對多種機器學習模型進行基準測試（Benchmarking）。  專案中除了評估 Scikit-learn 的隨機森林（Random Forest）與 XGBoost 之外，更以 NumPy 手寫實現了基於梯度下降法（Gradient Descent）的 Logistic 回歸分類器，進行非線性與線性決策邊界的交叉驗證。
