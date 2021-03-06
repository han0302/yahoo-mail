# 使用案例

|案例名稱|註冊作業|
|----|-----|
|使用案例描述|讓用戶申請平台註冊
|主要參予者|使用者
|利害關係人與目標|使用者:申請平台註冊
|前置條件|引入使用者成功資料
|後置條件|使用者完成平台申請作業
|主要成功情節|1.使用者點選註冊鍵，展開註冊畫面並選擇註冊使用者身分<br>2.需於該⾴⾯填入帳號、密碼、密碼再次確認、居住地址與個人基本資料與聯絡資訊(email)<br>3.若是內部身分要再填寫加密文件;<br>4.按下確定鍵
|例外情節|無
|其他需求|當填入email時，需查看email有無註冊過資訊<br>密碼與密碼再次確認的字串內需符合英文⼤⼩寫、數字，⻑度需藉於(包含)8⾄(包含)16<br>若密碼與再次確認密碼不同則出現紅色驚嘆號

|案例名稱|信箱作業|
|----|-----|
|使用案例描述|寄件者與收信者可以用email進行連絡
|主要參予者|寄件人、收件人
|利害關係人與目標|寄件者與收件者可以互相進行聯絡
|前置條件|寄件人與收件人完成登入系統動作而寄件人也已寄出完信件
|後置條件|能互相發送訊息
|主要成功情節|1.當寄件人完成登入與寄出信件;收件人完成登入動作<br>2.寄件人與收件人會同時收到雙方email信件進行聯絡
|例外情節|無
|其他需求|無

|案例名稱|使用者基本資料管理流程
|----|-----|
|使用案例描述|平台人員媒合成功或未成功時基本資料給予的權限處理
|主要參予者|平台人員
|利害關係人與目標|平台人員給予使用者看取個人資料權限
|前置條件|平台人員完成登入流程
|後置條件|查看使用者媒合成功或未成功
|主要成功情節|1.當使用者媒合成功時，平台人員會給予使用者查看個人資料的權限
|例外情節|*1a.如果媒合未成功，平台人員不給予使用者查看email的權限
|其他需求|無
