Teamlogs – transcription and analysis of audio and video files

### **Teamlogs 1.51 — Improved file loading,** 28.06.2023

* we have improved the file download algorithm – fixed download errors with a slow or unstable Internet connection, accelerated file downloads, and also made it possible to resume file downloads when the connection is lost,
* added the ability to delete an audio file without deleting the entire transcript,
* added analytics module for organizations,
* minor changes have been made and errors in the work of the transcript editor have been corrected

### **Teamlogs 1.5 — Improved English, autospickers, new file downloads and transcript updates,** 04.05.2023

1. **English, new recognition model** <br>
We have updated the English language recognition model, now English speech is recognized much better. <br>
Processing time of an hour-long English-language recording is 7 minutes

2. **Auto-detection of speakers** <br>
When uploading recordings, you can now choose to automatically determine the number of speakers. <br>
But you can still set the number of speakers manually

3. **Accelerated file upload** <br>
We have improved the upload algorithm, now files are loaded much faster


4. <p style="margin-bottom: 3px"><strong>Transcript improvements:</strong></p>
   * the operation of the Enter key has been improved, now it hits a paragraph where the text input cursor is. <br>
   Enter – moves the text to the next line inside the replica, <br>
   Ctrl + Enter – divides the replica into two by cursor position, 
   * ability to merge adjacent replicas using Backspace at the beginning of the lower replica

### **Teamlogs 1.499 — Single account for organizations,** 24.03.2023

**Organizations** <br>
_We have added the ability to create a single billing account. Now you can:_

* create your own organization inside Teamlogs,
* invite users to the organization,
* assign administrators among users,
* pay for the processing of records from the general account of the organization,
* transfer processed records to participants within the organization

### **Teamlogs 1.4 — export to .xslx and transcript sharing,** 26.10.2022
* Added export to .xlsx. The transcript is exported in a tabular format, divided into replicas, speakers and timings
* Added the ability to share transcripts. Now you can open access to the transcript to another registered user. Just like in Google Docs
* Fixed errors when editing the text of replicas

### **Teamlogs 1.31,** 16.08.2022
* The model of dividing text into speakers has been completely updated. Now the speakers' replicas are shared without capturing unnecessary phrases from the next speaker
* Improved text quality thanks to the new speaker division
* Optimized file processing – records are processed much faster

### **Teamlogs 1.3,** 07.07.2022

_Big update – speaker editing, new punctuation and numerals placement model_

* Added speaker editing feature. Now you can change speakers for each replica, give speakers names, add and remove speakers
* The punctuation placement model has been updated, which we have trained on data from open sources: news, Wikipedia, subtitles of shows and blogs. Now the model places punctuation marks almost like a person, knows how to put paragraphs, hyphens, dashes and quotes
* The module for working with numerals has been updated. Fixed the problem when "one" was displayed as "1-n", etc., in general, the logic of working with ordinal numerals was redesigned

### **Teamlogs 1.22,** 24.06.2022

* Fixed problems with the appearance of spaces when editing the transcript
* The step of rewinding audio using hotkeys has been changed – now it is 0.5 seconds
* Improved the logic of highlighting words in the transcript when playing audio

### **Teamlogs 1.21 – Transcript 2.0,** 25.05.2022

_The transcript editing module has been completely redesigned:_
* transcript editing has become faster and more convenient,
* it is now possible to add, delete and share speaker cues,
* now on Enter you can repel a new paragraph inside the replica,
* copying from the browser works fine,
* added hotkeys "play audio", "stop" and others, a list of hotkeys at the top of the transcript widget,
* added the status of saving the transcript,
* temporarily removed emotions from the text

### **Teamlogs 1.11,** 05.05.2022

* added widget for automatic transcript summary,
* slightly updated transcript interface,
* added the ability to cancel an order in case of an error when switching from the file download to the payment page

### **Teamlogs 1.01,** 22.04.2022

* Added deletion of records <br>
  Now you can delete your transcripts from the service. The delete button is located in the list of entries and is active when the cursor hovers over the desired entry. The deletion function is only available in the desktop version of the service. <br>
  Deletion is possible for records with the status "Completed" and "Rejected". Records "In processing" cannot be deleted. <br>
  Important: after deleting the record, it is impossible to restore it

### **Teamlogs 1.0,** 14.04.2022

* added English language support,
* improved recognition of geographical names, names and brands,
* the payment system has been improved – now the minimum purchase is from 1 minute,
* redesigned record loading system: <br>
  added language selection function – Russian, English, <br>
  now the recording duration is checked when downloading and the missing minutes can be paid immediately from the download window.
* we started a (<a href="https://t.me/teamlogs" target="_blank">telegram channel</a>) and (<a href="https://vk.com/teamlogs" target="_blank">vkontakte</a>), be sure to subscribe. There you can also find a promo code for a discount.

### **v0.99,** 5.02.2022

* automated transcription of speech,
* punctuation,
* speaker diarization,
* highlighting keywords,
* analytics of non-verbal emotions,
* face recognition,
* listening to audio and editing the transcript, 
* export to *.docx and *.srt,
* supported languages: Russian
