# MintyTON

https://docs.ton.org/develop/dapps/tutorials/collection-minting

Ошибка:
.\venv\Scripts\activate : Невозможно загрузить файл C:\path\venv\Scripts\activate.ps1, так как выполнение сценариев отключено в этой системе. 
Для получения дополнительных сведений см. about_Execution_Policies по адресу http://go.microsoft.com/fwlink/?LinkID=135170.
строка:1 знак:1
.\venv\Scripts\activate
~~~~~~~~~~~~~~~~~~~~~~~
CategoryInfo          : Ошибка безопасности: (:) [], PSSecurityException
FullyQualifiedErrorId : UnauthorizedAccess

Решение проблемы:
- Открываем терминал PowerShell от админа.
- Вставляем и запускаем - Set-ExecutionPolicy RemoteSigned
- На вопрос отвечаем - A
