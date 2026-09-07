<div align="center">

<img src="docs/assets/banner.jpg" alt="tbankvzlom" width="100%">

# tbankvzlom

**Общий ящик.** Есть ссылка — можно смотреть. Есть GitHub-аккаунт — можно закинуть файл.

[![public](https://img.shields.io/badge/доступ-по_ссылке-111111?style=for-the-badge&labelColor=FFDD2D&color=111111)](https://github.com/vakumchik/tbankvzlom)
[![upload](https://img.shields.io/badge/закинуть_файл-uploads-111111?style=for-the-badge&labelColor=FFDD2D&color=111111)](https://github.com/vakumchik/tbankvzlom/upload/main/uploads)
[![license](https://img.shields.io/badge/license-MIT-111111?style=for-the-badge&labelColor=FFDD2D&color=111111)](LICENSE)

<br>

**[＋ Добавить файл](https://github.com/vakumchik/tbankvzlom/upload/main/uploads)**
&nbsp;·&nbsp;
**[Стать редактором](https://vakumchik.github.io/tbankvzlom/editor.html)**
&nbsp;·&nbsp;
**[Открыть папку uploads](https://github.com/vakumchik/tbankvzlom/tree/main/uploads)**

</div>

---

## Ссылка, чтобы стать редактором

Отправь другу это:

**https://vakumchik.github.io/tbankvzlom/editor.html**

или напрямую форму GitHub:

**https://github.com/vakumchik/tbankvzlom/issues/new?template=editor.yml**

Человек жмёт Submit → приходит приглашение → он принимает его на  
https://github.com/vakumchik/tbankvzlom/invitations  
и может заливать файлы без fork.

Добавить кого-то вручную (только владелец):  
https://github.com/vakumchik/tbankvzlom/settings/access

---

## Как закинуть файл за 30 секунд

Не нужен git, терминал и «клон репозитория». Только браузер.

| Шаг | Что нажать |
| :---: | --- |
| **1** | Открой **[эту ссылку](https://github.com/vakumchik/tbankvzlom/upload/main/uploads)** |
| **2** | Если GitHub попросит войти — войди (аккаунт бесплатный) |
| **3** | Если предложит **Fork** — согласись. Это копия, чтобы ты мог залить файл |
| **4** | Перетащи файл в окно или нажми *choose your files* |
| **5** | Нажми **Commit changes** → **Create pull request** → **Create pull request** ещё раз |

Пул-реквест с файлом **только в `uploads/`** можно сразу мержить. У владельца репозитория файл из ссылки загрузки падает в `main` без fork.

> Уже есть доступ на запись? Тогда шаг с Fork не понадобится — файл сразу улетит в `main`.

---

## Другие способы

<details>
<summary><b>Через Issue</b> — если лень делать fork</summary>

1. [New issue](https://github.com/vakumchik/tbankvzlom/issues/new?template=drop.yml)
2. Прикрепи файл (до 25 МБ)
3. Отправь. Разберём и положим в `uploads/`

</details>

<details>
<summary><b>С компьютера, через git</b></summary>

```bash
git clone https://github.com/vakumchik/tbankvzlom.git
cd tbankvzlom
git checkout -b drop/my-file
cp ~/Desktop/файл.pdf uploads/
git add uploads/
git commit -m "drop: файл.pdf"
git push -u origin drop/my-file
```

Потом открой Pull Request в GitHub.

</details>

---

## Правила ящика

- Кладём файлы **только** в [`uploads/`](uploads)
- Не трогаем `.github/`, README и чужие файлы — такие PR бот отклонит
- Секреты, пароли, ключи, чужие паспорта — нельзя
- Это **не** банк, **не** взлом и **не** фишинг. Название — шутка. Т-Банк здесь ни при чём

---

<div align="center">

сайт-визитка: **[vakumchik.github.io/tbankvzlom](https://vakumchik.github.io/tbankvzlom)**

</div>
