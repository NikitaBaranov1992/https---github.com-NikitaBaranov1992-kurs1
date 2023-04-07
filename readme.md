# Отличия git pull от git fetch

> **Простыми словами, git pull = git fetch + git merge**

- [x] *Когда вы делаете pull*, git старается автоматически выполнить всю работу за вас. Этот процесс зависит от контекста, git объединит все коммиты и обновит ту ветку, на которой вы в данный момент находитесь. Слияние осуществляется автоматически, без вашего участия. <span style="color:red"> *Если система обнаружит несопоставимые различия, произойдет конфликт.*</span>

- [x] *Когда вы делаете fetch*, git просто собирает все коммиты целевой ветки, которых у вас еще нет, и сохраняет их локально. Объединения веток при этом не происходит. Это очень полезно, если вам необходимо актуальное состояние репозитория, но оно может нарушить вашу работу.  <span style="color:green"> *Ознакомившись с изменениями, вы можете слить их в вашу ветку с помощью merge.*</span>



