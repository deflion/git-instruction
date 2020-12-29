# GIT. Система контроля версий

**Система управления версиями** *(англ. Version Control System)* — программное обеспечение для облегчения работы с изменяющейся информацией. Система управления версиями позволяет хранить несколько версий одного и того же документа.

Ситуация, в которой электронный документ за время своего существования претерпевает ряд изменений, достаточно типична. При этом часто бывает важно иметь не только последнюю версию, но и несколько предыдущих. В простейшем случае можно просто хранить несколько вариантов документа, нумеруя их соответствующим образом. Такой способ неэффективен (приходится хранить несколько практически идентичных копий), он требует повышенного внимания и дисциплины и часто ведёт к ошибкам, поэтому были разработаны средства для автоматизации этой работы.

## **GIT**
![](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png "Логотип GIT" )

[Логотип GIT](https://git-scm.com/downloads/logos " ") Автор: *Jason Long*

Проект был создан [Линусом Торвальдсом](https://ru.wikipedia.org/wiki/%D0%A2%D0%BE%D1%80%D0%B2%D0%B0%D0%BB%D1%8C%D0%B4%D1%81,_%D0%9B%D0%B8%D0%BD%D1%83%D1%81 "https://ru.wikipedia.org/wiki/Торвальдс,_Линус") для управления разработкой ядра Linux, первая версия выпущена 7 апреля 2005 года. Большую часть времени проект поддерживается Джунио Хамано.

Это распределённая система управления версиями, что значит, что центрального репозитория проекта в *GIT* не существует: все копии создаются равными. Разработчики могут обмениваться изменениями до их объединения в официальную ветвь.

В *GIT* практически все операции совершаются локально, сеть используется только для операций обмена с удаленными репозиториями. Разработчики могут работать локально в автономном режиме, пока программный код не будет готов к публикации.

### **Установка GIT**

![](https://raw.githubusercontent.com/deflion/git-instruction/main/img/windows_logo.png?token=AFIG5TGW3FOL3AH3GS2QKLS75NDH6 "Windows logo") | ![](https://raw.githubusercontent.com/deflion/git-instruction/main/img/ubuntu_logo.png?token=AFIG5TEOJNLVZKJXQNX3XLK75NERU "Ubuntu logo") | ![](https://raw.githubusercontent.com/deflion/git-instruction/main/img/MacOS_wordmark.svg.png?token=AFIG5TH6NLIHJFCOCBDCSXK75NEQG "Mac logo")
------------- | ------------- | -------------
[Для Windows](https://github.com/deflion/sf-git-readmd/blob/main/git-inst-win.md)| [Для Linux/Unix](https://github.com/deflion/sf-git-readmd/blob/main/git-inst-unix.md)| [Для MacOS](https://github.com/deflion/sf-git-readmd/blob/main/git-inst-mac.md)

 
**Другие способы установки**

Существует огромное количество способов установки GIT. [Смотрите их в официальной документации](https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-Git "Установка Git").

