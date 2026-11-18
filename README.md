# Private SOFT BrainWords v1.0 new 

## Find Lost Bitcoin phrases (Brainwallet GPU)
Search phrases on the fastest program in the world<br>
22,052 passphrases were found, an estimated 5,000 passphrases are lost<br>
They were found on a processor with a maximum speed of 100,000 passphrases per second.<br>
Speed RTX 4090 = 360,000,000 passphrases/sec. It's 3600 times faster.<br>
The fact that one 4090 GPU runs in 24 hours is a legendary CPU program brainflayer in 10 years.<br>

**To buy the program, telegram** https://t.me/cuda8

| GPU card | --bits | Speed |
|----------|----|-------------|
| 5090     | 24	| 540 Mkeys/s |
| 4090     | 24	| 360 Mkeys/s |
| A100     | 24 | 180 Mkeys/s |
| A6000    | 24 | 180 Mkeys/s |
| 3090     | 24 | 180 Mkeys/s |
| 3080 Ti  | 24 | 170 Mkeys/s |
| 3080     | 24 | 150 Mkeys/s |
| 3070 Ti  | 24 | 120 Mkeys/s |
| 3070     | 24 | 110 Mkeys/s |
| 3060     | 24 | 70 Mkeys/s |
| 2080 S   | 24 | 70 Mkeys/s |
| 2070     | 24 | 50 Mkeys/s |

* 1 MKey = 1000000 passwords or words per sec.

How to search for old lost phrases:<br>

Mode 0 (special)<br>
It takes a line from the first file and processes all lines from the second file against it.<br>
You can add suffixes, dates of birth, numbers, etc. No more than 50 million lines in dic.txt<br>
The program stops once the additions are complete; there is a toolbar.<br>

```BrainWords.exe -a addresses.txt -words dic.txt -words2 dic2.txt -suffix 0 -bits 24```

<hr>
Mode 1<br>
Generating all string with increment<br>
abc -> abcabc -> abcabcabcabc<br>

```BrainWords.exe -a addresses.txt -words dic.txt -suffix 0 -bits 24```

<hr>
Mode 2<br>
Generating all string with increment<br>
abc -> abc abc -> abc abc abc abc...<br>

```BrainWords.exe -a addresses.txt -words dic.txt -suffix 0 -bits 24 -mode 2```

<hr>
Mode 3<br>
Generating all string with increment<br>
abc -> Abcabc -> Abcabcabcabc...<br>

```BrainWords.exe -a addresses.txt -words dic.txt -suffix 0 -bits 24 -mode 3```

<hr>
Mode 4<br>
Generating all string with increment<br>
abc -> Abc abc -> Abc abc abc abc...<br>

```BrainWords.exe -a addresses.txt -words dic.txt -suffix 0 -bits 24 -mode 4```

<hr>
Mode 5<br>
Generating all string with increment<br>
abc -> AbcAbc -> AbcAbcAbcAbc...<br>

```BrainWords.exe -a addresses.txt -words dic.txt -suffix 0 -bits 24 -mode 5```

<hr>
Mode 6<br>
Generating all string with increment<br>
abc -> Abc Abc -> Abc Abc Abc Abc...<br>

```BrainWords.exe -a addresses.txt -words dic.txt -suffix 0 -bits 24 -mode 6```

<hr><hr>

**You can add a prefix (a fixed part at the beginning of the generated output)** <br>
Generating all string with increment<br>
abc -> Theabcabc -> Theabcabcabcabc<br>
```BrainWords.exe -a addresses.txt -root The -words dic.txt -suffix 0 -bits 24```

With a space after the prefix<br>
Generating all string with increment<br>
abc -> The abcabc -> The abcabcabcabc<br>
```BrainWords.exe -a addresses.txt -root "The " -words dic.txt -suffix 0 -bits 24```

With a space after the prefix<br>
Generating all string with increment<br>
abc -> The abc abc -> The abc abc abc abc<br>
```BrainWords.exe -a addresses.txt -root "The " -words dic.txt -suffix 0 -bits 24 -mode 2```

<hr><hr>
**Reading phrases from a file; long lines are supported.**

```BrainWords.exe -a addresses.txt -inputPhrase phrases.txt -bits 8```

Reading phrases from an external generator (slow speed)

```py gen.py | BrainWords.exe -a addresses.txt -inputIn -bits 8```

**Linux The same commands**

```chmod +x BrainWords```<br>
```./BrainWords -a addresses.txt -words dic.txt -suffix 0 -bits 24```


### Frequently asked Questions

**How do I search alphabetically?**
<br><br>
Add symbols, characters, etc., to the dic.txt file, each on a new line.
<hr>

What is the maximum length of a phrase?<br>
Which languages ​​are supported?
<br><br>
Supports up to 240 characters.<br>
Includes all languages, logograms (hieroglyphs), Cyrillic script, etc.<br>
Some languages, such as Japanese and Spanish, may present issues with longer phrases.<br>
Be sure to test your specific language.
<hr>

**How to buy the program?**
<br><br>
https://t.me/cuda8
<hr>

