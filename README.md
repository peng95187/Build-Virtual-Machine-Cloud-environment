# Build-Virtual-Machine-Cloud-environment
Google Cloud Platform, Compute Engine

從公開映像檔建立 VM 執行個體

    1. 在 Google Cloud Console 中，轉到 VM執行個體頁面

    2. 選擇Project，然後點擊繼續。

    3. 點擊 "建立執行個體"
       
    4. 為VM 指定一個名稱。

    5. (非必要)更改此 VM 的區域。選擇asia-east1 (台灣)

    6. 為此 VM 選擇機器配置。
    E2 最多可支援 32 個 vCPU 和 128 GB 記憶體。相當適合用於微服務、虛擬桌面和開發環境。 N2、N2D 和 N1最多可搭載 224 個 vCPU 和 896 GB 記憶體，適合用於網路服務、應用程式服務和後端應用程式。
    7. 在開機磁碟部分，點擊變更以設定開機磁碟。

    8. 在公開映像檔選項中，選擇以下選項：
    • 作業系統
    • 版本 (OS)
    • 開機磁碟類型
    • 大小 (GB)

    9. 點擊選取以確認開機磁碟選項。
    
    10. 選擇允許 HTTP 流量和允許 HTTPS 流量以允許到 VM 的 HTTP 或 HTTPS 流量。

    11. 點擊建立以創建並啟動 VM



