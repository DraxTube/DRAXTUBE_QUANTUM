# 🎬 DRAXTUBE QUANTUM v1.0 (Quantum Engine)

**DraxTube Quantum** è un server locale in Python progettato per trasformare la tua PS Vita in una stazione di download definitiva. Permette di cercare film e serie TV sul PC e inviarli direttamente alla console tramite Wi-Fi, pronti per essere guardati offline.

---

## 🛠️ Requisiti Obbligatori (PS VITA)

Per far sì che la PS Vita accetti il download del file `.mp4`, è **fondamentale** installare il seguente plugin:

* **Download Enabler**: Consente al browser della PS Vita di scaricare file da qualsiasi link.
* **Come installarlo**: Usa **AutoPlugin II**, cerca "Download Enabler" nella lista dei plugin Vita e installalo. Riavvia la console dopo l'installazione.

---

## 💻 Requisiti Tecnici (PC)

Il programma necessita dei seguenti componenti nella cartella principale:

1.  **Python 3.x** installato.
2.  **yt-dlp.exe**: L'eseguibile per il download dei flussi video.
3.  **ffmpeg.exe**: Necessario per convertire i video nel formato corretto per la Vita.
4.  **Librerie Python**:
    ```bash
    pip install flask requests beautifulsoup4
    ```

---

## 🚀 Caratteristiche Principali

* **Anti-Loop System**: Impedisce al processo di riavviarsi se il browser della Vita ricarica la pagina.
* **Smart Conversion**: Converte automaticamente in `.mp4` con il `moov atom` all'inizio del file (ottimizzato per lo streaming locale).
* **Auto-IP Detection**: Mostra l'indirizzo corretto da digitare sulla PS Vita appena avviato.
* **Interfaccia con Copertine**: Visualizzazione fluida delle locandine dei film direttamente sul browser della console.

---

## 📖 Istruzioni d'uso

1.  Metti `asf.py`, `yt-dlp.exe` e `ffmpeg.exe` nella stessa cartella.
2.  Avvia lo script: `python asf.py`.
3.  Nella console apparirà un messaggio come: `URL PS VITA: http://192.168.x.x:5000`.
4.  Apri il **Browser della PS Vita** e digita quell'indirizzo.
5.  Cerca un film, scegli un Mirror e attendi che il PC completi l'elaborazione.
6.  Quando compare il tasto verde **"SCARICA SU VITA"**, premilo per iniziare il download nella memoria della console.

---

## 👤 Credits & Supporto

Sviluppato da **DraxTube**. Se il progetto ti piace, seguimi sui miei canali:

* **GitHub**: [DraxTube Profile](https://github.com/DraxTube)
* **YouTube**: [@DraxTube01](https://www.youtube.com/@DraxTube01)

 ---

## ⚠️ Note legali
Questo programma è stato creato a scopo puramente illustrativo e per uso personale. L'autore non si assume alcuna responsabilità per l'uso improprio del software.

---
**DraxTube - Rendiamo la PS Vita immortale!**
