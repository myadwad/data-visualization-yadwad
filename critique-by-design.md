| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# A Critique and Redesign 

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: the visualization from MakeoverMonday

I selected a visualization originally published by the Center for Strategic and International Studies (CSIS) titled [_Terrorist Attacks and Plots in the United States by Perpetrator Orientation, 1994–2025_](https://makeovermonday.vercel.app/dataset/2025w45-terrorism-and-political-violence-in-the-usa).

<img width="525" height="440" alt="Screenshot 2026-09-17 at 7 45 27 PM" src="https://github.com/user-attachments/assets/0c31088b-434c-4561-bf4e-3345cec314f2" />

## Step two: the critique
_The comments below have been submitted in the Google form_
	
The data visualization is attempting to depict the change in terrorism and political violence plots categorized by perpetrator. The visualization utilized stacked bars to represent the different categories, and the color red immediately stands out to me. The legend identifies that terrorist attacks perpetrated by the right are consistently the most prevalent over time. The ‘Right’ is colorized as red, which in the United States is typically associated with right-leaning political parties or Republicans. However, the title of the viz is not clear that perpetrator orientation is associated with a political party. Nevertheless, I immediately made the assumption that ‘Right’ and red are associated with conservative or Republican perpetrators. However, the ‘Ethnonationalism’ category debunks the assumption around political orientation. I think the use of color for the other categories (Jihadist, Ethnonationalist, Other) worked well. 

It’s difficult to see where each new year begins and ends because the spacing between bars is very small and there is no distinctive space between the years. More generally, I think the designers can improve the data categorization to reflect the differences in politically-motivated violence. These discrepancies are especially important because the study’s meta data explains that some left-wing terrorist incidents were classified as ethnonationalist.  

The primary audience appears to be policymakers and I think the secondary audience is the general public. I think the data viz could be more effective for the policymaker audience. Currently, the color and categorization choices may be divisive. For example, a Republican policymaker may not be receptive to reading more about the data on right-wing political terrorist plots upon seeing the number of red bars. This presentation creates a negative impression of right-leaning politics. While the data may be accurate in representing the disproportionately higher number of right-leaning terrorist plots it fails to keep the right-leaning policymaker interested in the complete story. 

I will try to focus on three elements: The use of color for each category, Renaming the categories and the title, and the distribution of space. I am also excited to experiment with different visualization types to better display the change in data over time. I think it would be interesting to subverting the typical color of categories ie. right-leaning and left-leaning are different from red and blue. I also want to observe the data more closely to create a better title for the viz. 


## Step three: Sketch a solution

I opted for a redesign that more distinctly depicts the temporal change in number of terrorist attacks across categories. I did not feel it was important to capture the total number of attacks per year as shown in the original visualization. I believe that the messaging should be focused on the different classifications. 

<img width="525" height="640" alt="CSIS Terrorism Redesign-1" src="https://github.com/user-attachments/assets/de902dca-e256-42b1-9046-07802b493d42" />


## Step four: Test the solution

Questions to ask:

- Where do your eyes go first when you look at the visualization? 

- What are your thoughts on the color choices for the different categories particularly for right-leaning and left-leaning? 

- Are you interested in knowing the total number of terrorist attacks across all categories for each year? 

- Is there anything you would change or do differently?

Results: 


| Question | Person 1 | Person 2 | Person 3
|----------|-------------|-------------|---------|
|- Where do your eyes go first when you look at the visualization?  | The multiple colors on the graph but they are not overwhelming            | Similar to Person 1            |Similar to Person 1	 |
|- What are your thoughts on the color choices for the different categories particularly for right-leaning and left-leaning?           | Did not notice that right-leaning was not red or left-leaning was not blue.   |Did not think that right or left was associated with politics so the use of purple and yellow did not affect their pereception of the data. But why are the categories 'jihadist' and 'ethnonationalist' separate?  | The use of green for 'ethnonationalist' was accidentally confused with environmental; perhaps should change to a different color. 	     |
| - Are you interested in knowing the total number of terrorist attacks across all categories for each year?          | Yes            | Yes            |Yes, it would be nice to see the aggregated data over time.       |

General Feedback: 
* The title should be reworked to be shorter and use a subtitle to convey additional information; can also bold certain words in the title to emphasize their importance ie. "right" and "left".
* Label the axes
* Consider grouping some of the categories together to emphasize the right and left categories since that is the narrative you're conveying in the title. Add notes or captions to capture this change. 
* Play around with the colors and consider using more grey


Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

## Step five: build the solution

I selected a visualization originally published by the Center for Strategic and International Studies (CSIS) titled [_Terrorist Attacks and Plots in the United States by Perpetrator Orientation, 1994–2025_](https://makeovermonday.vercel.app/dataset/2025w45-terrorism-and-political-violence-in-the-usa). The visualization was part of a broader report on political violence trends in the United States titled [_Left-Wing Terrorism and Political Violence in the United States: What the Data Tells Us_](https://www.csis.org/analysis/left-wing-terrorism-and-political-violence-united-states-what-data-tells-us#h2-definitions). Pictured below: 

<img width="525" height="440" alt="Screenshot 2026-09-17 at 7 45 27 PM" src="https://github.com/user-attachments/assets/0c31088b-434c-4561-bf4e-3345cec314f2" />

### My Revisions Post-Feedback

After receiving feedback from my peers, I re-evaluated the relevance of all the data points and the specific categories. I took more time to read through the original CSIS report to better understand the authors' methodologies and classification of terrorist attacks into the different categories. I learned that the ethnonationalist attacks in 2025 would have typically fallen under left-wing attacks but the authors decided to categorize as ethnonationalist. However, for the purposes of simplifying the data, I moved those data points to the left wing category. I also combined the categories ethnonationalist, jihadist, and other together into a broader 'Other' category. The CSIS report focused primarily on the rise of left-wing political violence with little emphasis on the other categories, therefore, I felt it was okay to reduce the number of categories and focus on left-wing and right-wing terrorism. 

I altered my use of colors for the final design. In my draft sketch, I tried to subvert the traditional red and left political colors schemes but since I decided to reduce the categories to only three, I went back to using red and blue for right-wing and left-wing. I felt that this color association would be less polarizing with my new title that aimed to equally emphasize the trends on both sides of the political aisle. 

I contemplated omitting the 2025 data since it only included attacks up till July 2025. However, I decided against this because then it would downplay the rise in left-wing terrorism. However, I have included a note in the visualization indicating this as the original CSIS authors have also done so. Because of the incomplete 2025 data, I decided to retain the phrasing of my title "right-wing attacks remain high" because prior to 2025, there were 14 right-wing attacks in 2024 which is disproportionately higher than the other categories. 

I incorporated annotations of major terrorist events in U.S. history on my visualization to provide additional context to readers. While the events may not have a definitive correlation with the prevalence of terrorist attacks, it may capture readers' attention and serve as an invitation to do further research. 

Overall, I believe that my redesign incorporates my peers feedback and my own review of the original CSIS data and report. While it is a simple temporal line graph, I believe it captures the message of the authors without an overwhelming use of color and amount of data. 

A static version of the redesign is feature below. To view an interactive version, please use the following link: https://public.tableau.com/views/MallikasRedesignofCSISTerroristAttacksDataViz/Sheet1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 

<div class='tableauPlaceholder' id='viz1789691351573' style='position: relative'><noscript><a href='#'><img alt='Left-wing terrorist attacks are on the rise while right-wing attacks remain high in the United StatesBetween 1994 and 2025* ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;MallikasRedesignofCSISTerroristAttacksDataViz&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MallikasRedesignofCSISTerroristAttacksDataViz&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image'value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ma&#47;MallikasRedesignofCSISTerroristAttacksDataViz&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div> <script type='text/javascript'>                    var divElement = document.getElementById('viz1789691351573');var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement); </script>

## References

Byman, Daniel, and Riley McCabe. Left-Wing Terrorism and Political Violence in the United States: What the Data Tells Us. September 25, 2025. https://www.csis.org/analysis/left-wing-terrorism-and-political-violence-united-states-what-data-tells-us.


## AI acknowledgements
Google Gemini 3.6 Flash assisted with basic instructions for Tableau use. 

