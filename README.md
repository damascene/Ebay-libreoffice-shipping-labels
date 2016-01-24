# Ebay-libreoffice-shipping-labels
Print shipping labels and standard CN22 form, from Ebay SalesHistory.csv file using the free software, Libreoffice

Currrent Version
================
Alpah 0.1 (development version for testing purposes)
Official Release will be named after more testing.


Features
===========
 - Import SalesHistory.csv file into Calc spread sheet and extract address data to be imported in a mail label document ready to print
 - Has the CN22 form with most of the data filled above the shipping address
 - Custom words for CN22 depending on Item number
 - Automatic Capitalization of reciver name
 - Automatic calculation of real quantity for lots (if you sell lots of 4, you will have 4 written on the custom declaration instead of 1)
 - All fit on A6 page

Known Bugs
==========
 - When a buyer order multiple items you will have to modify information by hand in SalesHistory.csv .
 - When a buyer has long address discription you will have to modify the page before printing to handle more words.


How to Use It
=============
1. Extract the files
2. Replace the SalesHistory.csv file with yours
3. open SalesHistory.ods and accept to update
4. open CN22-one.odt file and you are ready to print

Warrenty
========
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

License
========
GPL V.3

Owner
=====
Usama Akkad
