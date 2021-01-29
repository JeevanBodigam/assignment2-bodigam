# assignment2-bodigam
# Jeevan Bodigam
###### My favourite food is Hyderabadi Chicken Biryani

The aroma of cooking Biryani wafting from the kitchen is enough to make you drool. A melodious union of rice, **spices** and **meat**, this lip smacking dish is rich and packed with calories. Usually cooked in ghee, and sometimes with nuts and raisins thrown in good measure, Biryani is a delicious combination of all things wonderful. **Each region has its own unique method of preparing this lovely dish**. A burst of flavours on your tongue, Biryani is extremely versatile, but always delicious. **Every plate will surprise you**.

----

## How to create a repository on github
1. Go to https://github.com
2. 2 ways to create a repo [See Here](/images/createRepo.PNG)
    1. Click on new button on the home screen
    2. Click on the + icon on top right and select New Repository
3. Give a valid [name](/images/nameImage.PNG) for your repo
4. Make your public or private as per your requirement
5. Initialize your repo with readme or .gitognore or license.[See Here](/images/markdown.PNG)
6. Click on [Create Repository](/images/createbutton.PNG)

* Required Items
    * An account on <https://github.com>
    * Check Internet Connectivity
    * Good name for your Repo
        * Should describe your project
        * No fancy Names

----

## Best Places to Visit:
The table below shows the list of cities that one can travel in US.This table also provides the No of hours one can spend to complete the city tour and the approximate amount one should spend during the travel in that city.

|Location | Number of Hours | Amount |
|:-------:|:---------------:|:------:|
| [New York](/images/ny.jpg) |  8 | 500 $ |
| [Las Vegas](/images/lv.jpg) | 7 | 350 $ |
| [San Fransisco](/images/sanfran.jpg)| 5 | 400 $ |
| [Los Angeles](/images/la.jpg) | 10 | 700 $ |
| [Missouri](/images/missouri.jpg) | 5 | 250 $ |

---

## Pithy Quotes
> Life is what happens when you're busy making other plans. 

\- *John Lennon*

> Whoever is happy will make others happy too.

\- *Anne Frank*

> You will face many defeats in life, but never let yourself be defeated. 

\- *Maya Angelou*

---

## Introduction to Unix Shell 

> In Unix, the shell is a program that interprets commands and acts as an intermediary between the user and the inner workings of the operating system. 
> A shell hides the details of the underlying operating system and manages the technical details of the operating system kernel interface, which is the lowest-level, or "inner-most" component of most operating systems.

**Source:**
1. <https://en.wikipedia.org/wiki/Unix_shell>
2. <https://kb.iu.edu/d/agvf>

```
# sendEmail Function - mail & exit.
START=$(date +%s)
sendEmail() {
	scripttime=0;
	END=$(date +%s)
	DIFF=$(( $END - $START ))
	if [ $DIFF -le 60 ]; then
		scripttime="$DIFF seconds.";
	else
		DIFF=$(( $DIFF / 60 ))
		scripttime="$DIFF minutes.";
	fi;
	content="$content. Exec Time: $scripttime"
	echo $content | mail -s "$subject" $email_list
	exit;
}
# sendEmail Function - end.

```

Ref:  <https://kedar.nitty-witty.com/blog/10-useful-shell-script-code-snippets-linux>


Look what I got [My Profile](https://github.com/JeevanBodigam/assignment2-bodigam/blob/main/AboutMe.md)
