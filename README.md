# I4G-cybersecurity-
## Objectives
Use a hashing program to verify the integrity of data.
## Background / Scenario
It is important to understand when data has been corrupted or it has been tampered with. A hashing program
can be used to verify if data has changed, or if it has remained the same. A hashing program performs a hash
function on data or a file, which returns a (usually much shorter) value. There are many different hash
functions, some very simple and some very complex. When the same hash is performed on the same data,
the value that is returned is always the same. If any change is performed on the data, the hash value returned
will be different.
### Required Resources
• PC with Internet access
#### Step 1: Create a Text file
a. Search your computer for the Notepad program and open it.

b. Type some text in the program

![HASH_ONE](https://user-images.githubusercontent.com/118770973/235687756-25655795-86ed-4bfc-a98d-fd6efae09399.png)

c. Choose File > Save.


d. Navigate to Desktop.

e. Type Hash in the File name: field, and click Save

#### Step 2: Install HashCalc

a. Open a web browser and navigate to http://www.slavasoft.com/download.htm.

b. Click Download in the HashCalc 2.02 row.

c. Open the hashcalc.zip file and run the setup.exe file inside.

![hashcalc setup](https://user-images.githubusercontent.com/118770973/235692672-a9b549c9-5afe-4e3d-bb46-c81999b18c39.png)

e. Click Finish on the last screen, and close the README file if it opened. You may read the file if you wish.

f. HashCalc is now installed and running.

#### Step 3: Calculate a hash of the Hash.txt file

a. Set the following items in HashCalc:

1) Data Format: File.

2) Data: Click the … button next to the Data field, navigate to the Desktop and choose the Hash.txt file.

3) Uncheck HMAC.

4) Uncheck all hash types except MD5.

b. Click the Calculate button.

![Hash calculator](https://user-images.githubusercontent.com/118770973/235695036-2c063650-868d-4ffe-9f9b-f92cf0261300.png)

check the value next to MD5

#### Step 4: Make a change to the Hash.txt file

a. Navigate to the Desktop and open the Hash.txt file.

b. Make a minor change to the text, such as deleting a letter, or adding a space or period.

c. Click File > Save, and close Notepad.

![hash file updated](https://user-images.githubusercontent.com/118770973/235696705-29bfb81d-7b9f-4d6b-8d62-089198c8dcbe.png)

#### Step 5: Calculate a new hash of the Hash.txt file

a. Click the Calculate button in HashCalc again.

What is the value next to MD5?

![hash updated calculation](https://user-images.githubusercontent.com/118770973/235698481-d87a6da8-c9db-4f88-ad21-95a93ed6803d.png)

Is the value different from the value recorded in Step 3? YES!



b. Place a check mark next to all of the hash types.

c. Click Calculate.

d. Notice that many of the hash types create a hash of a different length

![hash calc with all ](https://user-images.githubusercontent.com/118770973/235701027-3cc2cc2e-8caa-4911-b434-6d4655f6c13e.png)




