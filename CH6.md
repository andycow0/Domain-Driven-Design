# O - Objective (觀察外在客觀、事實)

* Aggregate
  * 透過定義清晰所屬關係和邊界，避免「混亂、複雜的物件關係網」以實作模型的內聚
  * 物件更改的一致性、謹慎的鎖定機制、遵守固定規則
  * root
    * 包含的特定 Entity
  * boundary 
    * 定義內部有什麼
  * invariant (固定規則)
    * 資料變化時須保持一致性規則
  * 只允許外部物件對 root 控制存取，不可繞過其修改內建物件，可確保任何狀態變化時，Aggregate 能做一個【整體】並滿足 invariant

* Factory
  * 抽象且不予其他物件發生耦合，一種負責建立其他物件的程式元素
  * 基本需求
    1. 每個方法都是原子的 (atomic)
    2. 應該被抽象為所需的類型 (interface? abstract clss?)
    