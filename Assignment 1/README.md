Given the prompt of the assignment, I began by planning the way in which I imagine my website to look like. I did so by sketching a rough plan of what each page on my website is going to look like forming a basic wireframe. Later on I chose the color pallet, and made basic plans regarding the amount of text and images I wanted to have on my website. Attached below is a copy of my initial wireframe:
5
​
6
<img width="1160" alt="Screen Shot 2022-09-26 at 5 04 29 PM" src="https://user-images.githubusercontent.com/98512511/192283966-44ee77fc-eda1-442c-a3d8-6fb9c6042a5c.png">
7
​
8
#### Planning:
9
1. Have the color pallet be black with vibrant peach and purple colors.
10
2. Have the home page be simple with large text to attarct the users.
11
3. Make the home page interactive to attract the users to watch the video.
12
4. Avoid extensive text so as to not bore the user, make the website self explanatory.
13
5. Instead of having the website shift to different pages, let it be one whole page wherein the user can scroll through it.
14
6. Allow the buttons to take the user through the website, but also ensure they are able to scroll smoothly.
15
7. Make the team members section interactive so that the user can reach out to the members. 
16
8. Be sure to include the portfolio, menu, and about us tabs. 
17
​
18
#### Possible Difficulties:
19
As I am not very familiar with html yet I believe that I might face difficulties in navigating my way through the different elements such as link, div , and header. I also believe that I might encounter difficulties in terms positioning items in the exact spot I want them to be in, especially since there a range of position commands that use different units of measurement. With that said, YouTube tutorials, as well as the short videos we watched in class can always be a great source for me to refer to as I work through this assignment.
20
​
21
​
22
As for the next tricky part I expect to face in creating this project, I do not think I have gotten my mind well rounded around the process of publishing my website live for any online users to access it, especially since this process could be done in different ways, and there is no specific method that is guaranteed to be the best fit for the program I am using and for my computer. 
23
​
24
#### Process:
25
After finalizing my general idea and listing the steps to my p0lan as well the possible difficulties that I expect to encounter I began working on my assignment. At first it was quite difficult to get started especially since I was not very well aware of the initial opening statements of code that I had to include in my html page. To get through this difficulty and to familiarize myself further with the program, I started with simple lines of code, that performed simple actions like writing the word "Hello" on the screen in different sizes, and associating it to different links. Once I was through that, using the program become somewhat easier and so I went through my intial plan in terms of including the texts and all the elements that were meant to appear on my web page. 
26
​
27
After finishing this process, my website doubtlessly appeared very dull, and that is when I began experimenting with CSS. While very interesting to use, coding to style my website was surprisingly harder than I expected, that was mostly due to the fact that once I changed a certain aspect of my code, it somehow hugely impacted the appearance of my website. I dealt with this issue by using the inspect option on Google Chrome to help me know wehat exactly was being controlled by every lne of code. Utilizing this trick helped me a lot and made styling my website so much easier. 
28
​
29
​
30
One issue I was not expecting to face but did face was having to repeatedly write the same line of code for different parts of the website that required similar actions. I resolved this issue by utilizing classses. In doing so I did not have to repeat the commands, but rather just call the class and have it perform the neccessary actions. Below is an example of where classes came in handy for me:
31
​
32
```javascript 
33
<div class="TeamMember">
34
          <div id="Members"></div>
35
          <img src="IMG_0587 2.JPG" alt="DHABIA" width="200" height="250">
36
          <h2>Dhabia Alhosani</h2>
37
          <p>Junior Student at NYUAD</p>
38
          <button class="MainButton"><a href="https://www.instagram.com/dhabialhosani/">Learn More</a></button>
39
        </div>
40
        <div class="TeamMember">
41
          <div id="Members"></div>
42
          <img src="IMG_0488.JPG" alt="LUKE" width="200" height="250">
43
          <h2>Luke Nguyen</h2>
44
          <p>Sophomore Student at NYUAD</p>
45
        <button class="MainButton"><a href="https://www.facebook.com/locnguyen20">Learn More</a></button>
46
        </div>
47
```
48
Above the class TeamMemeber called the actions from the CSS file for each specific team member. Through the use of classes I did not have to repeatedly list how I wanted the team members section to be styled. I also ensured that they all were perfectly aligned and looked very similar. 
49
​
50
Following that my plan of progress was mainly revolving around running the website, seeing how it looks, and trying to update the style accordingly. This process was a bit difficult as I had to judge which styles and color coordinations looked the best together. 
51
​
52
Once I was satisifed with the way my website looked I did some user testings with some of my friends to get their insights on what they think was well done in my website and what they think could be improved. 
53
​
54
While most of my friends agreed that the website was fairly well constructed, one of them pointed out that my website was not the smoothes when it came to scrolling through the page. After researching I was able to resolve this issue by including the following line of code: 
55
​``` javascript
html
{
   scroll-behavior: smooth;
}
```

57
Finally I was done with constructing my website and the final result was formed as seen below: 


#### What I Learnt:
I learnt a lot through this assignment but one thing that was truly new to me was the importance of style and the difference small elements could make to the effectivity and the appearance of my website. Creating this website, while challenging led me to become more creative and made me more comfortable and familiar with coding using html and css. One thing that I have not yet experimented with and I look forward to using is java script, as we were only starting to learn about it, I was unable to incorprate it into my code in a working manner. However, I look forward to furthe rdeveloping my skills in javascript. 
58
​
59
​
60
​
