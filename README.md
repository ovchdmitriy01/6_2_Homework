# Домашнее задание к занятию «Типы виртуализации: KVM, QEMU»


### Задание 1

**Ответьте на вопрос в свободной форме.**

Какие виртуализации существуют? Приведите примеры продуктов разных типов виртуализации.

1. Аппаратная - работает благодаря поддержке со стороны процессора. На чипе Intel реализована в HT, VT-x, VT-d, VMDQ. На чипе AMD - AMD-V. На чипе ARM -EL2; 

2. Программная - эмулирует все железо от процессора до сетевого адаптера. Пример: KVM, QEMU, VirtualBox, XEN, HYPER-V; 

3. Контейнерная - эмулирует несколько изолированных пространств пользователя вместо одного. Виртуальная среда запускается прямо из ядра хостовой операционной системы. Пример: Docker, Kubernetes;

4. Хостинговая - эмулирует железо в облаке. Пример: AWS, GCP, Яндекс и т.д.;

---


### Задание 2 

Выполните действия и приложите скриншоты по каждому этапу:

1. Установите QEMU в зависимости от системы (в лекции рассматривались примеры).
2. Создайте виртуальную машину.
3. Установите виртуальную машину.
Можете использовать пример [по ссылке](https://dl-cdn.alpinelinux.org/alpine/v3.13/releases/x86/alpine-standard-3.13.5-x86.iso).

Пример взят [с сайта](https://alpinelinux.org). 

<a href="https://ibb.co/x8s2f8f"><img src="https://i.ibb.co/Nn3Fmnm/6-2-1-1.png" alt="6-2-1-1" border="0"></a>
<a href="https://ibb.co/y8m2w95"><img src="https://i.ibb.co/khVZR70/6-2-2.png" alt="6-2-2" border="0"></a>
<a href="https://ibb.co/yFH6Fd6"><img src="https://i.ibb.co/d48P4jP/6-2-3.png" alt="6-2-3" border="0"></a>
 
---

### Задание 3 

Выполните действия и приложите скриншоты по каждому этапу:

1. Установите KVM и библиотеку libvirt. Можете использовать GUI-версию из лекции. 
2. Создайте виртуальную машину. 
3. Установите виртуальную машину. 
Можете использовать пример [по ссылке](https://dl-cdn.alpinelinux.org/alpine/v3.13/releases/x86/alpine-standard-3.13.5-x86.iso). 

Пример взят [с сайта](https://alpinelinux.org). 

<a href="https://ibb.co/0JQS2xw"><img src="https://i.ibb.co/ryvS0VW/6-3-1.png" alt="6-3-1" border="0"></a>
<a href="https://ibb.co/dcs9rSw"><img src="https://i.ibb.co/LPDw8MX/6-3-2.png" alt="6-3-2" border="0"></a>
<a href="https://ibb.co/6wFTFHy"><img src="https://i.ibb.co/H4qbqtK/6-3-3.png" alt="6-3-3" border="0"></a>

 ---

### Задание 4

Выполните действия и приложите скриншоты по каждому этапу:

1. Создайте проект в GNS3, предварительно установив [GNS3](https://github.com/GNS3/gns3-gui/releases).
2. Создайте топологию, как на скрине ниже.
3. Для реализации используйте машину на базе QEMU. Можно дублировать, сделанную ранее. 

![image](https://user-images.githubusercontent.com/73060384/118615008-f95e9680-b7c8-11eb-9610-fc1e73d8bd70.png)

<a href="https://ibb.co/z7RpwJd"><img src="https://i.ibb.co/D8Chnpd/6-4-1.png" alt="6-4-1" border="0"></a>
<a href="https://ibb.co/m9BC38x"><img src="https://i.ibb.co/bs3gkJf/6-4-3.png" alt="6-4-3" border="0"></a>
<a href="https://ibb.co/z7cQS30"><img src="https://i.ibb.co/pRDb3H9/6-4-2.png" alt="6-4-2" border="0"></a>


