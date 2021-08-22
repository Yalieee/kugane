# Migrate
用來管理 DB 的 schema 變化，當 schema 被改動時應該同步變更 model，並且執行指令才產生 migrate script
```
python manage.py makemigrations <app name>
```

實務上我們不會用這個來改動 schema，但透過這個可以管理 local sqlite 測試環境來使他與 production db 同步
