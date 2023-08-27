PowerShell Script for Shutting Down Computers and Generating Reports
Description:
This script allows you to shut down multiple computers and generate a report on the operation status. The script iterates through a list of specified computers, checks their availability, and performs a shutdown. Subsequently, it creates a CSV report indicating the status of each computer after the operation.

Usage:

Open PowerShell on the computer from which you intend to run the script.
Paste the script code and save it in a file with a .ps1 extension.
Open PowerShell and navigate to the directory where the saved script resides.
Run the script using the command .\ScriptName.ps1.
Parameters:

$computerNames: An array containing the names or IP addresses of the computers you wish to shut down.
$reportFilePath: The path to the file where the report on the performed operations will be saved.
Notes:

To successfully execute the script, ensure that you have administrative privileges on the remote computers.
Before running the script, it is recommended to test it on a small number of computers in a safe environment.
Example:

powershell
Copy code
$computerNames = @(
    "Computer1",
    "Computer2"
)

$reportFilePath = "C:\Path\To\Report.csv"

# Script code...

Write-Host "Report on operations has been saved to $reportFilePath"
Important:

The script author is not responsible for any potential negative consequences of using the script without due caution. Please review the code and understand what each part does before executing the script.
Translation to Russian:
(Please note that the translation might not be perfect and might need further review by a native speaker.)

markdown
Copy code
## Скрипт PowerShell для Выключения Компьютеров и Генерации Отчетов

**Описание:**
Этот скрипт позволяет выключить несколько компьютеров и создать отчет о статусе операций. Скрипт перебирает список указанных компьютеров, проверяет их доступность и выполняет выключение. Затем он создает CSV-отчет, в котором указан статус каждого компьютера после операции.

**Использование:**
1. Откройте PowerShell на компьютере, с которого вы планируете запустить скрипт.
2. Вставьте код скрипта и сохраните его в файле с расширением `.ps1`.
3. Откройте PowerShell и перейдите в каталог, где находится сохраненный скрипт.
4. Запустите скрипт с помощью команды `.\ИмяСкрипта.ps1`.

**Параметры:**
- `$computerNames`: Массив, содержащий имена или IP-адреса компьютеров, которые вы хотите выключить.
- `$reportFilePath`: Путь к файлу, в который будет сохранен отчет о выполненных операциях.

**Примечания:**
- Для успешного выполнения скрипта удостоверьтесь, что у вас есть административные привилегии на удаленных компьютерах.
- Перед запуском скрипта рекомендуется протестировать его на небольшом количестве компьютеров в безопасной среде.

**Пример:**
```powershell
$computerNames = @(
    "Компьютер1",
    "Компьютер2"
)

$reportFilePath = "C:\Путь\К\Отчету.csv"

# Код скрипта...

Write-Host "Отчет о выполненных операциях сохранен в $reportFilePath"
Важно:

Автор скрипта не несет ответственности за возможные негативные последствия использования скрипта без должной осторожности. Пожалуйста, ознакомьтесь с кодом и понимайте, что делает каждая часть перед запуском скрипта.