**Why did the program freeze at startup?**
<br><br>
She didn't hang up! Program start 3090 --bits 24 (10 min.)<br>
The program creates tables and downloads to the device<br>
One card requires 4GB or more of RAM to work.<br>
The consumption depends on the size of the table (--bits) and the size of the address file.
<hr>

**What address formats can be uploaded?**
<br><br>
BTC bc.., 3.., 1.., in a text file from a new line<br>
<hr>

**How to continue searching after stopping the program?**
<br><br>
The program saves the position in fileStatus.txt<br>
You can start from any position by specifying ```-suffix 1234567```<br>
For convenience, the file contains ready-to-use commands to continue.
<hr>

**How to start with long 9 characters or words?**
<br><br>
Count the number of characters in the alphabet and choose the one you need.<br>
Example 9 characters (alphabet 64 characters or 64 words)<br>
64 * 64 * 64 * 64 * 64 * 64 * 64 * 64 = 281474976710656<br>
Use ```-suffix 281474976710656```<br>
<hr>

**Explain what we are looking for?** <br>
**How it works? What's this?**
<br><br>
Here is a good example of work for you.<br>
Enter passphrase: fhqyqzhao123 pay attention to the address 1MVFUmYLKmLyC1m3WfyHkEJTZfoHjwDeXE<br>
The difference is that instead of requests to the blockchain.<br>
The program checks against the database of addresses with a positive balance.
<hr>

**What is a brain wallet?**
<br><br>
These are passwords or phrases converted to sha256; the output is a private key to the address.<br>
At the address, people stored coins there, a passphrase in their heads.<br>
This method was used 10-15 years ago. At that time, coins were worth almost nothing.<br>
Passwords were lost and forgotten. Do you remember your password 12 years ago? Are you sure?<br>
One character, dot or register is wrong and the entire wallet is lost. There is no restore button.<br>
Look for more information about brain wallet on the Internet.
See hire generation [https://brainwalletx.github.io](https://brainwalletx.github.io)
<hr>

**What does Brain Wallet look like?**
<br><br>
Were there any finds at all?
<br><br>
Here is a white list of passwords, phrases, balances, study<br>
https://privatekeyfinder.io/brainwallet/bitcoin/<br>
FOUNDS Download https://github.com/kupridis/BrainWords/blob/main/Brainwallet_Found.txt
<hr>

**Multigpu program?**
<br><br>
The program is NOT multigpu. For each card, indicate your id<br>
-d 0 or -d 1 ... -d 11<br>
<hr>

**Why does the program use a lot of RAM?**
<br><br>
The program creates the necessary tables and stores them in memory -bits 24 = 4.6 GB RAM.<br>
RAM is also used to store the address database and RIPEMD-160 hashes.
<hr>

**Unable to launch using the BTC history database.**<br>
**The database contains only 1... P2PKH and P2PKH_UNCOMPRESSED addresses.**

To fit this database onto a 24 GB card, specify `-bits 8` or `-bits 4`<br>
The processing speed will be lower, but the program will be able to run using the history data.<br>
There are no issues with 32 GB cards.
<hr>

**Does the program require an internet connection?**
<br><br>
No, the program is looking for the key offline.
<hr>

**The program is sold with source code?**
<br><br>
Yes, the program is sold with original source code v1.0 and instructions<br>
For linux Makefile, for Win VS2019 files.
<hr>

**How to compile a program?**
<br><br>
ubuntu 20.04 CUDA 11.7 (for RTX 4090 CUDA 13.3)<br>
Run: ```make```

vast.ai<br>
Template: cuda:13.3.0-devel-ubuntu20.04<br>

Image: nvidia/cuda:13.3.0-devel-ubuntu20.04<br>

Image CUDA version:<br>
Incompatible images hidden<br>
Launch Type: jupyter<br>

Windows use VS2022 + install CUDA 13.3
<hr>

**Unable to load a dictionary containing 2 billion lines.**

The program loads file lines into high-speed memory, which has a limit of 50 million lines.
<hr>

**In what modes is the program looking for?**
<br><br>
She is looking for everyone at once.<br>
Addresses 1 (uncompressed + compressed), addresses 3... and bc...
<hr>

**What arguments are there in the program?**
<br><br>

```-suffix``` Number o combination to start from ```-suffix 0```<br>
```-d``` number of the required GPU ```-d 0``` or ```-d 1``` ... ```-d 11```
```-words``` file.txt in which letters or words are on new lines<br>
```-words2``` file2.txt in which letters or words are on new lines<br>
```-mode``` num Capitalization and word-spacing modes<br>
```-o``` File for saving the result (default is FOUND.txt)<br>
```-bits``` Number of bits to generate table 8, 16, 20, 24<br>
```-fstatus``` File name status (default fileStatus.txt)<br>
```-a``` file list of addresses of BTC in a text file from a new line<br>
```-inputPhrase``` Filename for reading phrases from a file<br>
```-inputIn``` Receive a stream of phrases from an external generator<br>
```-iteration``` Number of iterations SHA256<br>
```-root``` text Fixed left part in generation ```-root 1234``` or ```-root " 1234 1234"``` with space<br>
```-b``` Number of GPU blocks (default set automatically)<br>
```-t``` Number of GPU cores (default set automatically)<br>
<hr>
