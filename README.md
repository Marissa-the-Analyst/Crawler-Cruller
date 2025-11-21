# Crawler-Cruller
![dash example](https://github.com/user-attachments/assets/f0ae3fed-c10e-48bb-bb7e-ef44dd9b67e4)

Hideyuki Furuhasi’s 126-chapter manga series, My Hero Academia: Vigilantes is a charming tale and reframing of what it means to be a hero. Additionally, it bolsters local communities, details rehabilitation practices, and emphasizes relationships over whatever might necessarily be “right”. When the anime released earlier this year, I knew I had to address a burning question. Does the long-running joke of people mispronouncing our protagonist, Koichi’s, hero name, “The Crawler” as “The Cruller” have any actual standing? 

Was it just one witty person? Did normal average people do this? During a light re-read of the manga, I decided to answer these questions by recording every instance of where Koichi was referred to or addressed to by another person while he was doing hero duties.  

### View finished product ###
View the finished project [here](https://public.tableau.com/app/profile/marissa.nash/viz/CrullerorCrawler/Dashboard1)

### Programs Used ###
- Excel for Data collection 
- Tableau for Visualization 
- Krita for minor graphical adjustments 
- Figma to create some pretty pie charts (didn’t end up using them) 

### Scope of Work ###
**Deliverables** <br>
- A dataset with 162 observations of Crawler/Cruller
- A dashboard exploring the frequency observations and any insights gained

### Goals ###
I wanted to explore a dataset that I felt connected with. I also wanted to fully see how much I could do with just 4 attributes. I also just wanted to jump into creating a fully-fledged dashboard. Beyond my [Stroll to 2,800,000 project](https://github.com/Marissa-the-Analyst/Strollto2800000), most of my projects have been smaller scale or still works in process. 

### Data Collection ###
It was a challenge creating this dataset as it feels a little convoluted lol. The situations I recorded could not be instances where he was in his home, doing daily tasks, or talking to friends casually while not “performing a heroic duty”. It was truly separating the “hero” from the “person”. Additionally, near the end of the series, One for All thinks about The Crawler over and over again but never actually addresses him vocally? So, I didn’t record those either. There were also characters that just didnt seem to have names? So i had to group them into a bundle of civilians. 

### Key Viz Metrics ### 
- Narrative Storytelling
- Bar chart Frequency Viz over Manga Series
- Detailed Breakdown of overall Name percentage using bar charts and percentages 
- Audience analysis

### Visualization Designs ###
<img width="813" height="171" alt="image" src="https://github.com/user-attachments/assets/f06bceb1-3a5f-4b2f-8dce-5a73cfa1e618" /> <br>
This bar chart was inspired by Wendy Shijia‘s [115 Moments in Ink](https://public.tableau.com/app/profile/wendy.shijia/viz/MomentsinInk/Moments). I really enjoyed how she utilized a smaller chart, but it told so much detail about her activity over the time span. For my work here, I enjoyed visualizing the entire 126-chapter series. I also added the twist of color to visualize the staying power of both names. I also took the tip (from somewhere on Linkedin I believe) to add the y-axis label horizontally for easier stakeholder comprehension. <br>

<img width="605" height="444" alt="image" src="https://github.com/user-attachments/assets/bda3d0dc-67b1-4aab-adf5-ce01a000af2f" /> <br>
During my re-read and some preliminary pivot table experimenting in Excel, I came to realize that Koichi himself played a large part in this analysis. So much so, that his involvement could skew the overall results. I decided to explore this using a stacked horizontal bar chart inspired by Jackbox Party Pack’s Brackteering. <br>

<img width="602" height="309" alt="image" src="https://github.com/user-attachments/assets/8e973b11-b16c-406f-b5cb-2ee75f1bd13c" /> <br>
It plays on the notion that once you strip out the “other” category, which of the two big names holds the most relevance? And how much of those results are influenced by Koichi’s own self-proclamations? This really gave me full power to explore Tableau’s parameter actions, quick-table calculations, and adding reference lines. 

The parameter action helps narrow all of these different people into easier to navigate categories. The quick table calculations helped keep the percentages all equaling up to 100% and being easy to interpret.  

### Dash Design ###
This was my weakest area. I knew I wanted it to be a longer vertical scroll situation with narrative elements to guide the user. I also knew generally which visual elements I wanted to make. I even sketched it out on paper several times to feel like I had a good grasp on what I was trying to say. However, I heavily underestimated several parts of the design process. 

### Pie Chart Peril ###
Despite all the negatives about Pie Charts and Doughnut Charts, I wanted to use them because I saw how pretty they could be from Shreya Arya’s [Customized Donut Charts tutorial](https://public.tableau.com/app/profile/shreya.arya/viz/CustomisedDonutChartsMapLayersDemo/Demo) 🥺👉👈. Plus, I really liked the display of information that really informs the reader of what's going on in the pie chart, in the center of it. <br>


<img width="690" height="192" alt="image" src="https://github.com/user-attachments/assets/55f308c5-39ab-4d52-8f73-80844cbc73cd" /> <br>
The initial charts looked like this. I did succeed following the tutorial (resizing them to fit properly caused me the most grief). But I didn’t enjoy how they represented different metrics, and I felt like that would be confusing to stakeholders. I ended up creating them all on one sheet and using the custom shapes route instead. This resulted in: <br>

<img width="555" height="191" alt="image" src="https://github.com/user-attachments/assets/1aa21fed-4786-49fc-8d8a-89696ec91b1f" /> <br>

However, there were text alignment issues (because Koichi’s symbol is not a circle) and overall readability suffered. Additionally, you weren't able to easily infer what each picture represented. By using different shaped icons playing off of hyper realism and symbols, you were able to differentiate and notice any alignment issues less.  <br>

<img width="665" height="202" alt="image" src="https://github.com/user-attachments/assets/d3ea6c88-5ff2-44b7-bf3a-c748ad80a486" /> <br>
My friend, Lawrence (also a data analyst in training!), recommended adding labels underneath and increasing the font size on the numbers to increase readability. I think I'd go back and make their opacity a bit lower so that the text is very easy to read. Overall, I’m pretty happy with how these turned out. <br>


<img width="804" height="302" alt="image" src="https://github.com/user-attachments/assets/c4066fd1-b306-45f9-ae9c-7f3bedd0e43e" /> <br>
This one and the “Honorable mentions” section were pretty simple, but I think they provided valuable context to the overall narrative.  I am getting more and more familiar using custom shapes and displaying information easily to stakeholders and I look forward to mastering this method in the future. <br>

## Opportunities ##
This project featured a *TON* of learning. <br>


**Containers** <br>
I understood containers, but it wasn’t until I started attempting to resize things that I really understood containers. This dashboard container situation is unorderly, messy, and generally like a plate of spaghetti, all tangled up. 🍝 <br>


**Layout** <br>
While I sketched and had an idea of what I wanted the layout to look like. Once I had all of the pieces, it was difficult to put it together in a way that flowed smoothly. There’s a big white space here: <br>

<img width="620" height="552" alt="image" src="https://github.com/user-attachments/assets/42695fe7-615a-47f7-be3e-bb1808e83dbb" /> <br>
That sticks out like a sore spot. I have a few ideas of what could’ve gone there but breaking up the text, the pictures, and the analysis was tough. <br>  


**Flow-wise** <br>


<img width="570" height="466" alt="image" src="https://github.com/user-attachments/assets/27cc9598-c1c3-4915-82ce-34980a825e55" /> <br>
This area flows well but could be a completely different dashboard if I didn’t know any better. I think a few decorative blue and red accents would’ve gone a long way in making it seem like a cohesive dashboard. <br>


**The danger of categorizing other or audience types w/o specifying who they were** <br>
I would’ve liked a way to specify who was in each group on civilian, hero, friend, villain. I calculated those categories using a mundane calculated field IF statement instead of having it directly in the dataset. Next time it could’ve been cool if you clicked on the group; you’d get a little pop up saying who made up the group and how many times they said the selected name.  <br>


As far as saying “other” for the many different things Koichi was called, I think for the overall data story, it helped keep the focus on Crawler Cruller, but for the “I want to see every detail available to me” it hurt by hiding it all away in a vague column. A drill down here could've also been helpful.  <br>


**Finally, WIP and Resource saving** <br>
I had a lot of help from various tutorials, videos, and guides on the internet, and I am disappointed I didn’t take care to save more of those. I got caught up in the rush of trying to complete this one and work on my other projects that I didn’t collect and save those resources that I know I will seek out later. Even saving the pretty donut charts I made (even if i didnt use them) would have been valuable to say “hey I did do this, and this is why I picked a different route”. Next time I will take more care for sure. <br>


### Relection ###
This project had a lot of emphasis on container importance, dashboard layout and flow, narrative storytelling, and optimizing the project process from start to finish. I really think this one tested my abilities and I’m proud to say that I’m getting better at Tableau with every new undertaking. I think parameters and parameter actions really clicked here, and I understand more about the importance of a dashboard layout. <br>
I can’t wait to see what I will do next! 



