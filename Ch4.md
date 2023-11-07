# O - Objective (觀察外在客觀、事實)

* 軟體程式需透過 design 和 code 來執行許多不同類型的任務

* 領域有關的 code 分散在大量的其他程式碼中，查看和分析領域程式碼變得困難
    * ex. UI、DataBase access in OOP business object
    * 影響分析
    * 缺乏物件實作一致
    * 影響自動化測試

* 關注點分離
* 程式碼必須簡單明瞭
* 分層式架構 (Layered Architecture)

* 多數成功的子架構
    * 標準架構
        * UI
        * Application (Controller?)
        * Domain (業務核心)
        * Infrastructure
    > 將 Domain 分離出來才是實作 Model Driven Design 的關鍵
    > * 標準只與上層進行鬆散的耦合 (coupling)
    > * Domain Layer 應該與其他層分開，不須考慮顯示與儲存的問題以及管理應用程式的任務內容，專注於領域模型的業務邏輯與知識

* Domain 實作獨立是 DDD 的前提

### Smart UI Pattern
* Anti-Pattern
* 與 DDD 不相容
* 簡單、期望值不高、開發周期短的專案不適用 DDD
* 4GL Tools
* 一旦使用了。除非重寫全部的模組，否則不能改用其他的設計方法



# R - Reflective (重視內在感受、反應)

* 內聚
* Domain 與 system 各部分保持鬆散耦合
* Model-Design Driven? Domain-Design Driven?

# I - Interpretive (詮釋意義、價值、經驗)

* 最好的框架既能解決複雜問題，也能讓開發人員集中精神表達模型
* 適切地找出符合專案目標的開發框架
* why、when for framework
 
# D - Decisional (找出決定、行動)

* 有些 framework 使用起來複雜、缺乏靈活，建構時耗費過多精力
* 正確地使用 framework 可讓 developer 更專注於【核心業務問題的建模工作】

