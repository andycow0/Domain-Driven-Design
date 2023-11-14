# O - Objective (觀察外在客觀、事實)

* Domain 中 Service 適合用動作 (action) 或操作 (operation) 表示，不應將之強加至 Entity 或 Value Object 上 
    * 做某項 stateless 的 activity
* Traverse (遍歷)
    * 簡化實作
    * 提高關聯的表達能力
    * 最終為簡化對 task 或模型物件基本涵義來說【不重要的關聯】
* Entity (Reference Object)
    > ex. 一個人、城市、汽車、銀行交易
    > 1. 整個生命週期中具有連續性
    > 2. 其區別不是由【對使用者非常重要的屬性】決定的
    * 組成
        * Identity (memory reference? variable?)
            * ex. Seat number
            
        * Attribute
            * 隨時間推移。發生改變
    * 特性
        * 唯一性 (unique)
            * 每個 Entity 都須有建立標識的操作方式，以便與其他物件區隔
            * 【簡單約束】ex. unique key
        * 不可變 (immutable)
            * 以技術框架使其保持不變，或透過工程紀律約束
    
    


# R - Reflective (重視內在感受、反應)

* 多用途的 attribute 不可作為 Entity 的標識

# I - Interpretive (詮釋意義、價值、經驗)

* 舉例有點跳 Tone 不連貫、不一致
 
# D - Decisional (找出決定、行動)

* 

