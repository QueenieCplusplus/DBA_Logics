# DBA_Logics
(查詢)邏輯的最佳化

操作資料通常以資料庫中的關聯代數為基礎並且以查詢語法樹作為載體，並透過檢查語法樹，保障了語法樹中的語法單元的語義，以及最後結果不變，上述情況下的等價變化，最終，獲得了一個沒有容錯成分的『查詢語法樹』。

# 邏輯最佳化要從查詢敘述的資料結構而起

    Info

    Base Relational Info (基表資訊)

    Join Info (連接資訊)

    Restrict Info (約束資訊)

    Path Info & Place Holder (物化資訊或稱路徑資訊)

    Cost: pages, tuples, baserestrictcost (代價資訊)

    Global (全域資訊)
    
    RelOptInfo
    
    EC, EquivalenceClasses (等式運算)
