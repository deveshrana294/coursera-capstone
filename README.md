![image](https://github.com/deveshrana294/coursera-capstone/assets/163284298/de7f0630-968c-4766-83e9-de5b1b539213)QR Generator App
This app can be used to transform any String Text to a QR. Anyone who will scan the QR would get the set string as the result. The QR that are saved can be accessed by other apps using ContentResolver. It could be deleted, or downloaded for local use from the HistoryActivity. Note that all the qr(s) generated are not saved by default if not clicked on the save button. If the user don't want the qr to be accessed by other apps and hence don't want to save the QR, they can opt to download. It will be downloaded as a png image file into the Downloads Folder which will be reflected in the Gallery.

Api
Documentation

We'll be using this api to generate and download QR for respective Text.

Used : https://api.qrserver.com/v1/create-qr-code/?size=`150x150`&format=`png`&data=`String Data`

Note- String Data could be anything like : url, text, upi id, etc.

Wireframes
