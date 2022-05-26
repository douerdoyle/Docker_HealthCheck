# Docker_HealthCheck
使用 Docker 的 Health 功能，搭配 Container 實現自動重啟處於非健康狀態的 Container<br>

# 說明
docker-compose 檔案內有設定 Container 可使用的 CPU 與 Memory 上限<br>
名為 autohealcheck 的 Container 由於與 Docker 的檔案有做映射，故可以取得相同環境下有無其他 Contaienr 處於不健康的狀態<br>
並可重啟處於不健康狀態的 Contaienr，並寄信通知<br>
