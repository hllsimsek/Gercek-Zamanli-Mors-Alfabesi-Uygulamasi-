# Morse Code Display with Microcontroller

## 📄 Project Description

In this project, the STM32F303RE microcontroller board is used to convert user-inputted text into Morse code and display it visually through an LED. The message received via UART is processed character by character, translated into Morse code, and represented by short (`.`) and long (`-`) LED blinks. Short pauses are applied between letters, and longer pauses between words, to follow the Morse code standard.

## ⚙️ Technical Specifications

- **Microcontroller:** STM32F303RE (Nucleo board)
- **Communication Protocol:** UART (9600 baud, 8 data bits, no parity, 1 stop bit)
- **Input:** User text via UART terminal
- **Output:** Visual Morse code via LED (connected to PB0)
- **Development Environment:** STM32CubeIDE, C Language

## 🎯 Objectives

- Practice UART-based serial communication
- Control digital outputs (GPIO) to drive LEDs
- Synchronize LED blinking with Morse code timing rules

## 🚀 Extendibility

- Add audio output using a buzzer
- Support multiple LEDs for parallel signaling
- Store input/output messages using EEPROM or SD card
- Implement an LCD or OLED screen for displaying plain text alongside Morse output

---

# Mikrodenetleyici ile Mors Alfabesi Gösterimi

## 📄 Proje Açıklaması

Bu projede STM32F303RE mikrodenetleyici kartı kullanılarak terminalden girilen metin, Mors alfabesine çevrilmekte ve LED yardımıyla görsel olarak iletilmektedir. UART üzerinden alınan mesaj karakter karakter işlenmekte, her harf Mors koduna çevrilmekte ve kısa (`.`) ile uzun (`-`) yanıp sönmelerle LED üzerinden gösterilmektedir. Harfler arasında kısa, kelimeler arasında ise daha uzun bekleme süreleri uygulanarak Morse kurallarına uygunluk sağlanmaktadır.

## ⚙️ Teknik Özellikler

- **Mikrodenetleyici:** STM32F303RE (Nucleo kartı)
- **İletişim Protokolü:** UART (9600 baud, 8 veri biti, parite yok, 1 stop biti)
- **Giriş:** UART terminalinden kullanıcı metni
- **Çıkış:** PB0 pinine bağlı LED ile görsel Mors çıktısı
- **Geliştirme Ortamı:** STM32CubeIDE, C dili

## 🎯 Hedefler

- UART tabanlı seri haberleşmeyi öğrenmek
- Dijital çıkışları (GPIO) kullanarak LED kontrolü yapmak
- Mors alfabesi zamanlamasını doğru biçimde senkronize etmek

## 🚀 Genişletilebilirlik

- Buzzer ile sesli çıktı ekleme
- Paralel LED desteği ile daha zengin gösterim
- EEPROM veya SD kart kullanarak mesaj kaydı
- Mors çıktısıyla birlikte düz metni göstermek için LCD/OLED ekran kullanımı
