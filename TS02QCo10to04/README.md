## TypeScript 02
## Chapter 02: Basic Types
It is my coding practice with the TUTORIAL of Dave Gray. 

## Source
### Dave Gray 的 TypeScript 資源
https://github.com/gitdagray/typescript-course

### Dave Gray 的 TypeScript 課程
https://youtube.com/playlist?list=PL0Zuz27SZ-6NS8GXt5nPrcYpust89zq_b&si=8IJALfXOcur2OO_K

### Dave Gray 的 YouTube 頻道
https://www.youtube.com/@DaveGrayTeachesCode

## Quick Concept offline
###  1. Intro
        教學影片開頭和介紹

###  2. Welcome

###  3. TS Terminology
        強類型語言: Strong Typed Language
        強類型語言: TypeScript
        鬆散類型語言: Loosely Type Language / Weakly Type Language
        鬆散類型語言: JavaScript
        靜態類型: Static Typing
        靜態類型: TypeScript
        動態類型: Dynamic Typing
        動態類型: JavaScript
        TypeScript = 強類型語言 + 靜態類型
        JavaScript = 鬆散類型語言 + 動態類型

###  4. Starter Code
        在 terminal 輸入 tsc -w

###  5. Inference, Implicit & Explicit meanings
        (1)宣告 myName
        (2)宣告 myName，設定類別為 string

###  6. TS provides more information
        (1)宣告 myName 為字串，
        又宣告 myName 為數值會顯示錯誤
        (2)可以先設定 myName 的類別為字串，接著宣告 myName
        (3)修改 myName
    
###  7. String, Number, and Boolean types
        (1)宣告 myName 為 Dave，設定類別為 string；
        設定 meaningOfLife 類別為 number
        設定 isLoading 類別為 boolean
        宣告 myName, meaningOfLife, isLoading
        (2)宣告 isLoading 為 42 會顯示錯誤
        (3)宣告 meaningOfLife 為 code 會顯示錯誤

###  8. The any type
        (1)設定 album 類別為 any；
        宣告 album 為 Van Halen 不會顯示錯誤
        (2)宣告 album 為 1984 不會顯示錯誤
        (3)宣告 album 為 true 不會顯示錯誤

###  9. Function parameters
        (1)宣告 sum，參數為 a 和 b，回傳 a + b；
        參數隱含的類別為 any，
        因為錯誤無法轉譯為 main.js
        (2)設定參數為 a 和 b 的類別為 number，
        sum 的類別亦為 number
        (3)設定參數為 a 的類別為 number，b 的類別為 string
        sum 的類別亦為 string

### 10. Union types
        (1)設定 album 類別為 string 或 number，
        宣告 album 為 1984，沒有顯示錯誤
        (2)宣告 album 為 Van Halen，沒有顯示錯誤
        (3)宣告 album 為 true，顯示錯誤
        (4)宣告 album 為 5150，沒有顯示錯誤
        (5)設定 postId 類別為 string 或 number，
        (6)設定 isActive 類別為 number 或 boolean
        (7)修改 isActive 類別為 number, boolean 或 string

### 11. When in doubt, check inference
        (1)宣告 regex 為 /\w+/g
        (2)確認推論，設定 regex 類別為 RegExp

### 12. Quick review
        複習