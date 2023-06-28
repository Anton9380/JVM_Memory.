# JVM.организация памяти, сборщики мусора, VisualVM.
### ClassLoader
1. ***JVM*** проверяет уникальность классов. Загрузчик классов подгружает класс JvmComprehension и пакеты указанные в pom.xml(Memory)(package org.example).
2. Подгрузка(loading) :
   1. ***Application***(приложение) ***ClassLoader*** делегирует запрос ***Platform***(в других источниках Extension - расширение) ClassLoader.