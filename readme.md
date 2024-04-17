# Запуск миграций

dotnet fm migrate -p postgres -c "Host=localhost; Port=5432; Timeout=600; User ID=postgres; Password=123456; Database=info_
kiosk" -a .\InfoKiosk.Migrations.dll

