# bnan430-portfolio
Portfolio Projects from my BNAN 430 course
  
Initial E-Commerce Profitability Analysis, Develop a basic Profitability set of dashboards and explaination in design, 
https://public.tableau.com/views/AdvancinginExcelandTableau-Pt_1_17894544637980/ExploratoryDash?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
If I were to changing anything, I'd spend more time editing the scatter plot.

Company Account Profitability & Tier Analysis - Develop a set of dashboard to describe Data Transformations in Net Contribution
https://public.tableau.com/views/AdvancinginExcelandTableau-Pt_2_17900599201630/AccountPortfolioDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
I'd like to change my Horizontal Bar graph so it fits to scale on the dashboard



-- Intro to Power BI, Completed on October 11, 2026 --  https://public.tableau.com/views/PowerBITrainingCertifications_17912641323870/PowerBIStory?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

One major task Power BI handles automatically that I previously did by hand in Tableau is connecting data from different tables and structuring the visual layout. In Power BI, visuals are created directly on the report canvas, whereas Tableau requires building individual worksheets and manually dragging them onto a dashboard. Power BI's autodetect feature links tables automatically, compared to Tableau where I manually verify the connections. Power BI automatically generates descriptive titles for visuals based on the fields placed in the x - axis, y - axis, or values sections, which saves a significant amount of setup time.



-- Introduction to DAX in Power BI, Completed on October 05, 2026 -- https://public.tableau.com/views/PowerBITrainingCertifications_17912641323870/PowerBIStory?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

I calculated the subcategory profit margin for Flex 3 by dividing total profit by total revenue. In Power BI, I would build this as a measure instead of a calculated column. 
This filter allows for contexts to be applied to the visual. Having the subcategory measure stored in the data table allows for VP Reyes to select different categories and set her own profit ranges. 
Without needing an Analyst to make an additional report, VP Reyes is able to make decisions about the profitability of office supply categories.


-- Data Visualization in Power BI, Completed on October 12, 2026 -- https://public.tableau.com/views/PowerBITrainingCertifications_17912641323870/PowerBIStory?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Dear Sarah,

I am ready to work with business intelligence at Southwest. In our initial e-commerce profitability analysis, I manually joined separate order tables and built exploratory Tableau dashboards to track profit margins. I would leverage Power BI's visualization modeling to link those tables in the background. Instead of relying on standard charts used for VP Reyes' account portfolio review, I would use Power BI's scatter plot to highlight which accounts sit in the wrong service tier based on its earned revenue.

Regarding our division of labor, Excel remains the right tool for quick calculations. Tableau is effective for highly customized storytelling. I prefer Power BI; it offers superior interactive capabilities, allowing non-developers to manipulate variables and uncover trends on a single report. It doesn't require separate workbooks and dashboards like Tableau. My core skills are strong; my biggest gaps is that I have only used Power BI through a virtual desktop workspace and haven't managed an online report that other users depend on for their work. I have not collaborated on a Power BI file with multiple developers. I plan to close these gaps by collaborating on practice dashboards with other developers and testing reports in a controlled environment.

-- Advancing in Excel and Tableau Pt. 3: Card Portfolio Review – Contactless Readiness --
https://public.tableau.com/views/AdvancinginExcelandTableauPt_3/ExploratoryDash?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

This visualization is designed to help Renee Castillo, Director of Card Operations, decide on early replacement of non-contact cards. I recommend targeting the standard Debit cards expiring in 2027. While the 2026 Debit cards have a slightly higher volume of non-contactless cards, replacing them now would waste budget since they expire immediately. The 2027 debit card represents the remaining gap. Replacing these 726 cards will cost the bank $5,808. 

I used a bar chart filtering non-contactless cards. This displays the exact number of cards needed to evaluate the total number of debit cards and total replacement costs. I considered using a stacked bar chart to show the percentage of cards that have tap - to - pay compared to cards without this feature. I found a percentage-based chart difficult to understand immediately and required further explanation.

One thing I would like to have added to my visualization was more data insights such as the percentage of cards expiring.


-- Advancing in Excel and Tableau Pt. 4: Card Growth Analysis - Wildcat Rewards Offer
https://public.tableau.com/app/profile/azuluaga/viz/AdvancinginExcelandTableauPt_4/ExploratoryDashboard#1
This visual is designed for Jordan Ellis, VP of Card Growth, to determine the target group for the initial Wildcat Rewards credit card pilot mailing.

I recommend targeting the southwestern regional states consisting of California, Nevada, Texas, Utah, New Mexico, and Colorado. Although Bear Down Bank is headquartered in Tucson, Arizona yields only 3 eligible customers. By targeting the adjacent states instead, the pilot reaches a pool of 131 eligible customers who meet all the guardrail requirements at the approved 670 FICO cutoff.

A highlighted geographic map of the U.S. was selected to show the targeted eligible customers. The visualization draws focus to the six brown-colored states and the number of eligible customers in each, while muting the remaining states in the background. A bar chart was considered as an additional visualization to provide more insights relating to which generation the eligible customers belong to (e.g., Baby Boomers, Millennials, Generation X). This was not chosen because it would create a visual redundant to what is already on the Exploratory Dashboard.





-- Data Storytelling with Adobe Express: Wildcat Rewards Offer --


https://new.express.adobe.com/publishedV2/urn:aaid:sc:VA6C2:246baa0d-1beb-56cb-aa30-b964b93eceba?promoid=Y69SGM5H&sdid=C4SZ2FYJ&mv=other
Nov 4, 2026

Work sample for Jordan Ellis, VP of Card Growth, to determine the target group for the initial Wildcat Rewards credit card pilot mailing. 

Design choice: I used two charts. The first is a bar chart showing the total number of eligible pilot participants with a minimum FICO of 670, and do not have a Bear Down credit card.  The second is a map recommending where to conduct the pilot. These five states have the lowest penetration of credit card holders. The adobe demonstrates how we arrived at the number of our strongest participants for the pilot to be successful.

Training completed: Nov 4, 2026 

REFERENCES

OpenAI. (2026, November 4). Various prompts to create Wilbur Wildcat, update Map and Bar charts from Advancing in Tableau and Excel Pt. 4, create a company logo and business description [Generative AI chat]. ChatGPT. 


AI PROMPTS AND TITLES:

Wilbur Wildcat:  Create a cartoon image of Wilbur Wildcat, the University of Arizona mascot, as a student who is reading a pamphlet from Bear Down Bank about saving money, with a transparent background.

Map Chart: Create a new image from the uploaded file. The new image must be graphical and highlight each state. Enlarge the numbers and make them all of the same. Make the space where the state of Arizona is transparent. Create the image with a transparent background.

Bar Chart: Create a new image from the uploaded file. The new image must be graphical. Replace the color in the bars using HEX: #106AB1. Create clear labels with backgrounds for the information above and below each bar. Create the image with a transparent background.

Company Logo:  Create a logo for my consulting company that offers data analytics and insights for businesses. The name of my company is "A2Z Consulting". Our mission is to provide our customers with the right insights in order to move their businesses forward and make the right decisions. I want the logo to represent a modern, forward-thinking approach, but at the same time, to let our customers know that we take their business seriously. I want the color scheme to align with the following palette below. I prefer to use the secondary and the accent colors:

Primary Colors - #AB0520, #0C234B 
Secondary Colors - #03132E, #1E5288, #106AB1, #81CEEB, #850000, #C62840
Accents - #7F8B5A, #3F7A7A, #85372B
Neutrals - #E5EFF7, #F2EFEA, #FFFFF

Company Description:  Based on the prompt for the company logo, I need some ideas for a description of my business and what I offer to customers.
