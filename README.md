# Slack - UX Redesign
image one

## Overview
Slack is widely used in our school across a wide range of disciplines. In design classes, students post their work and receive peer feedback; In engineering classes, students discuss about their group projects. 

I have decided to redesign the mobile Slack’s Thread feature by 
* **making the interface more accessible**
* **adding one functionality**

in order to make browsing and searching more efficient.

## Research
I conducted user study by interviewing eight people. The distribution is shown as below.

* **Have you ever used Slack?**
image two
Among the six people who have used it, 
* **What is your familiarity with Slack?**
image three
* **What is your role when using Slack?**
image four
* **What class do you use it for?**
image five
Through user study, I find that people use mobile Slack Thread for **heavy text-based conversation** and **viewing pictures**. For either purpose, they reflect that there is some inconvenience. To facilitate users to browse through wordy conversation, I decide to change the **layout of Thread**; To help users find target pictures quickly, I decide to **create a shortcut**.

### Problem 1
<img src="https://github.com/Okrasee/DOne/blob/master/FAB.gif" align="right" width="200px"/>
<strong>Go to another screen to view all replies</strong> <br>
One of the teaching assistants pointed out that people have to click on the “+replies” and then enter into a new screen to read the complete list of replies. As he is obliged to read every thread, he felt doing so pretty annoying. Other Slack users among my interviewees had the same opinion. When I brought the issue to those two people who have not used Slack, they also claimed they would not want to check the replies. 

<br clear="right"/>

### Solution 
#### Expand to open a thread; Add button as cue for editing
**iteration 1** <br>
By clicking on a message, the user could expand a dropdown list of replies instead of entering into a whole new screen. The position of the message may be pushed up a bit to create enough space for the replies. The current message and its replies are marked grey to be differed from other messages.

image seven
image eight

What if there are 50 replies, for example? Then people would have to scroll a lot to get to the next message. Here are two solutions:

#### Solution 1. 
<img src="https://github.com/Okrasee/DOne/blob/master/FAB.gif" align="right" width="200px"/>
<strong>Make the thread scrollable while the message always stay on the screen. </strong> <br>
The user could click on the message to fold the replies at any time and get to the next message; or directly click on the next message if it appears on screen.
<br clear="right"/>

#### Solution 2. 
<img src="https://github.com/Okrasee/DOne/blob/master/FAB.gif" align="right" width="200px"/>
<strong>Display at most four replies and swipe left for the next few replies. </strong> <br>
I decided to pick this solution because the message always stay on the screen such that the user could fold the thread with a single click. Besides, internal scroll should be avoided according to the Material Design Guideline. 
<br clear="right"/>
<br clear="right"/>

<img src="https://github.com/Okrasee/DOne/blob/master/FAB.gif" align="right" width="200px"/>
<strong>iteration 2 </strong> <br>
Each reply could be edited/deleted by a <strong>long press</strong> on it. However, none of the Slack users I talked to know this because it is unintuitive. So I added a button to inform people that they could edit/delete their replies or mark others’ replies. Swiping (left/right to check other replies) is disabled to avoid mis-clicking on the button.
<br clear="right"/>

### Problem 2
#### Hard to find a picture posted long ago
When people need to refer to a picture posted long ago or they simply want to look back to that picture, they have to scroll through a lot of later information to find it.

#### Solution
<img src="https://github.com/Okrasee/DOne/blob/master/FAB.gif" align="right" width="200px"/>
<strong>Create a Gallery that stores all pictures </strong> <br>
Clicking on the button at the top right corner leads people to a gallery that stores images or videos. The images are divided into chucks sorted by the order of time. For instance, all images/videos from last month are grouped together.
<br clear="right"/>
<br clear="right"/>
<img src="https://github.com/Okrasee/DOne/blob/master/FAB.gif" align="right" width="200px"/>
<strong>Search by date</strong><br>
Nevertheless, if the user is trying to search for something posted 2 years ago, there is still a lot to scroll through. If the user remembers the rough date of the post, he/she could enter year and month into the search bar which helps him/her jump to that particular month.
<br clear="right"/>
<br clear="right"/>
&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/Okrasee/DOne/blob/master/FAB.gif" align="right" width="200px"/>
<strong>Filter by channel</strong><br>
Images from all channels are stored in the same gallery in case that the user forgets in which channel the image is posted. One could, however, select “this channel” if he/she clearly knows which channel the image is posted in. It helps narrow down the range and enables the user to find target more efficiently.
<br clear="right"/>
<br clear="right"/>

