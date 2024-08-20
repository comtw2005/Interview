靜態成員 (Static Members)

    定義: 在類別中，使用 static 關鍵字宣告的成員稱為靜態成員。
    種類: 靜態成員包括靜態方法、靜態變數和靜態塊。
    特性:
        屬於類別本身，而非特定物件。
        在類別載入時即被初始化，並可以透過類別名稱直接存取，不需要建立物件。
        所有物件共享同一個靜態成員。

main() 方法

    程式執行起點: Java程式執行時，JVM會先尋找並執行 public static void main(String[] args) 這個方法。
    必須定義: 每一個可執行的Java程式都必須有一個 main 方法。
    作用: 作為程式的進入點，通常用來初始化程式環境或執行主要的程式邏輯。

類別結構

    多個Java檔案: 一個Java應用程式可以由多個.java檔案組成，每個檔案中可以包含一個或多個類別。
    單一執行點: 雖然一個應用程式可以有多個類別，但只能有一個 main 方法，且這個方法只能屬於一個類別。

範例程式碼

    Hello World: 範例程式展示了如何使用 main 方法輸出 "Hello World"。
    無 main 方法的類別: 說明了如果一個類別沒有 main 方法，無法直接執行。

    ![圖片](https://github.com/user-attachments/assets/b3d04aac-bbe4-4fc1-a815-46bf68c62984)
    
    ![圖片](https://github.com/user-attachments/assets/1b96c6c1-89b7-46d4-9d01-b97ab415360a)


結論

靜態成員，尤其是 main 方法，是Java程式設計的基礎。理解靜態成員的特性和 main 方法的作用，對於撰寫Java程式至關重要。

延伸思考

    靜態變數與物件變數的差異: 靜態變數屬於類別，物件變數屬於物件。
    靜態方法能否存取非靜態成員: 一般來說，靜態方法無法直接存取非靜態成員，因為靜態方法在物件建立之前就可以被呼叫。
    靜態塊的作用: 靜態塊用於在類別初始化時執行一些特定的程式碼

ref: https://www.instagram.com/p/C-myRRvSiPK/?img_index=1
