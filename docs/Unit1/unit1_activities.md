# Unit 1 / Activities

## Activity 1: get the data!

* In Box ```/ DCI102-F19-data / unit-1-text``` there is a zip file ```TesseractOCR```. 
* **Do not search then click on this folder!** It will unzip, expand, and take up a lot of space. 
* Instead, download this file to your Desktop, then unzip/decompress to view the contents. 

## Activity 2
To search the RTP from your computer, open it in your text editor. 

In Sublime/Atom:
* File > Open > select TesseractOCR. If you select the file, then press open, rather than double clicking and entering the folder, you should see all the folders in the left pane. 
* Use ```Cmd + F``` to search or the Find menu item. If you select a folder name or specific file on the left, you can search on just that folder/file.

## Activity 3: RTP Scavenger Hunt

1. Form teams of three. Each team is responsible for 3-4 topics. One topic can be your choice.
2. In Box, create a Boxnote for your team. List your team name, participants, and your topics as headings. 
3. For each topic, find the relevant RTP issue in BOTH the Digital Archive and the data set on your computer. 
4. Paste in a URL from the Digital Archive AND the filename for the text file in your data set. 
5. As you go along, note your observations/frustrations about the data set at the bottom of the Box note. What was hard to find? Why? Where are the inconsistencies? How's the OCR? 

### Topics:
* Coeducation
* Integration 
* Fraternity Renaissance
* Sit in (Vietnam) 
* Martin Luther King Jr.
* Y2K
* “The move” of Leyburn Library
* WW1 or WW2
* Ambulance Corps 
* Hurricane Camille 
* Virginia Horse Center
* Prohibition 
* Lee Chapel 1920s controversy or 1960s renovation
* Mock Con 
* Buildings! Burning of Tucker, Lenfest/Wilson, Elrod Commons, 
* Cold War
* Best Fancy Dress theme:
* Best Advertisement:
* Best Greek story:
* Best sports story: 
* Your choice: 


## Activity 4: Text Analysis Tools
In order to find the right text analysis tool for your research question, let's sample several different options. You can find more info about options on the [Methodology page](unit1_methodology.md).

In your assigned groups, work together to install your piece of software, review the documentation, and test out how it works. Often, you can find a "Quickstart" guide or tutorial with the basic instructions you will need to get going. 

* [AntConc](http://www.laurenceanthony.net/software/antconc/) (team 1)
* [Topic Modeling Tool](https://senderle.github.io/topic-modeling-tool/documentation/2017/01/06/quickstart.html) (team 2)
* [Lexos](http://lexos.wheatoncollege.edu/) (team 3)
* [Voyant](http://voyant-tools.org/) (team 4)

As a group, consider the following questions. Be prepared to share with the class.  

* Who created this tool?
* What documentation is available?
* How do you input/output data? 
* What visualization options are available? 
* What types of questions does this tool enable?



## Activity 5: Documentation
Let's practice writing documentation for a technical task.

* Create a Box Note in ```Unit1_Text/Activity4``` with your name + number.
* Compose 5-7 steps to complete the assigned task. 
* Remember the best practices we discussed. Include screenshots and links when appropriate.
* Then, compare notes with another student with your number. 
	* How did you do things differently? Different doesn't mean bad/good. Discuss motivations. 
* Finally, compare notes with a student with another number. Pretend you have never done this before! Can you follow their steps? What are they missing? What was helpful?


1. Install Wordpress from CPanel
2. Write a basic HTML page
3. Create a menu in Wordpress

# Data Assessment 
Record the answers to all questions in a text file or Word doc. You will turn in Parts 1 + 2 with the rest of Unit 1 assignments.  

## Part 1 - File structure + command line
Using your new found command line skills, let's learn more about the RTP data. 

* Use `pwd` `cd` and `ls` to navigate through the `TesseractOCR` folder. 
	* What is the basic file structure of the data set as you have received it? What about the file names? What are the patterns? Where (or when) do the patterns change? 
	* What is the granularity (of the text files? Does each file contain one page? Issue? Reel? Volume? Year? 
* Use `cat` to read a file. Find the manual for `cat`. What else can you do with this command?
* What happens when you type `ls *.2.txt`?
* Can you figure out how to list all the file names in `TesseractOCR` and send them to a text file?
* Last step: type `history` and paste your command history into the text file. 

## Part 2 - RegEx 
Using your new found regex skills, let's start cleaning up some RTP data.

* In Sublime, open the TesseractOCR folder so the left pane contains the file structure. You can do this by clicking File > Open, select the TesseractOCR folder, then click Open.
* Look around for repetitive problems in the OCR. List 5 problems you find more than once. 
* Start testing regular expressions on those problems. List your successful tests. You can use regex101.com if it helps. 
* Answer the following: 
	* How would you find large spaces between words?
	* Are there frequent misspellings of common words? \(Ring-tum, Rockbridge, Washington for instance\).

## Part 3 - Lexos
With your data subset, start exploring Lexos. Use the documentation often!
* What looks the most helpful on the `Prepare > Scrub` menu?
* What are lemmas?
* What is a document term matrix?
* Which visualization is most useful?
* What is interesting in the `Analyze` menu? Why?


## Part 4 - Next steps
* What are the biggest problems with the data set?
* Which problems can you solve?
* Based on your proposed research question, what are your priorities for OCR cleanup? 
* What's going in your subset of data? 


## Bonus round - script reading
Box also contains the folder `/tesseractscript` with the original scripts used to create the OCRed text files. The `tesseract_process.sh` script was written by Professor Sara Sprenkle in 2014 in order to create a data set for another DH course.

Even if you don't understand everything that's happening in the script, there is one important detail that affects your data. Can you find it?